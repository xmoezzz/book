# `tree-sitter` `0.25.10`

Platform: Windows x86_64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/tree-sitter-05d9b3bfa86b88b1/out/libtree-sitter.a`

Owner: `tree-sitter` `0.25.10`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/src/lib.c`

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
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
    "-D_POSIX_C_SOURCE=200112L",
    "-D_DEFAULT_SOURCE",
    "-D_DARWIN_C_SOURCE",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
  "src": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.3",
      "name": "aho-corasick",
      "version": "1.1.3",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.10",
      "name": "cc",
      "version": "1.2.10",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.1",
      "name": "equivalent",
      "version": "1.0.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.15.2",
      "name": "hashbrown",
      "version": "0.15.2",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.7.1",
      "name": "indexmap",
      "version": "2.7.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
      "name": "itoa",
      "version": "1.0.14",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
      "name": "memchr",
      "version": "2.7.4",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.93",
      "name": "proc-macro2",
      "version": "1.0.93",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.93\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.93"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
      "name": "quote",
      "version": "1.0.38",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.38\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.38"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.11.1",
      "name": "regex",
      "version": "1.11.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
      "name": "regex-automata",
      "version": "0.4.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.5",
      "name": "regex-syntax",
      "version": "0.8.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.18",
      "name": "ryu",
      "version": "1.0.18",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
      "name": "serde",
      "version": "1.0.217",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
      "name": "serde_derive",
      "version": "1.0.217",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.217\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.217"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
      "name": "serde_json",
      "version": "1.0.137",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
      "name": "shlex",
      "version": "1.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#streaming-iterator@0.1.9",
      "name": "streaming-iterator",
      "version": "0.1.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.96",
      "name": "syn",
      "version": "2.0.96",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.96\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.96"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
      "name": "tree-sitter",
      "version": "0.25.10",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.5",
      "name": "tree-sitter-language",
      "version": "0.1.5",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.15",
      "name": "unicode-ident",
      "version": "1.0.15",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.15\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.15"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1920,
  "ppid": 17108,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "used:link:ef3d69d8274ed50e:c3a299325208df85:4b829b75179d6d14",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
  "pid": 1920,
  "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "used:link:ef3d69d8274ed50e:9995d22a92c2b300:4b829b75179d6d14",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
  "pid": 1920,
  "sha256": "5800f197c0be4c3f32da5874684843eff871aa25e46eee4bdc1ae0c2ae888817",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "used:link:ef3d69d8274ed50e:905e2c2b5cc770d3:4b829b75179d6d14",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
  "pid": 1920,
  "sha256": "edefc2d8bd4abec3a13ba01e9fa30a1e6024260a6eba45ad389417977cf8491d",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "used:link:ef3d69d8274ed50e:1ceda9c220daf075:4b829b75179d6d14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "path": "kernel32.lib",
  "pid": 1920,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "used:link:ef3d69d8274ed50e:1ceda9c220daf075:4b829b75179d6d14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "path": "kernel32.lib",
  "pid": 1920,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "used:link:ef3d69d8274ed50e:1ceda9c220daf075:4b829b75179d6d14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "path": "kernel32.lib",
  "pid": 1920,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "used:link:ef3d69d8274ed50e:1db9512c4d5c31e6:4b829b75179d6d14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "path": "ntdll.lib",
  "pid": 1920,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "used:link:ef3d69d8274ed50e:861f0814f9c52599:4b829b75179d6d14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "path": "userenv.lib",
  "pid": 1920,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "used:link:ef3d69d8274ed50e:50848825683fdca9:4b829b75179d6d14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "path": "ws2_32.lib",
  "pid": 1920,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "used:link:ef3d69d8274ed50e:df7d4e53c08047f7:4b829b75179d6d14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "path": "dbghelp.lib",
  "pid": 1920,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib"
  ],
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.137",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1920,
  "ppid": 17108,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "directories": [
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000148       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000198       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001b8       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001d0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001e0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001f0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000288       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002a0       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002b8       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000148       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140017148     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000198       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140017198     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400171b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001d0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400171d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001e0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400171e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400171f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140017288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002a0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400172a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002b8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400172b8     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-1920-1783962245990025800.map",
  "pid": 1920,
  "ppid": 17108,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-1920-1783962245990025800.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "exit_code": 0,
  "kind": "exec",
  "pid": 10872,
  "ppid": 15876,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "used:link:b175432e286124a9:6ed45e24be8aae8d:5fd4764f921fe814",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
  "pid": 10872,
  "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "used:link:b175432e286124a9:2cc065b40d934635:5fd4764f921fe814",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
  "pid": 10872,
  "sha256": "dfd85aa78e4d037a90d97aebc6bd1468d194276593ebf91de6bf1978a20955ad",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "used:link:b175432e286124a9:453b5d7062097c52:5fd4764f921fe814",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
  "pid": 10872,
  "sha256": "518d1157387fb13e61acf08564fd712b8f1889afbdbc6c934f981b963abb41bb",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "used:link:b175432e286124a9:1ceda9c220daf075:5fd4764f921fe814",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "path": "kernel32.lib",
  "pid": 10872,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "used:link:b175432e286124a9:1ceda9c220daf075:5fd4764f921fe814",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "path": "kernel32.lib",
  "pid": 10872,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "used:link:b175432e286124a9:1ceda9c220daf075:5fd4764f921fe814",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "path": "kernel32.lib",
  "pid": 10872,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "used:link:b175432e286124a9:1db9512c4d5c31e6:5fd4764f921fe814",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "path": "ntdll.lib",
  "pid": 10872,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "used:link:b175432e286124a9:861f0814f9c52599:5fd4764f921fe814",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "path": "userenv.lib",
  "pid": 10872,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "used:link:b175432e286124a9:50848825683fdca9:5fd4764f921fe814",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "path": "ws2_32.lib",
  "pid": 10872,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "used:link:b175432e286124a9:df7d4e53c08047f7:5fd4764f921fe814",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "path": "dbghelp.lib",
  "pid": 10872,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 27

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib"
  ],
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.217",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 10872,
  "ppid": 15876,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 29

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "directories": [
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000200       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000250       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000270       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000288       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000298       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000340       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000358       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 000000014002f200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014002f250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014002f270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014002f288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014002f298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014002f2a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014002f340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014002f358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  000000014002f388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-10872-1783962245989846800.map",
  "pid": 10872,
  "ppid": 15876,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-10872-1783962245989846800.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\rustcqzlIWp\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 8152,
  "ppid": 20364,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 31

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\rustcqzlIWp\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\rustcqzlIWp\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 32

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\rustcqzlIWp\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 8152,
  "ppid": 20364,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 33

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\rustcqzlIWp\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400bd020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400bd298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400bd2b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400bd300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400bd320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400bd338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400bd348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400bd358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400bd3f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400bd408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400bd418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400bd448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400bd460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-8152-1783962248740943900.map",
  "pid": 8152,
  "ppid": 20364,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-8152-1783962248740943900.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 34

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17632,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 35

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:3cafc974b3fb846d:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c",
  "pid": 17632,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c"
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
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 37

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 17632,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 38

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 18384,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 39

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 18384,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 40

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 696,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 41

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:4728324d84ff70fe:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c",
  "pid": 696,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 42

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c"
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
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 43

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 696,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 44

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 16460,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 45

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 16460,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 46

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-std=c11",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 11856,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 47

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-std=c11",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:7e984453d5269621:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c",
  "pid": 11856,
  "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 48

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-std=c11",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
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
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 49

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-std=c11",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 11856,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 50

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 15920,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 51

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:6c10beffbf666a94:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c",
  "pid": 15920,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 52

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c"
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
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 53

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 15920,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 54

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 2772,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 55

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 2772,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 56

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-fvisibility=hidden",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 10208,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 57

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-fvisibility=hidden",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:7e984453d5269621:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c",
  "pid": 10208,
  "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 58

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-fvisibility=hidden",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
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
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 59

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-fvisibility=hidden",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 10208,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 60

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17684,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 61

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:41e82ffbb857f75d:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c",
  "pid": 17684,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 62

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c"
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
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 63

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 17684,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 64

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 14396,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 65

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 14396,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 66

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wshadow",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 2,
  "kind": "exec",
  "pid": 7760,
  "ppid": 18532,
  "success": false,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 67

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wshadow",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:7e984453d5269621:e3b0c44298fc1c14",
  "exit_code": 2,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c",
  "pid": 7760,
  "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
  "success": false,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 68

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wshadow",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 2,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": false,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 69

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wshadow",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 2,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 7760,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": false,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 70

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 15592,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 71

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:8188b375a5411fc0:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c",
  "pid": 15592,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 72

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c"
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
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 73

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 15592,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 74

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 13552,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 75

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 13552,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 76

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wno-unused-parameter",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 2,
  "kind": "exec",
  "pid": 10484,
  "ppid": 18532,
  "success": false,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 77

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wno-unused-parameter",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:7e984453d5269621:e3b0c44298fc1c14",
  "exit_code": 2,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c",
  "pid": 10484,
  "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
  "success": false,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 78

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wno-unused-parameter",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 2,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": false,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 79

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wno-unused-parameter",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 2,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 10484,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": false,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 80

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 12744,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 81

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:006dd2358dd1babe:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c",
  "pid": 12744,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 82

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c"
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
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 83

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 12744,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 84

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 7404,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 85

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 7404,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 86

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wno-incompatible-pointer-types",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 2,
  "kind": "exec",
  "pid": 9816,
  "ppid": 18532,
  "success": false,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 87

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wno-incompatible-pointer-types",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:7e984453d5269621:e3b0c44298fc1c14",
  "exit_code": 2,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c",
  "pid": 9816,
  "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
  "success": false,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 88

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wno-incompatible-pointer-types",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 2,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": false,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 89

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Brepro",
    "-W4",
    "-Wno-incompatible-pointer-types",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 2,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 9816,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": false,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 90

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
    "-D_POSIX_C_SOURCE=200112L",
    "-D_DEFAULT_SOURCE",
    "-D_DARWIN_C_SOURCE",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1384,
  "ppid": 18532,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 91

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
    "-D_POSIX_C_SOURCE=200112L",
    "-D_DEFAULT_SOURCE",
    "-D_DARWIN_C_SOURCE",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:df41823705492ad6:963858abf4d062c3",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c",
  "pid": 1384,
  "sha256": "6bca070a6a70740c8e8af244af8a7311dbea09fbb60372376f5260facaf785f0",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 92

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
    "-D_POSIX_C_SOURCE=200112L",
    "-D_DEFAULT_SOURCE",
    "-D_DARWIN_C_SOURCE",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:d78c2d033a60f960:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
  "pid": 1384,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 93

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
    "-D_POSIX_C_SOURCE=200112L",
    "-D_DEFAULT_SOURCE",
    "-D_DARWIN_C_SOURCE",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:cl:94193cbe3619e71b:df41823705492ad6:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c",
  "pid": 1384,
  "sha256": "6bca070a6a70740c8e8af244af8a7311dbea09fbb60372376f5260facaf785f0",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 94

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
    "-D_POSIX_C_SOURCE=200112L",
    "-D_DEFAULT_SOURCE",
    "-D_DARWIN_C_SOURCE",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
  "src": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 95

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
    "-D_POSIX_C_SOURCE=200112L",
    "-D_DEFAULT_SOURCE",
    "-D_DARWIN_C_SOURCE",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
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
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 96

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
    "-I",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
    "-D_POSIX_C_SOURCE=200112L",
    "-D_DEFAULT_SOURCE",
    "-D_DARWIN_C_SOURCE",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
    "-c",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 1384,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 97

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 4324,
  "ppid": 18532,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 98

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:lib:94193cbe3619e71b:963858abf4d062c3:4633060361a2afbe",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
  "pid": 4324,
  "sha256": "2f5ced627636ec3e3823cf7ec58ef7bfcf27d18c70594f2ac6ec5aae88778952",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 99

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
  ],
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "used:lib:94193cbe3619e71b:963858abf4d062c3:c3bb58a1f9366d53",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
  "pid": 4324,
  "sha256": "2f5ced627636ec3e3823cf7ec58ef7bfcf27d18c70594f2ac6ec5aae88778952",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 100

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 101

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 102

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "cargo_pkg_name": "tree-sitter",
  "cargo_pkg_version": "0.25.10",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "pid": 4324,
  "ppid": 18532,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 103

```json
{
  "crate": "tree-sitter",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "event_id": "bsrun:e8de5016c3ad9891:c216331bae5f9379:432904e04dc5cce2",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "0.25.10",
  "_owner": {
    "crate": "tree-sitter",
    "version": "0.25.10",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
    "source": "cwd_prefix"
  }
}
```

#### Record 104

```json
{
  "crate": "serde_json",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "event_id": "bsrun:49ea300c8563b789:411ab890be90b741:b4b2287e06f42b00",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde_json-858377e4e94a61ae\\build-script-build.exe",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde_json-858377e4e94a61ae/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
  "success": true,
  "target": null,
  "version": "1.0.137",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cwd_prefix"
  }
}
```

#### Record 105

```json
{
  "crate": "serde",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "event_id": "bsrun:893a9f975b59d1cf:31ac3276dd27a923:e74fe01984eaa130",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde-4fd563a138450351\\build-script-build.exe",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde-4fd563a138450351/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
  "success": true,
  "target": null,
  "version": "1.0.217",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cwd_prefix"
  }
}
```

#### Record 106

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
  "raw_event_count": 53406,
  "parsed_event_count": 53292,
  "parse_error_count": 0,
  "command_line_event_count": 53292,
  "build_script_root_event_count": 807,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 11426,
  "dropped_event_count": 27624
}
```

#### Record 107

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 20272,
  "ppid": 18472,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T17:04:06.202013+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build-script-build.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 20272,
  "build_script_related": true,
  "build_script_target_dir": "serde_json-858377e4e94a61ae",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.137",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde_json-858377e4e94a61ae/out"
}
```

#### Record 108

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16600,
  "ppid": 18472,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T17:04:06.242862+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build-script-build.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 16600,
  "build_script_related": true,
  "build_script_target_dir": "serde-4fd563a138450351",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde-4fd563a138450351/out"
}
```

#### Record 109

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17056,
  "ppid": 16600,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T17:04:06.253651+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 16600,
  "build_script_related": true,
  "build_script_target_dir": "serde-4fd563a138450351",
  "_owner": {
    "crate": "serde",
    "version": "1.0.217",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde-4fd563a138450351/out",
  "_direct_build_script_child": true,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 110

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 18532,
  "ppid": 18472,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T17:04:09.118921+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\build-script-build.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 111

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17632,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.194710+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 112

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12708,
  "ppid": 17632,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.204658+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 113

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 18384,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.242323+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 114

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15480,
  "ppid": 18384,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.248232+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 115

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 696,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.294515+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 116

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 472,
  "ppid": 696,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.300697+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 117

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16460,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.335272+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 118

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 10468,
  "ppid": 16460,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.339998+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 119

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11856,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.381421+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 120

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 14072,
  "ppid": 11856,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.387591+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 121

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 5088,
  "ppid": 14072,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe"
  ],
  "comm": "link.exe",
  "time": "2026-07-13T17:04:09.419846+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 122

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15920,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.466255+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 123

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17452,
  "ppid": 15920,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.472245+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 124

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 2772,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.503595+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 125

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 14228,
  "ppid": 2772,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.507738+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 126

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 10208,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.546502+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 127

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 856,
  "ppid": 10208,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.552226+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 128

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17428,
  "ppid": 856,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe"
  ],
  "comm": "link.exe",
  "time": "2026-07-13T17:04:09.579716+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 129

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17684,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.614186+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 130

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 21296,
  "ppid": 17684,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.635048+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 131

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 14396,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.670057+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 132

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 9520,
  "ppid": 14396,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.674391+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 133

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 7760,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.717368+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 134

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13544,
  "ppid": 7760,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.723687+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 135

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15592,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.750279+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 136

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16268,
  "ppid": 15592,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.756249+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 137

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13552,
  "ppid": 18532,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T17:04:09.789644+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
  "root_cargo_pid": 19560,
  "build_script_root_pid": 18532,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-2d76d60e21575414"
}
```

#### Record 138

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 12744,
  "ppid": 12660,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
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
  "time": "2026-07-13T17:04:05.337886+00:00",
  "end_time": "2026-07-13T17:04:05.357081+00:00",
  "start_unix_nanos": 1783962245337885800,
  "end_unix_nanos": 1783962245357080900,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 139

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 2600,
  "ppid": 12660,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
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
  "time": "2026-07-13T17:04:05.364871+00:00",
  "end_time": "2026-07-13T17:04:05.388162+00:00",
  "start_unix_nanos": 1783962245364871200,
  "end_unix_nanos": 1783962245388162100,
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

#### Record 140

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 5668,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
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
  "time": "2026-07-13T17:04:05.689584+00:00",
  "end_time": "2026-07-13T17:04:05.709167+00:00",
  "start_unix_nanos": 1783962245689583600,
  "end_unix_nanos": 1783962245709167000,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 141

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 6616,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
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
  "time": "2026-07-13T17:04:05.719519+00:00",
  "end_time": "2026-07-13T17:04:05.742493+00:00",
  "start_unix_nanos": 1783962245719518800,
  "end_unix_nanos": 1783962245742493200,
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

#### Record 142

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 21148,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
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
  "time": "2026-07-13T17:04:05.774333+00:00",
  "end_time": "2026-07-13T17:04:05.794504+00:00",
  "start_unix_nanos": 1783962245774332800,
  "end_unix_nanos": 1783962245794503700,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 143

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 4008,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "memchr",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\src\\lib.rs",
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
    "feature=\"alloc\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"compiler_builtins\", \"core\", \"default\", \"libc\", \"logging\", \"rustc-dep-of-std\", \"std\", \"use_std\"))",
    "-C",
    "metadata=7034d8af99562755",
    "-C",
    "extra-filename=-67ed63e3e8d56c77",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name memchr --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"default\\\", \\\"libc\\\", \\\"logging\\\", \\\"rustc-dep-of-std\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=7034d8af99562755 -C extra-filename=-67ed63e3e8d56c77 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "memchr",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\src\\lib.rs",
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
    "feature=\"alloc\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"compiler_builtins\", \"core\", \"default\", \"libc\", \"logging\", \"rustc-dep-of-std\", \"std\", \"use_std\"))",
    "-C",
    "metadata=7034d8af99562755",
    "-C",
    "extra-filename=-67ed63e3e8d56c77",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.827397+00:00",
  "end_time": "2026-07-13T17:04:06.359125+00:00",
  "start_unix_nanos": 1783962245827397400,
  "end_unix_nanos": 1783962246359125200,
  "crate_name": "memchr",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 144

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 19092,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"default\", \"derive\", \"rc\", \"serde_derive\", \"std\", \"unstable\"))",
    "-C",
    "metadata=cad933f048c8506f",
    "-C",
    "extra-filename=-4fd563a138450351",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"default\\\", \\\"derive\\\", \\\"rc\\\", \\\"serde_derive\\\", \\\"std\\\", \\\"unstable\\\"))\" -C metadata=cad933f048c8506f -C extra-filename=-4fd563a138450351 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351 -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"default\", \"derive\", \"rc\", \"serde_derive\", \"std\", \"unstable\"))",
    "-C",
    "metadata=cad933f048c8506f",
    "-C",
    "extra-filename=-4fd563a138450351",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.830163+00:00",
  "end_time": "2026-07-13T17:04:06.112433+00:00",
  "start_unix_nanos": 1783962245830163000,
  "end_unix_nanos": 1783962246112433000,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351"
}
```

#### Record 145

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 16248,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "itoa",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14\\src\\lib.rs",
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
    "cfg(feature, values(\"no-panic\"))",
    "-C",
    "metadata=9cc7da6ccd78d9fa",
    "-C",
    "extra-filename=-4095bc4c8c644f32",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name itoa --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"no-panic\\\"))\" -C metadata=9cc7da6ccd78d9fa -C extra-filename=-4095bc4c8c644f32 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "itoa",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14\\src\\lib.rs",
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
    "cfg(feature, values(\"no-panic\"))",
    "-C",
    "metadata=9cc7da6ccd78d9fa",
    "-C",
    "extra-filename=-4095bc4c8c644f32",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.832875+00:00",
  "end_time": "2026-07-13T17:04:05.964383+00:00",
  "start_unix_nanos": 1783962245832875200,
  "end_unix_nanos": 1783962245964382700,
  "crate_name": "itoa",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 146

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 18260,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "equivalent",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1\\src\\lib.rs",
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
    "cfg(feature, values())",
    "-C",
    "metadata=80511815283e4320",
    "-C",
    "extra-filename=-53e6508dea69364c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name equivalent --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=80511815283e4320 -C extra-filename=-53e6508dea69364c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "equivalent",
    "--edition=2015",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1\\src\\lib.rs",
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
    "cfg(feature, values())",
    "-C",
    "metadata=80511815283e4320",
    "-C",
    "extra-filename=-53e6508dea69364c",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.836033+00:00",
  "end_time": "2026-07-13T17:04:05.916097+00:00",
  "start_unix_nanos": 1783962245836033000,
  "end_unix_nanos": 1783962245916097100,
  "crate_name": "equivalent",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 147

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 10796,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\build.rs",
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
    "feature=\"indexmap\"",
    "--cfg",
    "feature=\"preserve_order\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"arbitrary_precision\", \"default\", \"float_roundtrip\", \"indexmap\", \"preserve_order\", \"raw_value\", \"std\", \"unbounded_depth\"))",
    "-C",
    "metadata=038f9bba91cd5828",
    "-C",
    "extra-filename=-858377e4e94a61ae",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"indexmap\\\"\" --cfg \"feature=\\\"preserve_order\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"arbitrary_precision\\\", \\\"default\\\", \\\"float_roundtrip\\\", \\\"indexmap\\\", \\\"preserve_order\\\", \\\"raw_value\\\", \\\"std\\\", \\\"unbounded_depth\\\"))\" -C metadata=038f9bba91cd5828 -C extra-filename=-858377e4e94a61ae --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\build.rs",
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
    "feature=\"indexmap\"",
    "--cfg",
    "feature=\"preserve_order\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"arbitrary_precision\", \"default\", \"float_roundtrip\", \"indexmap\", \"preserve_order\", \"raw_value\", \"std\", \"unbounded_depth\"))",
    "-C",
    "metadata=038f9bba91cd5828",
    "-C",
    "extra-filename=-858377e4e94a61ae",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.838850+00:00",
  "end_time": "2026-07-13T17:04:06.113235+00:00",
  "start_unix_nanos": 1783962245838849600,
  "end_unix_nanos": 1783962246113235200,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae"
}
```

#### Record 148

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 10320,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "hashbrown",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2\\src\\lib.rs",
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
    "cfg(feature, values(\"alloc\", \"allocator-api2\", \"compiler_builtins\", \"core\", \"default\", \"default-hasher\", \"equivalent\", \"inline-more\", \"nightly\", \"raw-entry\", \"rayon\", \"rustc-dep-of-std\", \"rustc-internal-api\", \"serde\"))",
    "-C",
    "metadata=9b150f7c959252c4",
    "-C",
    "extra-filename=-0aa971b51ad432f2",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name hashbrown --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"allocator-api2\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"default\\\", \\\"default-hasher\\\", \\\"equivalent\\\", \\\"inline-more\\\", \\\"nightly\\\", \\\"raw-entry\\\", \\\"rayon\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-internal-api\\\", \\\"serde\\\"))\" -C metadata=9b150f7c959252c4 -C extra-filename=-0aa971b51ad432f2 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "hashbrown",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2\\src\\lib.rs",
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
    "cfg(feature, values(\"alloc\", \"allocator-api2\", \"compiler_builtins\", \"core\", \"default\", \"default-hasher\", \"equivalent\", \"inline-more\", \"nightly\", \"raw-entry\", \"rayon\", \"rustc-dep-of-std\", \"rustc-internal-api\", \"serde\"))",
    "-C",
    "metadata=9b150f7c959252c4",
    "-C",
    "extra-filename=-0aa971b51ad432f2",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.844405+00:00",
  "end_time": "2026-07-13T17:04:06.313485+00:00",
  "start_unix_nanos": 1783962245844405500,
  "end_unix_nanos": 1783962246313485500,
  "crate_name": "hashbrown",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 149

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 21392,
  "ppid": 18472,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=f9b15d7751a7b186 -C extra-filename=-8a85cb2cd59e9679 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.848181+00:00",
  "end_time": "2026-07-13T17:04:06.006221+00:00",
  "start_unix_nanos": 1783962245848180800,
  "end_unix_nanos": 1783962246006221000,
  "crate_name": "shlex",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 150

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 20296,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "streaming_iterator",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9\\src\\lib.rs",
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
    "cfg(feature, values(\"alloc\", \"std\"))",
    "-C",
    "metadata=435ff8906afe8180",
    "-C",
    "extra-filename=-a568802d179ad611",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name streaming_iterator --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"std\\\"))\" -C metadata=435ff8906afe8180 -C extra-filename=-a568802d179ad611 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "streaming_iterator",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9\\src\\lib.rs",
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
    "cfg(feature, values(\"alloc\", \"std\"))",
    "-C",
    "metadata=435ff8906afe8180",
    "-C",
    "extra-filename=-a568802d179ad611",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.851144+00:00",
  "end_time": "2026-07-13T17:04:06.098245+00:00",
  "start_unix_nanos": 1783962245851144400,
  "end_unix_nanos": 1783962246098244900,
  "crate_name": "streaming_iterator",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 151

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 19972,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "regex_syntax",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5\\src\\lib.rs",
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
    "feature=\"std\"",
    "--cfg",
    "feature=\"unicode\"",
    "--cfg",
    "feature=\"unicode-age\"",
    "--cfg",
    "feature=\"unicode-bool\"",
    "--cfg",
    "feature=\"unicode-case\"",
    "--cfg",
    "feature=\"unicode-gencat\"",
    "--cfg",
    "feature=\"unicode-perl\"",
    "--cfg",
    "feature=\"unicode-script\"",
    "--cfg",
    "feature=\"unicode-segment\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"arbitrary\", \"default\", \"std\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\"))",
    "-C",
    "metadata=bc2cf6bb9d6e8e62",
    "-C",
    "extra-filename=-c55cad3561091859",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name regex_syntax --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"std\\\"\" --cfg \"feature=\\\"unicode\\\"\" --cfg \"feature=\\\"unicode-age\\\"\" --cfg \"feature=\\\"unicode-bool\\\"\" --cfg \"feature=\\\"unicode-case\\\"\" --cfg \"feature=\\\"unicode-gencat\\\"\" --cfg \"feature=\\\"unicode-perl\\\"\" --cfg \"feature=\\\"unicode-script\\\"\" --cfg \"feature=\\\"unicode-segment\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arbitrary\\\", \\\"default\\\", \\\"std\\\", \\\"unicode\\\", \\\"unicode-age\\\", \\\"unicode-bool\\\", \\\"unicode-case\\\", \\\"unicode-gencat\\\", \\\"unicode-perl\\\", \\\"unicode-script\\\", \\\"unicode-segment\\\"))\" -C metadata=bc2cf6bb9d6e8e62 -C extra-filename=-c55cad3561091859 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "regex_syntax",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5\\src\\lib.rs",
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
    "feature=\"std\"",
    "--cfg",
    "feature=\"unicode\"",
    "--cfg",
    "feature=\"unicode-age\"",
    "--cfg",
    "feature=\"unicode-bool\"",
    "--cfg",
    "feature=\"unicode-case\"",
    "--cfg",
    "feature=\"unicode-gencat\"",
    "--cfg",
    "feature=\"unicode-perl\"",
    "--cfg",
    "feature=\"unicode-script\"",
    "--cfg",
    "feature=\"unicode-segment\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"arbitrary\", \"default\", \"std\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\"))",
    "-C",
    "metadata=bc2cf6bb9d6e8e62",
    "-C",
    "extra-filename=-c55cad3561091859",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.854631+00:00",
  "end_time": "2026-07-13T17:04:07.725927+00:00",
  "start_unix_nanos": 1783962245854630800,
  "end_unix_nanos": 1783962247725927100,
  "crate_name": "regex_syntax",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 152

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 20000,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "ryu",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18\\src\\lib.rs",
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
    "cfg(feature, values(\"no-panic\", \"small\"))",
    "-C",
    "metadata=a35175013979633a",
    "-C",
    "extra-filename=-0ab869bcfcaecf84",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name ryu --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"no-panic\\\", \\\"small\\\"))\" -C metadata=a35175013979633a -C extra-filename=-0ab869bcfcaecf84 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "ryu",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18\\src\\lib.rs",
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
    "cfg(feature, values(\"no-panic\", \"small\"))",
    "-C",
    "metadata=a35175013979633a",
    "-C",
    "extra-filename=-0ab869bcfcaecf84",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.857210+00:00",
  "end_time": "2026-07-13T17:04:06.006217+00:00",
  "start_unix_nanos": 1783962245857209700,
  "end_unix_nanos": 1783962246006217300,
  "crate_name": "ryu",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 153

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 20968,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "tree_sitter_language",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5\\language.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--warn=clippy::pedantic",
    "--warn=clippy::nursery",
    "--warn=clippy::cargo",
    "--allow=clippy::used_underscore_items",
    "--allow=clippy::unused_self",
    "--allow=clippy::unnecessary_wraps",
    "--allow=clippy::transmute_undefined_repr",
    "--allow=clippy::too_many_lines",
    "--deny=clippy::todo",
    "--allow=clippy::struct_field_names",
    "--allow=clippy::struct_excessive_bools",
    "--allow=clippy::string_lit_as_bytes",
    "--allow=clippy::similar_names",
    "--allow=clippy::ref_option",
    "--allow=clippy::redundant_closure_for_method_calls",
    "--allow=clippy::redundant_clone",
    "--allow=clippy::range_plus_one",
    "--allow=clippy::or_fun_call",
    "--allow=clippy::option_if_let_else",
    "--allow=clippy::multiple_crate_versions",
    "--allow=clippy::module_name_repetitions",
    "--allow=clippy::missing_panics_doc",
    "--allow=clippy::missing_errors_doc",
    "--allow=clippy::match_wildcard_for_single_variants",
    "--allow=clippy::items_after_statements",
    "--allow=clippy::inline_always",
    "--allow=clippy::if_not_else",
    "--allow=clippy::fn_params_excessive_bools",
    "--allow=clippy::fallible_impl_from",
    "--deny=clippy::dbg_macro",
    "--allow=clippy::collection_is_never_read",
    "--allow=clippy::cognitive_complexity",
    "--allow=clippy::checked_conversions",
    "--allow=clippy::cast_sign_loss",
    "--allow=clippy::cast_precision_loss",
    "--allow=clippy::cast_possible_wrap",
    "--allow=clippy::cast_possible_truncation",
    "--allow=clippy::cast_lossless",
    "--allow=clippy::branches_sharing_code",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=cd17754602491c03",
    "-C",
    "extra-filename=-53ffe3285be676f2",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name tree_sitter_language --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5\\language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps --allow=clippy::transmute_undefined_repr --allow=clippy::too_many_lines --deny=clippy::todo --allow=clippy::struct_field_names --allow=clippy::struct_excessive_bools --allow=clippy::string_lit_as_bytes --allow=clippy::similar_names --allow=clippy::ref_option --allow=clippy::redundant_closure_for_method_calls --allow=clippy::redundant_clone --allow=clippy::range_plus_one --allow=clippy::or_fun_call --allow=clippy::option_if_let_else --allow=clippy::multiple_crate_versions --allow=clippy::module_name_repetitions --allow=clippy::missing_panics_doc --allow=clippy::missing_errors_doc --allow=clippy::match_wildcard_for_single_variants --allow=clippy::items_after_statements --allow=clippy::inline_always --allow=clippy::if_not_else --allow=clippy::fn_params_excessive_bools --allow=clippy::fallible_impl_from --deny=clippy::dbg_macro --allow=clippy::collection_is_never_read --allow=clippy::cognitive_complexity --allow=clippy::checked_conversions --allow=clippy::cast_sign_loss --allow=clippy::cast_precision_loss --allow=clippy::cast_possible_wrap --allow=clippy::cast_possible_truncation --allow=clippy::cast_lossless --allow=clippy::branches_sharing_code --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=cd17754602491c03 -C extra-filename=-53ffe3285be676f2 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "tree_sitter_language",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5\\language.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--warn=clippy::pedantic",
    "--warn=clippy::nursery",
    "--warn=clippy::cargo",
    "--allow=clippy::used_underscore_items",
    "--allow=clippy::unused_self",
    "--allow=clippy::unnecessary_wraps",
    "--allow=clippy::transmute_undefined_repr",
    "--allow=clippy::too_many_lines",
    "--deny=clippy::todo",
    "--allow=clippy::struct_field_names",
    "--allow=clippy::struct_excessive_bools",
    "--allow=clippy::string_lit_as_bytes",
    "--allow=clippy::similar_names",
    "--allow=clippy::ref_option",
    "--allow=clippy::redundant_closure_for_method_calls",
    "--allow=clippy::redundant_clone",
    "--allow=clippy::range_plus_one",
    "--allow=clippy::or_fun_call",
    "--allow=clippy::option_if_let_else",
    "--allow=clippy::multiple_crate_versions",
    "--allow=clippy::module_name_repetitions",
    "--allow=clippy::missing_panics_doc",
    "--allow=clippy::missing_errors_doc",
    "--allow=clippy::match_wildcard_for_single_variants",
    "--allow=clippy::items_after_statements",
    "--allow=clippy::inline_always",
    "--allow=clippy::if_not_else",
    "--allow=clippy::fn_params_excessive_bools",
    "--allow=clippy::fallible_impl_from",
    "--deny=clippy::dbg_macro",
    "--allow=clippy::collection_is_never_read",
    "--allow=clippy::cognitive_complexity",
    "--allow=clippy::checked_conversions",
    "--allow=clippy::cast_sign_loss",
    "--allow=clippy::cast_precision_loss",
    "--allow=clippy::cast_possible_wrap",
    "--allow=clippy::cast_possible_truncation",
    "--allow=clippy::cast_lossless",
    "--allow=clippy::branches_sharing_code",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=cd17754602491c03",
    "-C",
    "extra-filename=-53ffe3285be676f2",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.861693+00:00",
  "end_time": "2026-07-13T17:04:05.935486+00:00",
  "start_unix_nanos": 1783962245861692900,
  "end_unix_nanos": 1783962245935485900,
  "crate_name": "tree_sitter_language",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 154

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 4612,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10\\src\\lib.rs",
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
    "metadata=01b3f11086860df2",
    "-C",
    "extra-filename=-e7715c40b0b1e5ba",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=01b3f11086860df2 -C extra-filename=-e7715c40b0b1e5ba --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10\\src\\lib.rs",
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
    "metadata=01b3f11086860df2",
    "-C",
    "extra-filename=-e7715c40b0b1e5ba",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:05.952849+00:00",
  "end_time": "2026-07-13T17:04:06.966965+00:00",
  "start_unix_nanos": 1783962245952849200,
  "end_unix_nanos": 1783962246966965200,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 155

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 6460,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "aho_corasick",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3\\src\\lib.rs",
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
    "feature=\"perf-literal\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"logging\", \"perf-literal\", \"std\"))",
    "-C",
    "metadata=9f43e72be9192352",
    "-C",
    "extra-filename=-698a890c685b674b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name aho_corasick --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"perf-literal\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"logging\\\", \\\"perf-literal\\\", \\\"std\\\"))\" -C metadata=9f43e72be9192352 -C extra-filename=-698a890c685b674b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "aho_corasick",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3\\src\\lib.rs",
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
    "feature=\"perf-literal\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"logging\", \"perf-literal\", \"std\"))",
    "-C",
    "metadata=9f43e72be9192352",
    "-C",
    "extra-filename=-698a890c685b674b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:06.255133+00:00",
  "end_time": "2026-07-13T17:04:07.660028+00:00",
  "start_unix_nanos": 1783962246255132800,
  "end_unix_nanos": 1783962247660028500,
  "crate_name": "aho_corasick",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 156

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 3288,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "indexmap",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=clippy::style",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"arbitrary\", \"borsh\", \"default\", \"quickcheck\", \"rayon\", \"rustc-rayon\", \"serde\", \"std\", \"test_debug\"))",
    "-C",
    "metadata=761ceb347af6d48c",
    "-C",
    "extra-filename=-172cf76332011bd8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libequivalent-53e6508dea69364c.rmeta",
    "--extern",
    "hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libhashbrown-0aa971b51ad432f2.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name indexmap --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=clippy::style --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arbitrary\\\", \\\"borsh\\\", \\\"default\\\", \\\"quickcheck\\\", \\\"rayon\\\", \\\"rustc-rayon\\\", \\\"serde\\\", \\\"std\\\", \\\"test_debug\\\"))\" -C metadata=761ceb347af6d48c -C extra-filename=-172cf76332011bd8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libequivalent-53e6508dea69364c.rmeta --extern hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libhashbrown-0aa971b51ad432f2.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "indexmap",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=clippy::style",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"arbitrary\", \"borsh\", \"default\", \"quickcheck\", \"rayon\", \"rustc-rayon\", \"serde\", \"std\", \"test_debug\"))",
    "-C",
    "metadata=761ceb347af6d48c",
    "-C",
    "extra-filename=-172cf76332011bd8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libequivalent-53e6508dea69364c.rmeta",
    "--extern",
    "hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libhashbrown-0aa971b51ad432f2.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:06.270156+00:00",
  "end_time": "2026-07-13T17:04:06.864939+00:00",
  "start_unix_nanos": 1783962246270156400,
  "end_unix_nanos": 1783962246864939300,
  "crate_name": "indexmap",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 157

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 20568,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "serde",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"default\", \"derive\", \"rc\", \"serde_derive\", \"std\", \"unstable\"))",
    "-C",
    "metadata=925db23f2ef610d0",
    "-C",
    "extra-filename=-2b0d0e9506dbd21b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "--check-cfg",
    "cfg(no_core_cstr)",
    "--check-cfg",
    "cfg(no_core_error)",
    "--check-cfg",
    "cfg(no_core_net)",
    "--check-cfg",
    "cfg(no_core_num_saturating)",
    "--check-cfg",
    "cfg(no_core_try_from)",
    "--check-cfg",
    "cfg(no_diagnostic_namespace)",
    "--check-cfg",
    "cfg(no_float_copysign)",
    "--check-cfg",
    "cfg(no_num_nonzero_signed)",
    "--check-cfg",
    "cfg(no_relaxed_trait_bounds)",
    "--check-cfg",
    "cfg(no_serde_derive)",
    "--check-cfg",
    "cfg(no_std_atomic)",
    "--check-cfg",
    "cfg(no_std_atomic64)",
    "--check-cfg",
    "cfg(no_systemtime_checked_add)",
    "--check-cfg",
    "cfg(no_target_has_atomic)"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name serde --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"default\\\", \\\"derive\\\", \\\"rc\\\", \\\"serde_derive\\\", \\\"std\\\", \\\"unstable\\\"))\" -C metadata=925db23f2ef610d0 -C extra-filename=-2b0d0e9506dbd21b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow --check-cfg cfg(no_core_cstr) --check-cfg cfg(no_core_error) --check-cfg cfg(no_core_net) --check-cfg cfg(no_core_num_saturating) --check-cfg cfg(no_core_try_from) --check-cfg cfg(no_diagnostic_namespace) --check-cfg cfg(no_float_copysign) --check-cfg cfg(no_num_nonzero_signed) --check-cfg cfg(no_relaxed_trait_bounds) --check-cfg cfg(no_serde_derive) --check-cfg cfg(no_std_atomic) --check-cfg cfg(no_std_atomic64) --check-cfg cfg(no_systemtime_checked_add) --check-cfg cfg(no_target_has_atomic)",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "serde",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"default\", \"derive\", \"rc\", \"serde_derive\", \"std\", \"unstable\"))",
    "-C",
    "metadata=925db23f2ef610d0",
    "-C",
    "extra-filename=-2b0d0e9506dbd21b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "--check-cfg",
    "cfg(no_core_cstr)",
    "--check-cfg",
    "cfg(no_core_error)",
    "--check-cfg",
    "cfg(no_core_net)",
    "--check-cfg",
    "cfg(no_core_num_saturating)",
    "--check-cfg",
    "cfg(no_core_try_from)",
    "--check-cfg",
    "cfg(no_diagnostic_namespace)",
    "--check-cfg",
    "cfg(no_float_copysign)",
    "--check-cfg",
    "cfg(no_num_nonzero_signed)",
    "--check-cfg",
    "cfg(no_relaxed_trait_bounds)",
    "--check-cfg",
    "cfg(no_serde_derive)",
    "--check-cfg",
    "cfg(no_std_atomic)",
    "--check-cfg",
    "cfg(no_std_atomic64)",
    "--check-cfg",
    "cfg(no_systemtime_checked_add)",
    "--check-cfg",
    "cfg(no_target_has_atomic)"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:06.285193+00:00",
  "end_time": "2026-07-13T17:04:08.041404+00:00",
  "start_unix_nanos": 1783962246285193200,
  "end_unix_nanos": 1783962248041403600,
  "crate_name": "serde",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 158

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 10620,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "regex_automata",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9\\src\\lib.rs",
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
    "feature=\"alloc\"",
    "--cfg",
    "feature=\"dfa-onepass\"",
    "--cfg",
    "feature=\"hybrid\"",
    "--cfg",
    "feature=\"meta\"",
    "--cfg",
    "feature=\"nfa-backtrack\"",
    "--cfg",
    "feature=\"nfa-pikevm\"",
    "--cfg",
    "feature=\"nfa-thompson\"",
    "--cfg",
    "feature=\"perf-inline\"",
    "--cfg",
    "feature=\"perf-literal\"",
    "--cfg",
    "feature=\"perf-literal-multisubstring\"",
    "--cfg",
    "feature=\"perf-literal-substring\"",
    "--cfg",
    "feature=\"std\"",
    "--cfg",
    "feature=\"syntax\"",
    "--cfg",
    "feature=\"unicode\"",
    "--cfg",
    "feature=\"unicode-age\"",
    "--cfg",
    "feature=\"unicode-bool\"",
    "--cfg",
    "feature=\"unicode-case\"",
    "--cfg",
    "feature=\"unicode-gencat\"",
    "--cfg",
    "feature=\"unicode-perl\"",
    "--cfg",
    "feature=\"unicode-script\"",
    "--cfg",
    "feature=\"unicode-segment\"",
    "--cfg",
    "feature=\"unicode-word-boundary\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"default\", \"dfa\", \"dfa-build\", \"dfa-onepass\", \"dfa-search\", \"hybrid\", \"internal-instrument\", \"internal-instrument-pikevm\", \"logging\", \"meta\", \"nfa\", \"nfa-backtrack\", \"nfa-pikevm\", \"nfa-thompson\", \"perf\", \"perf-inline\", \"perf-literal\", \"perf-literal-multisubstring\", \"perf-literal-substring\", \"std\", \"syntax\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\", \"unicode-word-boundary\"))",
    "-C",
    "metadata=e1da46555908029d",
    "-C",
    "extra-filename=-53e61e69396e7d26",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta",
    "--extern",
    "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
    "--extern",
    "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name regex_automata --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"dfa-onepass\\\"\" --cfg \"feature=\\\"hybrid\\\"\" --cfg \"feature=\\\"meta\\\"\" --cfg \"feature=\\\"nfa-backtrack\\\"\" --cfg \"feature=\\\"nfa-pikevm\\\"\" --cfg \"feature=\\\"nfa-thompson\\\"\" --cfg \"feature=\\\"perf-inline\\\"\" --cfg \"feature=\\\"perf-literal\\\"\" --cfg \"feature=\\\"perf-literal-multisubstring\\\"\" --cfg \"feature=\\\"perf-literal-substring\\\"\" --cfg \"feature=\\\"std\\\"\" --cfg \"feature=\\\"syntax\\\"\" --cfg \"feature=\\\"unicode\\\"\" --cfg \"feature=\\\"unicode-age\\\"\" --cfg \"feature=\\\"unicode-bool\\\"\" --cfg \"feature=\\\"unicode-case\\\"\" --cfg \"feature=\\\"unicode-gencat\\\"\" --cfg \"feature=\\\"unicode-perl\\\"\" --cfg \"feature=\\\"unicode-script\\\"\" --cfg \"feature=\\\"unicode-segment\\\"\" --cfg \"feature=\\\"unicode-word-boundary\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"default\\\", \\\"dfa\\\", \\\"dfa-build\\\", \\\"dfa-onepass\\\", \\\"dfa-search\\\", \\\"hybrid\\\", \\\"internal-instrument\\\", \\\"internal-instrument-pikevm\\\", \\\"logging\\\", \\\"meta\\\", \\\"nfa\\\", \\\"nfa-backtrack\\\", \\\"nfa-pikevm\\\", \\\"nfa-thompson\\\", \\\"perf\\\", \\\"perf-inline\\\", \\\"perf-literal\\\", \\\"perf-literal-multisubstring\\\", \\\"perf-literal-substring\\\", \\\"std\\\", \\\"syntax\\\", \\\"unicode\\\", \\\"unicode-age\\\", \\\"unicode-bool\\\", \\\"unicode-case\\\", \\\"unicode-gencat\\\", \\\"unicode-perl\\\", \\\"unicode-script\\\", \\\"unicode-segment\\\", \\\"unicode-word-boundary\\\"))\" -C metadata=e1da46555908029d -C extra-filename=-53e61e69396e7d26 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta --extern memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta --extern regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "regex_automata",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9\\src\\lib.rs",
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
    "feature=\"alloc\"",
    "--cfg",
    "feature=\"dfa-onepass\"",
    "--cfg",
    "feature=\"hybrid\"",
    "--cfg",
    "feature=\"meta\"",
    "--cfg",
    "feature=\"nfa-backtrack\"",
    "--cfg",
    "feature=\"nfa-pikevm\"",
    "--cfg",
    "feature=\"nfa-thompson\"",
    "--cfg",
    "feature=\"perf-inline\"",
    "--cfg",
    "feature=\"perf-literal\"",
    "--cfg",
    "feature=\"perf-literal-multisubstring\"",
    "--cfg",
    "feature=\"perf-literal-substring\"",
    "--cfg",
    "feature=\"std\"",
    "--cfg",
    "feature=\"syntax\"",
    "--cfg",
    "feature=\"unicode\"",
    "--cfg",
    "feature=\"unicode-age\"",
    "--cfg",
    "feature=\"unicode-bool\"",
    "--cfg",
    "feature=\"unicode-case\"",
    "--cfg",
    "feature=\"unicode-gencat\"",
    "--cfg",
    "feature=\"unicode-perl\"",
    "--cfg",
    "feature=\"unicode-script\"",
    "--cfg",
    "feature=\"unicode-segment\"",
    "--cfg",
    "feature=\"unicode-word-boundary\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"default\", \"dfa\", \"dfa-build\", \"dfa-onepass\", \"dfa-search\", \"hybrid\", \"internal-instrument\", \"internal-instrument-pikevm\", \"logging\", \"meta\", \"nfa\", \"nfa-backtrack\", \"nfa-pikevm\", \"nfa-thompson\", \"perf\", \"perf-inline\", \"perf-literal\", \"perf-literal-multisubstring\", \"perf-literal-substring\", \"std\", \"syntax\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\", \"unicode-word-boundary\"))",
    "-C",
    "metadata=e1da46555908029d",
    "-C",
    "extra-filename=-53e61e69396e7d26",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta",
    "--extern",
    "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
    "--extern",
    "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:07.152817+00:00",
  "end_time": "2026-07-13T17:04:09.120600+00:00",
  "start_unix_nanos": 1783962247152816900,
  "end_unix_nanos": 1783962249120600400,
  "crate_name": "regex_automata",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 159

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 20628,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "serde_json",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\src\\lib.rs",
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
    "feature=\"indexmap\"",
    "--cfg",
    "feature=\"preserve_order\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"arbitrary_precision\", \"default\", \"float_roundtrip\", \"indexmap\", \"preserve_order\", \"raw_value\", \"std\", \"unbounded_depth\"))",
    "-C",
    "metadata=b8624e194fe468fe",
    "-C",
    "extra-filename=-c86d1c8394de6867",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "indexmap=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libindexmap-172cf76332011bd8.rmeta",
    "--extern",
    "itoa=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libitoa-4095bc4c8c644f32.rmeta",
    "--extern",
    "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
    "--extern",
    "ryu=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libryu-0ab869bcfcaecf84.rmeta",
    "--extern",
    "serde=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde-2b0d0e9506dbd21b.rmeta",
    "--cap-lints",
    "allow",
    "--cfg",
    "fast_arithmetic=\"64\"",
    "--check-cfg",
    "cfg(fast_arithmetic, values(\"32\", \"64\"))"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name serde_json --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"indexmap\\\"\" --cfg \"feature=\\\"preserve_order\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"arbitrary_precision\\\", \\\"default\\\", \\\"float_roundtrip\\\", \\\"indexmap\\\", \\\"preserve_order\\\", \\\"raw_value\\\", \\\"std\\\", \\\"unbounded_depth\\\"))\" -C metadata=b8624e194fe468fe -C extra-filename=-c86d1c8394de6867 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern indexmap=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libindexmap-172cf76332011bd8.rmeta --extern itoa=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libitoa-4095bc4c8c644f32.rmeta --extern memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta --extern ryu=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libryu-0ab869bcfcaecf84.rmeta --extern serde=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde-2b0d0e9506dbd21b.rmeta --cap-lints allow --cfg \"fast_arithmetic=\\\"64\\\"\" --check-cfg \"cfg(fast_arithmetic, values(\\\"32\\\", \\\"64\\\"))\"",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "serde_json",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\src\\lib.rs",
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
    "feature=\"indexmap\"",
    "--cfg",
    "feature=\"preserve_order\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"alloc\", \"arbitrary_precision\", \"default\", \"float_roundtrip\", \"indexmap\", \"preserve_order\", \"raw_value\", \"std\", \"unbounded_depth\"))",
    "-C",
    "metadata=b8624e194fe468fe",
    "-C",
    "extra-filename=-c86d1c8394de6867",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "indexmap=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libindexmap-172cf76332011bd8.rmeta",
    "--extern",
    "itoa=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libitoa-4095bc4c8c644f32.rmeta",
    "--extern",
    "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
    "--extern",
    "ryu=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libryu-0ab869bcfcaecf84.rmeta",
    "--extern",
    "serde=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde-2b0d0e9506dbd21b.rmeta",
    "--cap-lints",
    "allow",
    "--cfg",
    "fast_arithmetic=\"64\"",
    "--check-cfg",
    "cfg(fast_arithmetic, values(\"32\", \"64\"))"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:07.958932+00:00",
  "end_time": "2026-07-13T17:04:08.587746+00:00",
  "start_unix_nanos": 1783962247958932300,
  "end_unix_nanos": 1783962248587746200,
  "crate_name": "serde_json",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 160

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 21352,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "regex",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1\\src\\lib.rs",
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
    "feature=\"perf\"",
    "--cfg",
    "feature=\"perf-backtrack\"",
    "--cfg",
    "feature=\"perf-cache\"",
    "--cfg",
    "feature=\"perf-dfa\"",
    "--cfg",
    "feature=\"perf-inline\"",
    "--cfg",
    "feature=\"perf-literal\"",
    "--cfg",
    "feature=\"perf-onepass\"",
    "--cfg",
    "feature=\"std\"",
    "--cfg",
    "feature=\"unicode\"",
    "--cfg",
    "feature=\"unicode-age\"",
    "--cfg",
    "feature=\"unicode-bool\"",
    "--cfg",
    "feature=\"unicode-case\"",
    "--cfg",
    "feature=\"unicode-gencat\"",
    "--cfg",
    "feature=\"unicode-perl\"",
    "--cfg",
    "feature=\"unicode-script\"",
    "--cfg",
    "feature=\"unicode-segment\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"logging\", \"pattern\", \"perf\", \"perf-backtrack\", \"perf-cache\", \"perf-dfa\", \"perf-dfa-full\", \"perf-inline\", \"perf-literal\", \"perf-onepass\", \"std\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\", \"unstable\", \"use_std\"))",
    "-C",
    "metadata=d0590efaab4b714d",
    "-C",
    "extra-filename=-83bebd8cc8d52f53",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta",
    "--extern",
    "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
    "--extern",
    "regex_automata=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_automata-53e61e69396e7d26.rmeta",
    "--extern",
    "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name regex --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"perf\\\"\" --cfg \"feature=\\\"perf-backtrack\\\"\" --cfg \"feature=\\\"perf-cache\\\"\" --cfg \"feature=\\\"perf-dfa\\\"\" --cfg \"feature=\\\"perf-inline\\\"\" --cfg \"feature=\\\"perf-literal\\\"\" --cfg \"feature=\\\"perf-onepass\\\"\" --cfg \"feature=\\\"std\\\"\" --cfg \"feature=\\\"unicode\\\"\" --cfg \"feature=\\\"unicode-age\\\"\" --cfg \"feature=\\\"unicode-bool\\\"\" --cfg \"feature=\\\"unicode-case\\\"\" --cfg \"feature=\\\"unicode-gencat\\\"\" --cfg \"feature=\\\"unicode-perl\\\"\" --cfg \"feature=\\\"unicode-script\\\"\" --cfg \"feature=\\\"unicode-segment\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"logging\\\", \\\"pattern\\\", \\\"perf\\\", \\\"perf-backtrack\\\", \\\"perf-cache\\\", \\\"perf-dfa\\\", \\\"perf-dfa-full\\\", \\\"perf-inline\\\", \\\"perf-literal\\\", \\\"perf-onepass\\\", \\\"std\\\", \\\"unicode\\\", \\\"unicode-age\\\", \\\"unicode-bool\\\", \\\"unicode-case\\\", \\\"unicode-gencat\\\", \\\"unicode-perl\\\", \\\"unicode-script\\\", \\\"unicode-segment\\\", \\\"unstable\\\", \\\"use_std\\\"))\" -C metadata=d0590efaab4b714d -C extra-filename=-83bebd8cc8d52f53 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta --extern memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta --extern regex_automata=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_automata-53e61e69396e7d26.rmeta --extern regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "regex",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1\\src\\lib.rs",
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
    "feature=\"perf\"",
    "--cfg",
    "feature=\"perf-backtrack\"",
    "--cfg",
    "feature=\"perf-cache\"",
    "--cfg",
    "feature=\"perf-dfa\"",
    "--cfg",
    "feature=\"perf-inline\"",
    "--cfg",
    "feature=\"perf-literal\"",
    "--cfg",
    "feature=\"perf-onepass\"",
    "--cfg",
    "feature=\"std\"",
    "--cfg",
    "feature=\"unicode\"",
    "--cfg",
    "feature=\"unicode-age\"",
    "--cfg",
    "feature=\"unicode-bool\"",
    "--cfg",
    "feature=\"unicode-case\"",
    "--cfg",
    "feature=\"unicode-gencat\"",
    "--cfg",
    "feature=\"unicode-perl\"",
    "--cfg",
    "feature=\"unicode-script\"",
    "--cfg",
    "feature=\"unicode-segment\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"logging\", \"pattern\", \"perf\", \"perf-backtrack\", \"perf-cache\", \"perf-dfa\", \"perf-dfa-full\", \"perf-inline\", \"perf-literal\", \"perf-onepass\", \"std\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\", \"unstable\", \"use_std\"))",
    "-C",
    "metadata=d0590efaab4b714d",
    "-C",
    "extra-filename=-83bebd8cc8d52f53",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta",
    "--extern",
    "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
    "--extern",
    "regex_automata=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_automata-53e61e69396e7d26.rmeta",
    "--extern",
    "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:08.447880+00:00",
  "end_time": "2026-07-13T17:04:08.779657+00:00",
  "start_unix_nanos": 1783962248447879900,
  "end_unix_nanos": 1783962248779656900,
  "crate_name": "regex",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

#### Record 161

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 16896,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "binding_rust\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--warn=clippy::pedantic",
    "--warn=clippy::nursery",
    "--warn=clippy::cargo",
    "--allow=clippy::used_underscore_items",
    "--allow=clippy::unused_self",
    "--allow=clippy::unnecessary_wraps",
    "--allow=clippy::transmute_undefined_repr",
    "--allow=clippy::too_many_lines",
    "--deny=clippy::todo",
    "--allow=clippy::struct_field_names",
    "--allow=clippy::struct_excessive_bools",
    "--allow=clippy::string_lit_as_bytes",
    "--allow=clippy::similar_names",
    "--allow=clippy::ref_option",
    "--allow=clippy::redundant_closure_for_method_calls",
    "--allow=clippy::redundant_clone",
    "--allow=clippy::range_plus_one",
    "--allow=clippy::or_fun_call",
    "--allow=clippy::option_if_let_else",
    "--allow=clippy::obfuscated_if_else",
    "--allow=clippy::needless_for_each",
    "--allow=clippy::multiple_crate_versions",
    "--allow=clippy::module_name_repetitions",
    "--allow=clippy::missing_panics_doc",
    "--allow=clippy::missing_errors_doc",
    "--allow=mismatched_lifetime_syntaxes",
    "--allow=clippy::match_wildcard_for_single_variants",
    "--allow=clippy::items_after_statements",
    "--allow=clippy::inline_always",
    "--allow=clippy::if_not_else",
    "--allow=clippy::fn_params_excessive_bools",
    "--allow=clippy::fallible_impl_from",
    "--deny=clippy::dbg_macro",
    "--allow=clippy::collection_is_never_read",
    "--allow=clippy::cognitive_complexity",
    "--allow=clippy::checked_conversions",
    "--allow=clippy::cast_sign_loss",
    "--allow=clippy::cast_precision_loss",
    "--allow=clippy::cast_possible_wrap",
    "--allow=clippy::cast_possible_truncation",
    "--allow=clippy::cast_lossless",
    "--allow=clippy::branches_sharing_code",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"bindgen\", \"default\", \"std\", \"wasm\", \"wasmtime-c-api\"))",
    "-C",
    "metadata=20932890e59f653e",
    "-C",
    "extra-filename=-2d76d60e21575414",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libcc-e7715c40b0b1e5ba.rlib",
    "--extern",
    "serde_json=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde_json-c86d1c8394de6867.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 binding_rust\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps --allow=clippy::transmute_undefined_repr --allow=clippy::too_many_lines --deny=clippy::todo --allow=clippy::struct_field_names --allow=clippy::struct_excessive_bools --allow=clippy::string_lit_as_bytes --allow=clippy::similar_names --allow=clippy::ref_option --allow=clippy::redundant_closure_for_method_calls --allow=clippy::redundant_clone --allow=clippy::range_plus_one --allow=clippy::or_fun_call --allow=clippy::option_if_let_else --allow=clippy::obfuscated_if_else --allow=clippy::needless_for_each --allow=clippy::multiple_crate_versions --allow=clippy::module_name_repetitions --allow=clippy::missing_panics_doc --allow=clippy::missing_errors_doc --allow=mismatched_lifetime_syntaxes --allow=clippy::match_wildcard_for_single_variants --allow=clippy::items_after_statements --allow=clippy::inline_always --allow=clippy::if_not_else --allow=clippy::fn_params_excessive_bools --allow=clippy::fallible_impl_from --deny=clippy::dbg_macro --allow=clippy::collection_is_never_read --allow=clippy::cognitive_complexity --allow=clippy::checked_conversions --allow=clippy::cast_sign_loss --allow=clippy::cast_precision_loss --allow=clippy::cast_possible_wrap --allow=clippy::cast_possible_truncation --allow=clippy::cast_lossless --allow=clippy::branches_sharing_code --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"bindgen\\\", \\\"default\\\", \\\"std\\\", \\\"wasm\\\", \\\"wasmtime-c-api\\\"))\" -C metadata=20932890e59f653e -C extra-filename=-2d76d60e21575414 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libcc-e7715c40b0b1e5ba.rlib --extern serde_json=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde_json-c86d1c8394de6867.rlib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "binding_rust\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--warn=clippy::pedantic",
    "--warn=clippy::nursery",
    "--warn=clippy::cargo",
    "--allow=clippy::used_underscore_items",
    "--allow=clippy::unused_self",
    "--allow=clippy::unnecessary_wraps",
    "--allow=clippy::transmute_undefined_repr",
    "--allow=clippy::too_many_lines",
    "--deny=clippy::todo",
    "--allow=clippy::struct_field_names",
    "--allow=clippy::struct_excessive_bools",
    "--allow=clippy::string_lit_as_bytes",
    "--allow=clippy::similar_names",
    "--allow=clippy::ref_option",
    "--allow=clippy::redundant_closure_for_method_calls",
    "--allow=clippy::redundant_clone",
    "--allow=clippy::range_plus_one",
    "--allow=clippy::or_fun_call",
    "--allow=clippy::option_if_let_else",
    "--allow=clippy::obfuscated_if_else",
    "--allow=clippy::needless_for_each",
    "--allow=clippy::multiple_crate_versions",
    "--allow=clippy::module_name_repetitions",
    "--allow=clippy::missing_panics_doc",
    "--allow=clippy::missing_errors_doc",
    "--allow=mismatched_lifetime_syntaxes",
    "--allow=clippy::match_wildcard_for_single_variants",
    "--allow=clippy::items_after_statements",
    "--allow=clippy::inline_always",
    "--allow=clippy::if_not_else",
    "--allow=clippy::fn_params_excessive_bools",
    "--allow=clippy::fallible_impl_from",
    "--deny=clippy::dbg_macro",
    "--allow=clippy::collection_is_never_read",
    "--allow=clippy::cognitive_complexity",
    "--allow=clippy::checked_conversions",
    "--allow=clippy::cast_sign_loss",
    "--allow=clippy::cast_precision_loss",
    "--allow=clippy::cast_possible_wrap",
    "--allow=clippy::cast_possible_truncation",
    "--allow=clippy::cast_lossless",
    "--allow=clippy::branches_sharing_code",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"bindgen\", \"default\", \"std\", \"wasm\", \"wasmtime-c-api\"))",
    "-C",
    "metadata=20932890e59f653e",
    "-C",
    "extra-filename=-2d76d60e21575414",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libcc-e7715c40b0b1e5ba.rlib",
    "--extern",
    "serde_json=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde_json-c86d1c8394de6867.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:08.607595+00:00",
  "end_time": "2026-07-13T17:04:08.979057+00:00",
  "start_unix_nanos": 1783962248607594800,
  "end_unix_nanos": 1783962248979056700,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414"
}
```

#### Record 162

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "tree-sitter:0.25.10:13240",
  "root_process_pid": 19560,
  "pid": 20068,
  "ppid": 18472,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "tree_sitter",
    "--edition=2021",
    "binding_rust\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--warn=clippy::pedantic",
    "--warn=clippy::nursery",
    "--warn=clippy::cargo",
    "--allow=clippy::used_underscore_items",
    "--allow=clippy::unused_self",
    "--allow=clippy::unnecessary_wraps",
    "--allow=clippy::transmute_undefined_repr",
    "--allow=clippy::too_many_lines",
    "--deny=clippy::todo",
    "--allow=clippy::struct_field_names",
    "--allow=clippy::struct_excessive_bools",
    "--allow=clippy::string_lit_as_bytes",
    "--allow=clippy::similar_names",
    "--allow=clippy::ref_option",
    "--allow=clippy::redundant_closure_for_method_calls",
    "--allow=clippy::redundant_clone",
    "--allow=clippy::range_plus_one",
    "--allow=clippy::or_fun_call",
    "--allow=clippy::option_if_let_else",
    "--allow=clippy::obfuscated_if_else",
    "--allow=clippy::needless_for_each",
    "--allow=clippy::multiple_crate_versions",
    "--allow=clippy::module_name_repetitions",
    "--allow=clippy::missing_panics_doc",
    "--allow=clippy::missing_errors_doc",
    "--allow=mismatched_lifetime_syntaxes",
    "--allow=clippy::match_wildcard_for_single_variants",
    "--allow=clippy::items_after_statements",
    "--allow=clippy::inline_always",
    "--allow=clippy::if_not_else",
    "--allow=clippy::fn_params_excessive_bools",
    "--allow=clippy::fallible_impl_from",
    "--deny=clippy::dbg_macro",
    "--allow=clippy::collection_is_never_read",
    "--allow=clippy::cognitive_complexity",
    "--allow=clippy::checked_conversions",
    "--allow=clippy::cast_sign_loss",
    "--allow=clippy::cast_precision_loss",
    "--allow=clippy::cast_possible_wrap",
    "--allow=clippy::cast_possible_truncation",
    "--allow=clippy::cast_lossless",
    "--allow=clippy::branches_sharing_code",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"bindgen\", \"default\", \"std\", \"wasm\", \"wasmtime-c-api\"))",
    "-C",
    "metadata=73a8caa36a17947b",
    "-C",
    "extra-filename=-4398dfe1415a54f2",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "regex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex-83bebd8cc8d52f53.rmeta",
    "--extern",
    "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
    "--extern",
    "streaming_iterator=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libstreaming_iterator-a568802d179ad611.rmeta",
    "--extern",
    "tree_sitter_language=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libtree_sitter_language-53ffe3285be676f2.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
    "-l",
    "static=tree-sitter"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name tree_sitter --edition=2021 binding_rust\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps --allow=clippy::transmute_undefined_repr --allow=clippy::too_many_lines --deny=clippy::todo --allow=clippy::struct_field_names --allow=clippy::struct_excessive_bools --allow=clippy::string_lit_as_bytes --allow=clippy::similar_names --allow=clippy::ref_option --allow=clippy::redundant_closure_for_method_calls --allow=clippy::redundant_clone --allow=clippy::range_plus_one --allow=clippy::or_fun_call --allow=clippy::option_if_let_else --allow=clippy::obfuscated_if_else --allow=clippy::needless_for_each --allow=clippy::multiple_crate_versions --allow=clippy::module_name_repetitions --allow=clippy::missing_panics_doc --allow=clippy::missing_errors_doc --allow=mismatched_lifetime_syntaxes --allow=clippy::match_wildcard_for_single_variants --allow=clippy::items_after_statements --allow=clippy::inline_always --allow=clippy::if_not_else --allow=clippy::fn_params_excessive_bools --allow=clippy::fallible_impl_from --deny=clippy::dbg_macro --allow=clippy::collection_is_never_read --allow=clippy::cognitive_complexity --allow=clippy::checked_conversions --allow=clippy::cast_sign_loss --allow=clippy::cast_precision_loss --allow=clippy::cast_possible_wrap --allow=clippy::cast_possible_truncation --allow=clippy::cast_lossless --allow=clippy::branches_sharing_code --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"bindgen\\\", \\\"default\\\", \\\"std\\\", \\\"wasm\\\", \\\"wasmtime-c-api\\\"))\" -C metadata=73a8caa36a17947b -C extra-filename=-4398dfe1415a54f2 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern regex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex-83bebd8cc8d52f53.rmeta --extern regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta --extern streaming_iterator=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libstreaming_iterator-a568802d179ad611.rmeta --extern tree_sitter_language=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libtree_sitter_language-53ffe3285be676f2.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out -l static=tree-sitter",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "tree_sitter",
    "--edition=2021",
    "binding_rust\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--warn=clippy::pedantic",
    "--warn=clippy::nursery",
    "--warn=clippy::cargo",
    "--allow=clippy::used_underscore_items",
    "--allow=clippy::unused_self",
    "--allow=clippy::unnecessary_wraps",
    "--allow=clippy::transmute_undefined_repr",
    "--allow=clippy::too_many_lines",
    "--deny=clippy::todo",
    "--allow=clippy::struct_field_names",
    "--allow=clippy::struct_excessive_bools",
    "--allow=clippy::string_lit_as_bytes",
    "--allow=clippy::similar_names",
    "--allow=clippy::ref_option",
    "--allow=clippy::redundant_closure_for_method_calls",
    "--allow=clippy::redundant_clone",
    "--allow=clippy::range_plus_one",
    "--allow=clippy::or_fun_call",
    "--allow=clippy::option_if_let_else",
    "--allow=clippy::obfuscated_if_else",
    "--allow=clippy::needless_for_each",
    "--allow=clippy::multiple_crate_versions",
    "--allow=clippy::module_name_repetitions",
    "--allow=clippy::missing_panics_doc",
    "--allow=clippy::missing_errors_doc",
    "--allow=mismatched_lifetime_syntaxes",
    "--allow=clippy::match_wildcard_for_single_variants",
    "--allow=clippy::items_after_statements",
    "--allow=clippy::inline_always",
    "--allow=clippy::if_not_else",
    "--allow=clippy::fn_params_excessive_bools",
    "--allow=clippy::fallible_impl_from",
    "--deny=clippy::dbg_macro",
    "--allow=clippy::collection_is_never_read",
    "--allow=clippy::cognitive_complexity",
    "--allow=clippy::checked_conversions",
    "--allow=clippy::cast_sign_loss",
    "--allow=clippy::cast_precision_loss",
    "--allow=clippy::cast_possible_wrap",
    "--allow=clippy::cast_possible_truncation",
    "--allow=clippy::cast_lossless",
    "--allow=clippy::branches_sharing_code",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"bindgen\", \"default\", \"std\", \"wasm\", \"wasmtime-c-api\"))",
    "-C",
    "metadata=73a8caa36a17947b",
    "-C",
    "extra-filename=-4398dfe1415a54f2",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
    "--extern",
    "regex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex-83bebd8cc8d52f53.rmeta",
    "--extern",
    "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
    "--extern",
    "streaming_iterator=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libstreaming_iterator-a568802d179ad611.rmeta",
    "--extern",
    "tree_sitter_language=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libtree_sitter_language-53ffe3285be676f2.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
    "-l",
    "static=tree-sitter"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T17:04:10.602295+00:00",
  "end_time": "2026-07-13T17:04:11.442754+00:00",
  "start_unix_nanos": 1783962250602295400,
  "end_unix_nanos": 1783962251442753800,
  "crate_name": "tree_sitter",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T17:04:12.500517+00:00",
  "crate": "tree-sitter",
  "version": "0.25.10",
  "duration_seconds": 30.150557100074366,
  "trace_record_count": 137,
  "trace_owner_summary": {
    "owner_package_count": 22,
    "owner_packages": [
      {
        "crate": "tree-sitter-language",
        "version": "0.1.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.5/Cargo.toml"
      },
      {
        "crate": "streaming-iterator",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#streaming-iterator@0.1.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.15",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.15",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.15/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.3",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.3/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.93",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.93",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.93",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.93/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.5",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.5",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.5/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137/Cargo.toml"
      },
      {
        "crate": "equivalent",
        "version": "1.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.1/Cargo.toml"
      },
      {
        "crate": "hashbrown",
        "version": "0.15.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.15.2",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.15.2",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.15.2/Cargo.toml"
      },
      {
        "crate": "indexmap",
        "version": "2.7.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.7.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.7.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.7.1/Cargo.toml"
      },
      {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217/Cargo.toml"
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
        "version": "1.0.38",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.11.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.11.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "1.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.18",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.18",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.18/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.96",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.96",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.96",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.96/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.10",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.10",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.10",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.10/Cargo.toml"
      }
    ],
    "attributed_event_count": 104,
    "unattributed_event_count": 33,
    "owners": [
      {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "event_count": 74,
        "kind_counts": {
          "exec": 20,
          "link": 14,
          "exec_context": 20,
          "resolved_link": 1,
          "used_input": 16,
          "compile": 1,
          "archive": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "serde",
        "version": "1.0.217",
        "event_count": 15,
        "kind_counts": {
          "exec": 1,
          "used_input": 10,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "serde_json",
        "version": "1.0.137",
        "event_count": 15,
        "kind_counts": {
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.3",
          "name": "aho-corasick",
          "version": "1.1.3",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.10",
          "name": "cc",
          "version": "1.2.10",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.1",
          "name": "equivalent",
          "version": "1.0.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.15.2",
          "name": "hashbrown",
          "version": "0.15.2",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.7.1",
          "name": "indexmap",
          "version": "2.7.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
          "name": "itoa",
          "version": "1.0.14",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
          "name": "memchr",
          "version": "2.7.4",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.93",
          "name": "proc-macro2",
          "version": "1.0.93",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.93\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\proc-macro2-1.0.93"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
          "name": "quote",
          "version": "1.0.38",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.38\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\quote-1.0.38"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.11.1",
          "name": "regex",
          "version": "1.11.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
          "name": "regex-automata",
          "version": "0.4.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.5",
          "name": "regex-syntax",
          "version": "0.8.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.18",
          "name": "ryu",
          "version": "1.0.18",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
          "name": "serde",
          "version": "1.0.217",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
          "name": "serde_derive",
          "version": "1.0.217",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.217\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_derive-1.0.217"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
          "name": "serde_json",
          "version": "1.0.137",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
          "name": "shlex",
          "version": "1.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#streaming-iterator@0.1.9",
          "name": "streaming-iterator",
          "version": "0.1.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.96",
          "name": "syn",
          "version": "2.0.96",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.96\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\syn-2.0.96"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
          "name": "tree-sitter",
          "version": "0.25.10",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.5",
          "name": "tree-sitter-language",
          "version": "0.1.5",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.15",
          "name": "unicode-ident",
          "version": "1.0.15",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.15\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\unicode-ident-1.0.15"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1920,
      "ppid": 17108,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "used:link:ef3d69d8274ed50e:c3a299325208df85:4b829b75179d6d14",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
      "pid": 1920,
      "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "used:link:ef3d69d8274ed50e:9995d22a92c2b300:4b829b75179d6d14",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
      "pid": 1920,
      "sha256": "5800f197c0be4c3f32da5874684843eff871aa25e46eee4bdc1ae0c2ae888817",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "used:link:ef3d69d8274ed50e:905e2c2b5cc770d3:4b829b75179d6d14",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
      "pid": 1920,
      "sha256": "edefc2d8bd4abec3a13ba01e9fa30a1e6024260a6eba45ad389417977cf8491d",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "used:link:ef3d69d8274ed50e:1ceda9c220daf075:4b829b75179d6d14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "path": "kernel32.lib",
      "pid": 1920,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "used:link:ef3d69d8274ed50e:1ceda9c220daf075:4b829b75179d6d14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "path": "kernel32.lib",
      "pid": 1920,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "used:link:ef3d69d8274ed50e:1ceda9c220daf075:4b829b75179d6d14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "path": "kernel32.lib",
      "pid": 1920,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "used:link:ef3d69d8274ed50e:1db9512c4d5c31e6:4b829b75179d6d14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "path": "ntdll.lib",
      "pid": 1920,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "used:link:ef3d69d8274ed50e:861f0814f9c52599:4b829b75179d6d14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "path": "userenv.lib",
      "pid": 1920,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "used:link:ef3d69d8274ed50e:50848825683fdca9:4b829b75179d6d14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "path": "ws2_32.lib",
      "pid": 1920,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "used:link:ef3d69d8274ed50e:df7d4e53c08047f7:4b829b75179d6d14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "path": "dbghelp.lib",
      "pid": 1920,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib"
      ],
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.137",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1920,
      "ppid": 17108,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\rustc28LehF\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.build_script_build.7dcac5c1f4cae53-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.36r36nuq226kjzdnxmy5xaon4.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build_script_build-858377e4e94a61ae.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "directories": [
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000148       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000198       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001b8       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001d0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001e0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001f0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000288       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002a0       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002b8       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000148       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000148       \\177KERNEL32_NULL_THUNK_DATA 0000000140017148     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000198       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000198       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140017198     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001b8       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400171b8     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001d0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001d0       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400171d0     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001e0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001e0       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400171e0     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000001f0       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400171f0     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:00000288       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140017288     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002a0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002a0       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400172a0     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002b8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\0002:000002b8       \\177ntdll_NULL_THUNK_DATA  00000001400172b8     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-1920-1783962245990025800.map",
      "pid": 1920,
      "ppid": 17108,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-1920-1783962245990025800.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "exit_code": 0,
      "kind": "exec",
      "pid": 10872,
      "ppid": 15876,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "used:link:b175432e286124a9:6ed45e24be8aae8d:5fd4764f921fe814",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
      "pid": 10872,
      "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "used:link:b175432e286124a9:2cc065b40d934635:5fd4764f921fe814",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
      "pid": 10872,
      "sha256": "dfd85aa78e4d037a90d97aebc6bd1468d194276593ebf91de6bf1978a20955ad",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "used:link:b175432e286124a9:453b5d7062097c52:5fd4764f921fe814",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
      "pid": 10872,
      "sha256": "518d1157387fb13e61acf08564fd712b8f1889afbdbc6c934f981b963abb41bb",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "used:link:b175432e286124a9:1ceda9c220daf075:5fd4764f921fe814",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "path": "kernel32.lib",
      "pid": 10872,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "used:link:b175432e286124a9:1ceda9c220daf075:5fd4764f921fe814",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "path": "kernel32.lib",
      "pid": 10872,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "used:link:b175432e286124a9:1ceda9c220daf075:5fd4764f921fe814",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "path": "kernel32.lib",
      "pid": 10872,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "used:link:b175432e286124a9:1db9512c4d5c31e6:5fd4764f921fe814",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "path": "ntdll.lib",
      "pid": 10872,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "used:link:b175432e286124a9:861f0814f9c52599:5fd4764f921fe814",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "path": "userenv.lib",
      "pid": 10872,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "used:link:b175432e286124a9:50848825683fdca9:5fd4764f921fe814",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "path": "ws2_32.lib",
      "pid": 10872,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "used:link:b175432e286124a9:df7d4e53c08047f7:5fd4764f921fe814",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "path": "dbghelp.lib",
      "pid": 10872,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib"
      ],
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.217",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 10872,
      "ppid": 15876,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\rustcLHYv87\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.build_script_build.3fa0ed3316417f32-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.65jf652tygzc1or34iokt3smn.rcgu.o",
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
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build_script_build-4fd563a138450351.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "directories": [
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000200       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000250       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000270       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000288       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000298       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000340       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000358       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000388       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 000000014002f200     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000250       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 000000014002f250     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000270       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 000000014002f270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 000000014002f288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 000000014002f298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 000000014002f2a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000340       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 000000014002f340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 000000014002f358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000388       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  000000014002f388     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-10872-1783962245989846800.map",
      "pid": 10872,
      "ppid": 15876,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-10872-1783962245989846800.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\rustcqzlIWp\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 8152,
      "ppid": 20364,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\rustcqzlIWp\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\rustcqzlIWp\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\rustcqzlIWp\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 8152,
      "ppid": 20364,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\rustcqzlIWp\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000300       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000320       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000003f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000418       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000448       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000460       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400bd020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400bd298     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400bd2b0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000300       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400bd300     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000320       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400bd320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400bd338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400bd348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400bd358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000003f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400bd3f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400bd408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000418       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400bd418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000448       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400bd448     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000460       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400bd460     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-8152-1783962248740943900.map",
      "pid": 8152,
      "ppid": 20364,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-link-link-8152-1783962248740943900.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17632,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:3cafc974b3fb846d:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c",
      "pid": 17632,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c"
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
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\6591334819659826976detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 17632,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 18384,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 18384,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 696,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:4728324d84ff70fe:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c",
      "pid": 696,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c"
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
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8144297299288479153detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 696,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 16460,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 16460,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-std=c11",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 11856,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-std=c11",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:7e984453d5269621:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c",
      "pid": 11856,
      "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-std=c11",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
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
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-std=c11",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 11856,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 15920,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:6c10beffbf666a94:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c",
      "pid": 15920,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c"
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
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9221657299257430954detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 15920,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 2772,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 2772,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-fvisibility=hidden",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 10208,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-fvisibility=hidden",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:7e984453d5269621:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c",
      "pid": 10208,
      "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-fvisibility=hidden",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
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
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-fvisibility=hidden",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 10208,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17684,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:41e82ffbb857f75d:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c",
      "pid": 17684,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c"
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
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\8210900562858340406detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 17684,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 14396,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 14396,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wshadow",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 2,
      "kind": "exec",
      "pid": 7760,
      "ppid": 18532,
      "success": false,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wshadow",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:7e984453d5269621:e3b0c44298fc1c14",
      "exit_code": 2,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c",
      "pid": 7760,
      "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
      "success": false,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wshadow",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 2,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": false,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wshadow",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 2,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 7760,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": false,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 15592,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:8188b375a5411fc0:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c",
      "pid": 15592,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c"
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
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\4353834153564186815detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 15592,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 13552,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 13552,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wno-unused-parameter",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 2,
      "kind": "exec",
      "pid": 10484,
      "ppid": 18532,
      "success": false,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wno-unused-parameter",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:7e984453d5269621:e3b0c44298fc1c14",
      "exit_code": 2,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c",
      "pid": 10484,
      "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
      "success": false,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wno-unused-parameter",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 2,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": false,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wno-unused-parameter",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 2,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 10484,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": false,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 12744,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:006dd2358dd1babe:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c",
      "pid": 12744,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c"
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
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\1788765405361793635detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 12744,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 7404,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 7404,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wno-incompatible-pointer-types",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 2,
      "kind": "exec",
      "pid": 9816,
      "ppid": 18532,
      "success": false,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wno-incompatible-pointer-types",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:7e984453d5269621:e3b0c44298fc1c14",
      "exit_code": 2,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c",
      "pid": 9816,
      "sha256": "65d2fad425e300ae19bd229a513aa7564086a7f0feb9405f806c70b2366ad59a",
      "success": false,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wno-incompatible-pointer-types",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 2,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": false,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-Wno-incompatible-pointer-types",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\flag_check.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 2,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 9816,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": false,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
        "-D_POSIX_C_SOURCE=200112L",
        "-D_DEFAULT_SOURCE",
        "-D_DARWIN_C_SOURCE",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1384,
      "ppid": 18532,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
        "-D_POSIX_C_SOURCE=200112L",
        "-D_DEFAULT_SOURCE",
        "-D_DARWIN_C_SOURCE",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:df41823705492ad6:963858abf4d062c3",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c",
      "pid": 1384,
      "sha256": "6bca070a6a70740c8e8af244af8a7311dbea09fbb60372376f5260facaf785f0",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
        "-D_POSIX_C_SOURCE=200112L",
        "-D_DEFAULT_SOURCE",
        "-D_DARWIN_C_SOURCE",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:d78c2d033a60f960:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
      "pid": 1384,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
        "-D_POSIX_C_SOURCE=200112L",
        "-D_DEFAULT_SOURCE",
        "-D_DARWIN_C_SOURCE",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:cl:94193cbe3619e71b:df41823705492ad6:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c",
      "pid": 1384,
      "sha256": "6bca070a6a70740c8e8af244af8a7311dbea09fbb60372376f5260facaf785f0",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
        "-D_POSIX_C_SOURCE=200112L",
        "-D_DEFAULT_SOURCE",
        "-D_DARWIN_C_SOURCE",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
      "src": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
        "-D_POSIX_C_SOURCE=200112L",
        "-D_DEFAULT_SOURCE",
        "-D_DARWIN_C_SOURCE",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
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
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
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
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\wasm",
        "-I",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\include",
        "-D_POSIX_C_SOURCE=200112L",
        "-D_DEFAULT_SOURCE",
        "-D_DARWIN_C_SOURCE",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
        "-c",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\src\\lib.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 1384,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 4324,
      "ppid": 18532,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:lib:94193cbe3619e71b:963858abf4d062c3:4633060361a2afbe",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
      "pid": 4324,
      "sha256": "2f5ced627636ec3e3823cf7ec58ef7bfcf27d18c70594f2ac6ec5aae88778952",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
      ],
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "used:lib:94193cbe3619e71b:963858abf4d062c3:c3bb58a1f9366d53",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o",
      "pid": 4324,
      "sha256": "2f5ced627636ec3e3823cf7ec58ef7bfcf27d18c70594f2ac6ec5aae88778952",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\libtree-sitter.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out\\9d101ca0d5afdee2-lib.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "cargo_pkg_name": "tree-sitter",
      "cargo_pkg_version": "0.25.10",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "pid": 4324,
      "ppid": 18532,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "tree-sitter",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "event_id": "bsrun:e8de5016c3ad9891:c216331bae5f9379:432904e04dc5cce2",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "0.25.10",
      "_owner": {
        "crate": "tree-sitter",
        "version": "0.25.10",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10#tree-sitter@0.25.10",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "serde_json",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "event_id": "bsrun:49ea300c8563b789:411ab890be90b741:b4b2287e06f42b00",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde_json-858377e4e94a61ae\\build-script-build.exe",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde_json-858377e4e94a61ae/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
      "success": true,
      "target": null,
      "version": "1.0.137",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.137",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.137",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.137",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "serde",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "event_id": "bsrun:893a9f975b59d1cf:31ac3276dd27a923:e74fe01984eaa130",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde-4fd563a138450351\\build-script-build.exe",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q8vp_7qg/src/tree-sitter-0.25.10/target/debug/build/serde-4fd563a138450351/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
      "success": true,
      "target": null,
      "version": "1.0.217",
      "_owner": {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
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
      "raw_event_count": 53406,
      "parsed_event_count": 53292,
      "parse_error_count": 0,
      "command_line_event_count": 53292,
      "build_script_root_event_count": 807,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 11426,
      "dropped_event_count": 27624
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 20272,
      "ppid": 18472,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T17:04:06.202013+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae\\build-script-build.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 20272,
      "build_script_related": true,
      "build_script_target_dir": "serde_json-858377e4e94a61ae"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16600,
      "ppid": 18472,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T17:04:06.242862+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351\\build-script-build.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 16600,
      "build_script_related": true,
      "build_script_target_dir": "serde-4fd563a138450351"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17056,
      "ppid": 16600,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T17:04:06.253651+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 16600,
      "build_script_related": true,
      "build_script_target_dir": "serde-4fd563a138450351"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 18532,
      "ppid": 18472,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T17:04:09.118921+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414\\build-script-build.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17632,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.194710+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12708,
      "ppid": 17632,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.204658+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 18384,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.242323+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15480,
      "ppid": 18384,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.248232+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 696,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.294515+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 472,
      "ppid": 696,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.300697+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16460,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.335272+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 10468,
      "ppid": 16460,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.339998+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11856,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.381421+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 14072,
      "ppid": 11856,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.387591+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 5088,
      "ppid": 14072,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe"
      ],
      "comm": "link.exe",
      "time": "2026-07-13T17:04:09.419846+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15920,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.466255+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17452,
      "ppid": 15920,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.472245+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 2772,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.503595+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 14228,
      "ppid": 2772,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.507738+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 10208,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.546502+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 856,
      "ppid": 10208,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.552226+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17428,
      "ppid": 856,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe"
      ],
      "comm": "link.exe",
      "time": "2026-07-13T17:04:09.579716+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\link.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17684,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.614186+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 21296,
      "ppid": 17684,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.635048+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 14396,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.670057+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 9520,
      "ppid": 14396,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.674391+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 7760,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.717368+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13544,
      "ppid": 7760,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.723687+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15592,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.750279+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16268,
      "ppid": 15592,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.756249+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13552,
      "ppid": 18532,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T17:04:09.789644+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\.tmp\\native-trace-19048-1783962245103\\shims\\cl.exe",
      "root_cargo_pid": 19560,
      "build_script_root_pid": 18532,
      "build_script_related": true,
      "build_script_target_dir": "tree-sitter-2d76d60e21575414"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 12744,
      "ppid": 12660,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
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
      "time": "2026-07-13T17:04:05.337886+00:00",
      "end_time": "2026-07-13T17:04:05.357081+00:00",
      "start_unix_nanos": 1783962245337885800,
      "end_unix_nanos": 1783962245357080900,
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
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 2600,
      "ppid": 12660,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
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
      "time": "2026-07-13T17:04:05.364871+00:00",
      "end_time": "2026-07-13T17:04:05.388162+00:00",
      "start_unix_nanos": 1783962245364871200,
      "end_unix_nanos": 1783962245388162100,
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
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 5668,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
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
      "time": "2026-07-13T17:04:05.689584+00:00",
      "end_time": "2026-07-13T17:04:05.709167+00:00",
      "start_unix_nanos": 1783962245689583600,
      "end_unix_nanos": 1783962245709167000,
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
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 6616,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
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
      "time": "2026-07-13T17:04:05.719519+00:00",
      "end_time": "2026-07-13T17:04:05.742493+00:00",
      "start_unix_nanos": 1783962245719518800,
      "end_unix_nanos": 1783962245742493200,
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
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 21148,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
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
      "time": "2026-07-13T17:04:05.774333+00:00",
      "end_time": "2026-07-13T17:04:05.794504+00:00",
      "start_unix_nanos": 1783962245774332800,
      "end_unix_nanos": 1783962245794503700,
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
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 4008,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "memchr",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\src\\lib.rs",
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
        "feature=\"alloc\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"compiler_builtins\", \"core\", \"default\", \"libc\", \"logging\", \"rustc-dep-of-std\", \"std\", \"use_std\"))",
        "-C",
        "metadata=7034d8af99562755",
        "-C",
        "extra-filename=-67ed63e3e8d56c77",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name memchr --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"default\\\", \\\"libc\\\", \\\"logging\\\", \\\"rustc-dep-of-std\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=7034d8af99562755 -C extra-filename=-67ed63e3e8d56c77 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "memchr",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\memchr-2.7.4\\src\\lib.rs",
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
        "feature=\"alloc\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"compiler_builtins\", \"core\", \"default\", \"libc\", \"logging\", \"rustc-dep-of-std\", \"std\", \"use_std\"))",
        "-C",
        "metadata=7034d8af99562755",
        "-C",
        "extra-filename=-67ed63e3e8d56c77",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.827397+00:00",
      "end_time": "2026-07-13T17:04:06.359125+00:00",
      "start_unix_nanos": 1783962245827397400,
      "end_unix_nanos": 1783962246359125200,
      "crate_name": "memchr",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 19092,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"default\", \"derive\", \"rc\", \"serde_derive\", \"std\", \"unstable\"))",
        "-C",
        "metadata=cad933f048c8506f",
        "-C",
        "extra-filename=-4fd563a138450351",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"default\\\", \\\"derive\\\", \\\"rc\\\", \\\"serde_derive\\\", \\\"std\\\", \\\"unstable\\\"))\" -C metadata=cad933f048c8506f -C extra-filename=-4fd563a138450351 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351 -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"default\", \"derive\", \"rc\", \"serde_derive\", \"std\", \"unstable\"))",
        "-C",
        "metadata=cad933f048c8506f",
        "-C",
        "extra-filename=-4fd563a138450351",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.830163+00:00",
      "end_time": "2026-07-13T17:04:06.112433+00:00",
      "start_unix_nanos": 1783962245830163000,
      "end_unix_nanos": 1783962246112433000,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde-4fd563a138450351"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 16248,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "itoa",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14\\src\\lib.rs",
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
        "cfg(feature, values(\"no-panic\"))",
        "-C",
        "metadata=9cc7da6ccd78d9fa",
        "-C",
        "extra-filename=-4095bc4c8c644f32",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name itoa --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"no-panic\\\"))\" -C metadata=9cc7da6ccd78d9fa -C extra-filename=-4095bc4c8c644f32 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "itoa",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\itoa-1.0.14\\src\\lib.rs",
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
        "cfg(feature, values(\"no-panic\"))",
        "-C",
        "metadata=9cc7da6ccd78d9fa",
        "-C",
        "extra-filename=-4095bc4c8c644f32",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.832875+00:00",
      "end_time": "2026-07-13T17:04:05.964383+00:00",
      "start_unix_nanos": 1783962245832875200,
      "end_unix_nanos": 1783962245964382700,
      "crate_name": "itoa",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 18260,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "equivalent",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1\\src\\lib.rs",
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
        "cfg(feature, values())",
        "-C",
        "metadata=80511815283e4320",
        "-C",
        "extra-filename=-53e6508dea69364c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name equivalent --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=80511815283e4320 -C extra-filename=-53e6508dea69364c --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "equivalent",
        "--edition=2015",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\equivalent-1.0.1\\src\\lib.rs",
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
        "cfg(feature, values())",
        "-C",
        "metadata=80511815283e4320",
        "-C",
        "extra-filename=-53e6508dea69364c",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.836033+00:00",
      "end_time": "2026-07-13T17:04:05.916097+00:00",
      "start_unix_nanos": 1783962245836033000,
      "end_unix_nanos": 1783962245916097100,
      "crate_name": "equivalent",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 10796,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\build.rs",
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
        "feature=\"indexmap\"",
        "--cfg",
        "feature=\"preserve_order\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"arbitrary_precision\", \"default\", \"float_roundtrip\", \"indexmap\", \"preserve_order\", \"raw_value\", \"std\", \"unbounded_depth\"))",
        "-C",
        "metadata=038f9bba91cd5828",
        "-C",
        "extra-filename=-858377e4e94a61ae",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"indexmap\\\"\" --cfg \"feature=\\\"preserve_order\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"arbitrary_precision\\\", \\\"default\\\", \\\"float_roundtrip\\\", \\\"indexmap\\\", \\\"preserve_order\\\", \\\"raw_value\\\", \\\"std\\\", \\\"unbounded_depth\\\"))\" -C metadata=038f9bba91cd5828 -C extra-filename=-858377e4e94a61ae --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\build.rs",
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
        "feature=\"indexmap\"",
        "--cfg",
        "feature=\"preserve_order\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"arbitrary_precision\", \"default\", \"float_roundtrip\", \"indexmap\", \"preserve_order\", \"raw_value\", \"std\", \"unbounded_depth\"))",
        "-C",
        "metadata=038f9bba91cd5828",
        "-C",
        "extra-filename=-858377e4e94a61ae",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.838850+00:00",
      "end_time": "2026-07-13T17:04:06.113235+00:00",
      "start_unix_nanos": 1783962245838849600,
      "end_unix_nanos": 1783962246113235200,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\serde_json-858377e4e94a61ae"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 10320,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "hashbrown",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2\\src\\lib.rs",
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
        "cfg(feature, values(\"alloc\", \"allocator-api2\", \"compiler_builtins\", \"core\", \"default\", \"default-hasher\", \"equivalent\", \"inline-more\", \"nightly\", \"raw-entry\", \"rayon\", \"rustc-dep-of-std\", \"rustc-internal-api\", \"serde\"))",
        "-C",
        "metadata=9b150f7c959252c4",
        "-C",
        "extra-filename=-0aa971b51ad432f2",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name hashbrown --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"allocator-api2\\\", \\\"compiler_builtins\\\", \\\"core\\\", \\\"default\\\", \\\"default-hasher\\\", \\\"equivalent\\\", \\\"inline-more\\\", \\\"nightly\\\", \\\"raw-entry\\\", \\\"rayon\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-internal-api\\\", \\\"serde\\\"))\" -C metadata=9b150f7c959252c4 -C extra-filename=-0aa971b51ad432f2 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "hashbrown",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\hashbrown-0.15.2\\src\\lib.rs",
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
        "cfg(feature, values(\"alloc\", \"allocator-api2\", \"compiler_builtins\", \"core\", \"default\", \"default-hasher\", \"equivalent\", \"inline-more\", \"nightly\", \"raw-entry\", \"rayon\", \"rustc-dep-of-std\", \"rustc-internal-api\", \"serde\"))",
        "-C",
        "metadata=9b150f7c959252c4",
        "-C",
        "extra-filename=-0aa971b51ad432f2",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.844405+00:00",
      "end_time": "2026-07-13T17:04:06.313485+00:00",
      "start_unix_nanos": 1783962245844405500,
      "end_unix_nanos": 1783962246313485500,
      "crate_name": "hashbrown",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 21392,
      "ppid": 18472,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=f9b15d7751a7b186 -C extra-filename=-8a85cb2cd59e9679 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.848181+00:00",
      "end_time": "2026-07-13T17:04:06.006221+00:00",
      "start_unix_nanos": 1783962245848180800,
      "end_unix_nanos": 1783962246006221000,
      "crate_name": "shlex",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 20296,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "streaming_iterator",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9\\src\\lib.rs",
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
        "cfg(feature, values(\"alloc\", \"std\"))",
        "-C",
        "metadata=435ff8906afe8180",
        "-C",
        "extra-filename=-a568802d179ad611",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name streaming_iterator --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"std\\\"))\" -C metadata=435ff8906afe8180 -C extra-filename=-a568802d179ad611 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "streaming_iterator",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\streaming-iterator-0.1.9\\src\\lib.rs",
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
        "cfg(feature, values(\"alloc\", \"std\"))",
        "-C",
        "metadata=435ff8906afe8180",
        "-C",
        "extra-filename=-a568802d179ad611",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.851144+00:00",
      "end_time": "2026-07-13T17:04:06.098245+00:00",
      "start_unix_nanos": 1783962245851144400,
      "end_unix_nanos": 1783962246098244900,
      "crate_name": "streaming_iterator",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 19972,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "regex_syntax",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5\\src\\lib.rs",
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
        "feature=\"std\"",
        "--cfg",
        "feature=\"unicode\"",
        "--cfg",
        "feature=\"unicode-age\"",
        "--cfg",
        "feature=\"unicode-bool\"",
        "--cfg",
        "feature=\"unicode-case\"",
        "--cfg",
        "feature=\"unicode-gencat\"",
        "--cfg",
        "feature=\"unicode-perl\"",
        "--cfg",
        "feature=\"unicode-script\"",
        "--cfg",
        "feature=\"unicode-segment\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"arbitrary\", \"default\", \"std\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\"))",
        "-C",
        "metadata=bc2cf6bb9d6e8e62",
        "-C",
        "extra-filename=-c55cad3561091859",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name regex_syntax --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"std\\\"\" --cfg \"feature=\\\"unicode\\\"\" --cfg \"feature=\\\"unicode-age\\\"\" --cfg \"feature=\\\"unicode-bool\\\"\" --cfg \"feature=\\\"unicode-case\\\"\" --cfg \"feature=\\\"unicode-gencat\\\"\" --cfg \"feature=\\\"unicode-perl\\\"\" --cfg \"feature=\\\"unicode-script\\\"\" --cfg \"feature=\\\"unicode-segment\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arbitrary\\\", \\\"default\\\", \\\"std\\\", \\\"unicode\\\", \\\"unicode-age\\\", \\\"unicode-bool\\\", \\\"unicode-case\\\", \\\"unicode-gencat\\\", \\\"unicode-perl\\\", \\\"unicode-script\\\", \\\"unicode-segment\\\"))\" -C metadata=bc2cf6bb9d6e8e62 -C extra-filename=-c55cad3561091859 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "regex_syntax",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-syntax-0.8.5\\src\\lib.rs",
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
        "feature=\"std\"",
        "--cfg",
        "feature=\"unicode\"",
        "--cfg",
        "feature=\"unicode-age\"",
        "--cfg",
        "feature=\"unicode-bool\"",
        "--cfg",
        "feature=\"unicode-case\"",
        "--cfg",
        "feature=\"unicode-gencat\"",
        "--cfg",
        "feature=\"unicode-perl\"",
        "--cfg",
        "feature=\"unicode-script\"",
        "--cfg",
        "feature=\"unicode-segment\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"arbitrary\", \"default\", \"std\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\"))",
        "-C",
        "metadata=bc2cf6bb9d6e8e62",
        "-C",
        "extra-filename=-c55cad3561091859",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.854631+00:00",
      "end_time": "2026-07-13T17:04:07.725927+00:00",
      "start_unix_nanos": 1783962245854630800,
      "end_unix_nanos": 1783962247725927100,
      "crate_name": "regex_syntax",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 20000,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "ryu",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18\\src\\lib.rs",
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
        "cfg(feature, values(\"no-panic\", \"small\"))",
        "-C",
        "metadata=a35175013979633a",
        "-C",
        "extra-filename=-0ab869bcfcaecf84",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name ryu --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"no-panic\\\", \\\"small\\\"))\" -C metadata=a35175013979633a -C extra-filename=-0ab869bcfcaecf84 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "ryu",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\ryu-1.0.18\\src\\lib.rs",
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
        "cfg(feature, values(\"no-panic\", \"small\"))",
        "-C",
        "metadata=a35175013979633a",
        "-C",
        "extra-filename=-0ab869bcfcaecf84",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.857210+00:00",
      "end_time": "2026-07-13T17:04:06.006217+00:00",
      "start_unix_nanos": 1783962245857209700,
      "end_unix_nanos": 1783962246006217300,
      "crate_name": "ryu",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 20968,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "tree_sitter_language",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5\\language.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--warn=clippy::pedantic",
        "--warn=clippy::nursery",
        "--warn=clippy::cargo",
        "--allow=clippy::used_underscore_items",
        "--allow=clippy::unused_self",
        "--allow=clippy::unnecessary_wraps",
        "--allow=clippy::transmute_undefined_repr",
        "--allow=clippy::too_many_lines",
        "--deny=clippy::todo",
        "--allow=clippy::struct_field_names",
        "--allow=clippy::struct_excessive_bools",
        "--allow=clippy::string_lit_as_bytes",
        "--allow=clippy::similar_names",
        "--allow=clippy::ref_option",
        "--allow=clippy::redundant_closure_for_method_calls",
        "--allow=clippy::redundant_clone",
        "--allow=clippy::range_plus_one",
        "--allow=clippy::or_fun_call",
        "--allow=clippy::option_if_let_else",
        "--allow=clippy::multiple_crate_versions",
        "--allow=clippy::module_name_repetitions",
        "--allow=clippy::missing_panics_doc",
        "--allow=clippy::missing_errors_doc",
        "--allow=clippy::match_wildcard_for_single_variants",
        "--allow=clippy::items_after_statements",
        "--allow=clippy::inline_always",
        "--allow=clippy::if_not_else",
        "--allow=clippy::fn_params_excessive_bools",
        "--allow=clippy::fallible_impl_from",
        "--deny=clippy::dbg_macro",
        "--allow=clippy::collection_is_never_read",
        "--allow=clippy::cognitive_complexity",
        "--allow=clippy::checked_conversions",
        "--allow=clippy::cast_sign_loss",
        "--allow=clippy::cast_precision_loss",
        "--allow=clippy::cast_possible_wrap",
        "--allow=clippy::cast_possible_truncation",
        "--allow=clippy::cast_lossless",
        "--allow=clippy::branches_sharing_code",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=cd17754602491c03",
        "-C",
        "extra-filename=-53ffe3285be676f2",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name tree_sitter_language --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5\\language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps --allow=clippy::transmute_undefined_repr --allow=clippy::too_many_lines --deny=clippy::todo --allow=clippy::struct_field_names --allow=clippy::struct_excessive_bools --allow=clippy::string_lit_as_bytes --allow=clippy::similar_names --allow=clippy::ref_option --allow=clippy::redundant_closure_for_method_calls --allow=clippy::redundant_clone --allow=clippy::range_plus_one --allow=clippy::or_fun_call --allow=clippy::option_if_let_else --allow=clippy::multiple_crate_versions --allow=clippy::module_name_repetitions --allow=clippy::missing_panics_doc --allow=clippy::missing_errors_doc --allow=clippy::match_wildcard_for_single_variants --allow=clippy::items_after_statements --allow=clippy::inline_always --allow=clippy::if_not_else --allow=clippy::fn_params_excessive_bools --allow=clippy::fallible_impl_from --deny=clippy::dbg_macro --allow=clippy::collection_is_never_read --allow=clippy::cognitive_complexity --allow=clippy::checked_conversions --allow=clippy::cast_sign_loss --allow=clippy::cast_precision_loss --allow=clippy::cast_possible_wrap --allow=clippy::cast_possible_truncation --allow=clippy::cast_lossless --allow=clippy::branches_sharing_code --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=cd17754602491c03 -C extra-filename=-53ffe3285be676f2 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "tree_sitter_language",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tree-sitter-language-0.1.5\\language.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--warn=clippy::pedantic",
        "--warn=clippy::nursery",
        "--warn=clippy::cargo",
        "--allow=clippy::used_underscore_items",
        "--allow=clippy::unused_self",
        "--allow=clippy::unnecessary_wraps",
        "--allow=clippy::transmute_undefined_repr",
        "--allow=clippy::too_many_lines",
        "--deny=clippy::todo",
        "--allow=clippy::struct_field_names",
        "--allow=clippy::struct_excessive_bools",
        "--allow=clippy::string_lit_as_bytes",
        "--allow=clippy::similar_names",
        "--allow=clippy::ref_option",
        "--allow=clippy::redundant_closure_for_method_calls",
        "--allow=clippy::redundant_clone",
        "--allow=clippy::range_plus_one",
        "--allow=clippy::or_fun_call",
        "--allow=clippy::option_if_let_else",
        "--allow=clippy::multiple_crate_versions",
        "--allow=clippy::module_name_repetitions",
        "--allow=clippy::missing_panics_doc",
        "--allow=clippy::missing_errors_doc",
        "--allow=clippy::match_wildcard_for_single_variants",
        "--allow=clippy::items_after_statements",
        "--allow=clippy::inline_always",
        "--allow=clippy::if_not_else",
        "--allow=clippy::fn_params_excessive_bools",
        "--allow=clippy::fallible_impl_from",
        "--deny=clippy::dbg_macro",
        "--allow=clippy::collection_is_never_read",
        "--allow=clippy::cognitive_complexity",
        "--allow=clippy::checked_conversions",
        "--allow=clippy::cast_sign_loss",
        "--allow=clippy::cast_precision_loss",
        "--allow=clippy::cast_possible_wrap",
        "--allow=clippy::cast_possible_truncation",
        "--allow=clippy::cast_lossless",
        "--allow=clippy::branches_sharing_code",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=cd17754602491c03",
        "-C",
        "extra-filename=-53ffe3285be676f2",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.861693+00:00",
      "end_time": "2026-07-13T17:04:05.935486+00:00",
      "start_unix_nanos": 1783962245861692900,
      "end_unix_nanos": 1783962245935485900,
      "crate_name": "tree_sitter_language",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 4612,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10\\src\\lib.rs",
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
        "metadata=01b3f11086860df2",
        "-C",
        "extra-filename=-e7715c40b0b1e5ba",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=01b3f11086860df2 -C extra-filename=-e7715c40b0b1e5ba --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.10\\src\\lib.rs",
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
        "metadata=01b3f11086860df2",
        "-C",
        "extra-filename=-e7715c40b0b1e5ba",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:05.952849+00:00",
      "end_time": "2026-07-13T17:04:06.966965+00:00",
      "start_unix_nanos": 1783962245952849200,
      "end_unix_nanos": 1783962246966965200,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 6460,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "aho_corasick",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3\\src\\lib.rs",
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
        "feature=\"perf-literal\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"logging\", \"perf-literal\", \"std\"))",
        "-C",
        "metadata=9f43e72be9192352",
        "-C",
        "extra-filename=-698a890c685b674b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name aho_corasick --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"perf-literal\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"logging\\\", \\\"perf-literal\\\", \\\"std\\\"))\" -C metadata=9f43e72be9192352 -C extra-filename=-698a890c685b674b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "aho_corasick",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\aho-corasick-1.1.3\\src\\lib.rs",
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
        "feature=\"perf-literal\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"logging\", \"perf-literal\", \"std\"))",
        "-C",
        "metadata=9f43e72be9192352",
        "-C",
        "extra-filename=-698a890c685b674b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:06.255133+00:00",
      "end_time": "2026-07-13T17:04:07.660028+00:00",
      "start_unix_nanos": 1783962246255132800,
      "end_unix_nanos": 1783962247660028500,
      "crate_name": "aho_corasick",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 3288,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "indexmap",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=clippy::style",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"arbitrary\", \"borsh\", \"default\", \"quickcheck\", \"rayon\", \"rustc-rayon\", \"serde\", \"std\", \"test_debug\"))",
        "-C",
        "metadata=761ceb347af6d48c",
        "-C",
        "extra-filename=-172cf76332011bd8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libequivalent-53e6508dea69364c.rmeta",
        "--extern",
        "hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libhashbrown-0aa971b51ad432f2.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name indexmap --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=clippy::style --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arbitrary\\\", \\\"borsh\\\", \\\"default\\\", \\\"quickcheck\\\", \\\"rayon\\\", \\\"rustc-rayon\\\", \\\"serde\\\", \\\"std\\\", \\\"test_debug\\\"))\" -C metadata=761ceb347af6d48c -C extra-filename=-172cf76332011bd8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libequivalent-53e6508dea69364c.rmeta --extern hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libhashbrown-0aa971b51ad432f2.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "indexmap",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\indexmap-2.7.1\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=clippy::style",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"arbitrary\", \"borsh\", \"default\", \"quickcheck\", \"rayon\", \"rustc-rayon\", \"serde\", \"std\", \"test_debug\"))",
        "-C",
        "metadata=761ceb347af6d48c",
        "-C",
        "extra-filename=-172cf76332011bd8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "equivalent=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libequivalent-53e6508dea69364c.rmeta",
        "--extern",
        "hashbrown=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libhashbrown-0aa971b51ad432f2.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:06.270156+00:00",
      "end_time": "2026-07-13T17:04:06.864939+00:00",
      "start_unix_nanos": 1783962246270156400,
      "end_unix_nanos": 1783962246864939300,
      "crate_name": "indexmap",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 20568,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "serde",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"default\", \"derive\", \"rc\", \"serde_derive\", \"std\", \"unstable\"))",
        "-C",
        "metadata=925db23f2ef610d0",
        "-C",
        "extra-filename=-2b0d0e9506dbd21b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "--check-cfg",
        "cfg(no_core_cstr)",
        "--check-cfg",
        "cfg(no_core_error)",
        "--check-cfg",
        "cfg(no_core_net)",
        "--check-cfg",
        "cfg(no_core_num_saturating)",
        "--check-cfg",
        "cfg(no_core_try_from)",
        "--check-cfg",
        "cfg(no_diagnostic_namespace)",
        "--check-cfg",
        "cfg(no_float_copysign)",
        "--check-cfg",
        "cfg(no_num_nonzero_signed)",
        "--check-cfg",
        "cfg(no_relaxed_trait_bounds)",
        "--check-cfg",
        "cfg(no_serde_derive)",
        "--check-cfg",
        "cfg(no_std_atomic)",
        "--check-cfg",
        "cfg(no_std_atomic64)",
        "--check-cfg",
        "cfg(no_systemtime_checked_add)",
        "--check-cfg",
        "cfg(no_target_has_atomic)"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name serde --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"default\\\", \\\"derive\\\", \\\"rc\\\", \\\"serde_derive\\\", \\\"std\\\", \\\"unstable\\\"))\" -C metadata=925db23f2ef610d0 -C extra-filename=-2b0d0e9506dbd21b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --cap-lints allow --check-cfg cfg(no_core_cstr) --check-cfg cfg(no_core_error) --check-cfg cfg(no_core_net) --check-cfg cfg(no_core_num_saturating) --check-cfg cfg(no_core_try_from) --check-cfg cfg(no_diagnostic_namespace) --check-cfg cfg(no_float_copysign) --check-cfg cfg(no_num_nonzero_signed) --check-cfg cfg(no_relaxed_trait_bounds) --check-cfg cfg(no_serde_derive) --check-cfg cfg(no_std_atomic) --check-cfg cfg(no_std_atomic64) --check-cfg cfg(no_systemtime_checked_add) --check-cfg cfg(no_target_has_atomic)",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "serde",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde-1.0.217\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"default\", \"derive\", \"rc\", \"serde_derive\", \"std\", \"unstable\"))",
        "-C",
        "metadata=925db23f2ef610d0",
        "-C",
        "extra-filename=-2b0d0e9506dbd21b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "--check-cfg",
        "cfg(no_core_cstr)",
        "--check-cfg",
        "cfg(no_core_error)",
        "--check-cfg",
        "cfg(no_core_net)",
        "--check-cfg",
        "cfg(no_core_num_saturating)",
        "--check-cfg",
        "cfg(no_core_try_from)",
        "--check-cfg",
        "cfg(no_diagnostic_namespace)",
        "--check-cfg",
        "cfg(no_float_copysign)",
        "--check-cfg",
        "cfg(no_num_nonzero_signed)",
        "--check-cfg",
        "cfg(no_relaxed_trait_bounds)",
        "--check-cfg",
        "cfg(no_serde_derive)",
        "--check-cfg",
        "cfg(no_std_atomic)",
        "--check-cfg",
        "cfg(no_std_atomic64)",
        "--check-cfg",
        "cfg(no_systemtime_checked_add)",
        "--check-cfg",
        "cfg(no_target_has_atomic)"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:06.285193+00:00",
      "end_time": "2026-07-13T17:04:08.041404+00:00",
      "start_unix_nanos": 1783962246285193200,
      "end_unix_nanos": 1783962248041403600,
      "crate_name": "serde",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 10620,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "regex_automata",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9\\src\\lib.rs",
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
        "feature=\"alloc\"",
        "--cfg",
        "feature=\"dfa-onepass\"",
        "--cfg",
        "feature=\"hybrid\"",
        "--cfg",
        "feature=\"meta\"",
        "--cfg",
        "feature=\"nfa-backtrack\"",
        "--cfg",
        "feature=\"nfa-pikevm\"",
        "--cfg",
        "feature=\"nfa-thompson\"",
        "--cfg",
        "feature=\"perf-inline\"",
        "--cfg",
        "feature=\"perf-literal\"",
        "--cfg",
        "feature=\"perf-literal-multisubstring\"",
        "--cfg",
        "feature=\"perf-literal-substring\"",
        "--cfg",
        "feature=\"std\"",
        "--cfg",
        "feature=\"syntax\"",
        "--cfg",
        "feature=\"unicode\"",
        "--cfg",
        "feature=\"unicode-age\"",
        "--cfg",
        "feature=\"unicode-bool\"",
        "--cfg",
        "feature=\"unicode-case\"",
        "--cfg",
        "feature=\"unicode-gencat\"",
        "--cfg",
        "feature=\"unicode-perl\"",
        "--cfg",
        "feature=\"unicode-script\"",
        "--cfg",
        "feature=\"unicode-segment\"",
        "--cfg",
        "feature=\"unicode-word-boundary\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"default\", \"dfa\", \"dfa-build\", \"dfa-onepass\", \"dfa-search\", \"hybrid\", \"internal-instrument\", \"internal-instrument-pikevm\", \"logging\", \"meta\", \"nfa\", \"nfa-backtrack\", \"nfa-pikevm\", \"nfa-thompson\", \"perf\", \"perf-inline\", \"perf-literal\", \"perf-literal-multisubstring\", \"perf-literal-substring\", \"std\", \"syntax\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\", \"unicode-word-boundary\"))",
        "-C",
        "metadata=e1da46555908029d",
        "-C",
        "extra-filename=-53e61e69396e7d26",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta",
        "--extern",
        "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
        "--extern",
        "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name regex_automata --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"alloc\\\"\" --cfg \"feature=\\\"dfa-onepass\\\"\" --cfg \"feature=\\\"hybrid\\\"\" --cfg \"feature=\\\"meta\\\"\" --cfg \"feature=\\\"nfa-backtrack\\\"\" --cfg \"feature=\\\"nfa-pikevm\\\"\" --cfg \"feature=\\\"nfa-thompson\\\"\" --cfg \"feature=\\\"perf-inline\\\"\" --cfg \"feature=\\\"perf-literal\\\"\" --cfg \"feature=\\\"perf-literal-multisubstring\\\"\" --cfg \"feature=\\\"perf-literal-substring\\\"\" --cfg \"feature=\\\"std\\\"\" --cfg \"feature=\\\"syntax\\\"\" --cfg \"feature=\\\"unicode\\\"\" --cfg \"feature=\\\"unicode-age\\\"\" --cfg \"feature=\\\"unicode-bool\\\"\" --cfg \"feature=\\\"unicode-case\\\"\" --cfg \"feature=\\\"unicode-gencat\\\"\" --cfg \"feature=\\\"unicode-perl\\\"\" --cfg \"feature=\\\"unicode-script\\\"\" --cfg \"feature=\\\"unicode-segment\\\"\" --cfg \"feature=\\\"unicode-word-boundary\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"default\\\", \\\"dfa\\\", \\\"dfa-build\\\", \\\"dfa-onepass\\\", \\\"dfa-search\\\", \\\"hybrid\\\", \\\"internal-instrument\\\", \\\"internal-instrument-pikevm\\\", \\\"logging\\\", \\\"meta\\\", \\\"nfa\\\", \\\"nfa-backtrack\\\", \\\"nfa-pikevm\\\", \\\"nfa-thompson\\\", \\\"perf\\\", \\\"perf-inline\\\", \\\"perf-literal\\\", \\\"perf-literal-multisubstring\\\", \\\"perf-literal-substring\\\", \\\"std\\\", \\\"syntax\\\", \\\"unicode\\\", \\\"unicode-age\\\", \\\"unicode-bool\\\", \\\"unicode-case\\\", \\\"unicode-gencat\\\", \\\"unicode-perl\\\", \\\"unicode-script\\\", \\\"unicode-segment\\\", \\\"unicode-word-boundary\\\"))\" -C metadata=e1da46555908029d -C extra-filename=-53e61e69396e7d26 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta --extern memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta --extern regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "regex_automata",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-automata-0.4.9\\src\\lib.rs",
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
        "feature=\"alloc\"",
        "--cfg",
        "feature=\"dfa-onepass\"",
        "--cfg",
        "feature=\"hybrid\"",
        "--cfg",
        "feature=\"meta\"",
        "--cfg",
        "feature=\"nfa-backtrack\"",
        "--cfg",
        "feature=\"nfa-pikevm\"",
        "--cfg",
        "feature=\"nfa-thompson\"",
        "--cfg",
        "feature=\"perf-inline\"",
        "--cfg",
        "feature=\"perf-literal\"",
        "--cfg",
        "feature=\"perf-literal-multisubstring\"",
        "--cfg",
        "feature=\"perf-literal-substring\"",
        "--cfg",
        "feature=\"std\"",
        "--cfg",
        "feature=\"syntax\"",
        "--cfg",
        "feature=\"unicode\"",
        "--cfg",
        "feature=\"unicode-age\"",
        "--cfg",
        "feature=\"unicode-bool\"",
        "--cfg",
        "feature=\"unicode-case\"",
        "--cfg",
        "feature=\"unicode-gencat\"",
        "--cfg",
        "feature=\"unicode-perl\"",
        "--cfg",
        "feature=\"unicode-script\"",
        "--cfg",
        "feature=\"unicode-segment\"",
        "--cfg",
        "feature=\"unicode-word-boundary\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"default\", \"dfa\", \"dfa-build\", \"dfa-onepass\", \"dfa-search\", \"hybrid\", \"internal-instrument\", \"internal-instrument-pikevm\", \"logging\", \"meta\", \"nfa\", \"nfa-backtrack\", \"nfa-pikevm\", \"nfa-thompson\", \"perf\", \"perf-inline\", \"perf-literal\", \"perf-literal-multisubstring\", \"perf-literal-substring\", \"std\", \"syntax\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\", \"unicode-word-boundary\"))",
        "-C",
        "metadata=e1da46555908029d",
        "-C",
        "extra-filename=-53e61e69396e7d26",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta",
        "--extern",
        "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
        "--extern",
        "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:07.152817+00:00",
      "end_time": "2026-07-13T17:04:09.120600+00:00",
      "start_unix_nanos": 1783962247152816900,
      "end_unix_nanos": 1783962249120600400,
      "crate_name": "regex_automata",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 20628,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "serde_json",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\src\\lib.rs",
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
        "feature=\"indexmap\"",
        "--cfg",
        "feature=\"preserve_order\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"arbitrary_precision\", \"default\", \"float_roundtrip\", \"indexmap\", \"preserve_order\", \"raw_value\", \"std\", \"unbounded_depth\"))",
        "-C",
        "metadata=b8624e194fe468fe",
        "-C",
        "extra-filename=-c86d1c8394de6867",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "indexmap=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libindexmap-172cf76332011bd8.rmeta",
        "--extern",
        "itoa=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libitoa-4095bc4c8c644f32.rmeta",
        "--extern",
        "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
        "--extern",
        "ryu=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libryu-0ab869bcfcaecf84.rmeta",
        "--extern",
        "serde=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde-2b0d0e9506dbd21b.rmeta",
        "--cap-lints",
        "allow",
        "--cfg",
        "fast_arithmetic=\"64\"",
        "--check-cfg",
        "cfg(fast_arithmetic, values(\"32\", \"64\"))"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name serde_json --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"indexmap\\\"\" --cfg \"feature=\\\"preserve_order\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"alloc\\\", \\\"arbitrary_precision\\\", \\\"default\\\", \\\"float_roundtrip\\\", \\\"indexmap\\\", \\\"preserve_order\\\", \\\"raw_value\\\", \\\"std\\\", \\\"unbounded_depth\\\"))\" -C metadata=b8624e194fe468fe -C extra-filename=-c86d1c8394de6867 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern indexmap=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libindexmap-172cf76332011bd8.rmeta --extern itoa=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libitoa-4095bc4c8c644f32.rmeta --extern memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta --extern ryu=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libryu-0ab869bcfcaecf84.rmeta --extern serde=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde-2b0d0e9506dbd21b.rmeta --cap-lints allow --cfg \"fast_arithmetic=\\\"64\\\"\" --check-cfg \"cfg(fast_arithmetic, values(\\\"32\\\", \\\"64\\\"))\"",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "serde_json",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\serde_json-1.0.137\\src\\lib.rs",
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
        "feature=\"indexmap\"",
        "--cfg",
        "feature=\"preserve_order\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"alloc\", \"arbitrary_precision\", \"default\", \"float_roundtrip\", \"indexmap\", \"preserve_order\", \"raw_value\", \"std\", \"unbounded_depth\"))",
        "-C",
        "metadata=b8624e194fe468fe",
        "-C",
        "extra-filename=-c86d1c8394de6867",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "indexmap=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libindexmap-172cf76332011bd8.rmeta",
        "--extern",
        "itoa=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libitoa-4095bc4c8c644f32.rmeta",
        "--extern",
        "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
        "--extern",
        "ryu=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libryu-0ab869bcfcaecf84.rmeta",
        "--extern",
        "serde=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde-2b0d0e9506dbd21b.rmeta",
        "--cap-lints",
        "allow",
        "--cfg",
        "fast_arithmetic=\"64\"",
        "--check-cfg",
        "cfg(fast_arithmetic, values(\"32\", \"64\"))"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:07.958932+00:00",
      "end_time": "2026-07-13T17:04:08.587746+00:00",
      "start_unix_nanos": 1783962247958932300,
      "end_unix_nanos": 1783962248587746200,
      "crate_name": "serde_json",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 21352,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "regex",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1\\src\\lib.rs",
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
        "feature=\"perf\"",
        "--cfg",
        "feature=\"perf-backtrack\"",
        "--cfg",
        "feature=\"perf-cache\"",
        "--cfg",
        "feature=\"perf-dfa\"",
        "--cfg",
        "feature=\"perf-inline\"",
        "--cfg",
        "feature=\"perf-literal\"",
        "--cfg",
        "feature=\"perf-onepass\"",
        "--cfg",
        "feature=\"std\"",
        "--cfg",
        "feature=\"unicode\"",
        "--cfg",
        "feature=\"unicode-age\"",
        "--cfg",
        "feature=\"unicode-bool\"",
        "--cfg",
        "feature=\"unicode-case\"",
        "--cfg",
        "feature=\"unicode-gencat\"",
        "--cfg",
        "feature=\"unicode-perl\"",
        "--cfg",
        "feature=\"unicode-script\"",
        "--cfg",
        "feature=\"unicode-segment\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"logging\", \"pattern\", \"perf\", \"perf-backtrack\", \"perf-cache\", \"perf-dfa\", \"perf-dfa-full\", \"perf-inline\", \"perf-literal\", \"perf-onepass\", \"std\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\", \"unstable\", \"use_std\"))",
        "-C",
        "metadata=d0590efaab4b714d",
        "-C",
        "extra-filename=-83bebd8cc8d52f53",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta",
        "--extern",
        "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
        "--extern",
        "regex_automata=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_automata-53e61e69396e7d26.rmeta",
        "--extern",
        "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name regex --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg \"feature=\\\"perf\\\"\" --cfg \"feature=\\\"perf-backtrack\\\"\" --cfg \"feature=\\\"perf-cache\\\"\" --cfg \"feature=\\\"perf-dfa\\\"\" --cfg \"feature=\\\"perf-inline\\\"\" --cfg \"feature=\\\"perf-literal\\\"\" --cfg \"feature=\\\"perf-onepass\\\"\" --cfg \"feature=\\\"std\\\"\" --cfg \"feature=\\\"unicode\\\"\" --cfg \"feature=\\\"unicode-age\\\"\" --cfg \"feature=\\\"unicode-bool\\\"\" --cfg \"feature=\\\"unicode-case\\\"\" --cfg \"feature=\\\"unicode-gencat\\\"\" --cfg \"feature=\\\"unicode-perl\\\"\" --cfg \"feature=\\\"unicode-script\\\"\" --cfg \"feature=\\\"unicode-segment\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"logging\\\", \\\"pattern\\\", \\\"perf\\\", \\\"perf-backtrack\\\", \\\"perf-cache\\\", \\\"perf-dfa\\\", \\\"perf-dfa-full\\\", \\\"perf-inline\\\", \\\"perf-literal\\\", \\\"perf-onepass\\\", \\\"std\\\", \\\"unicode\\\", \\\"unicode-age\\\", \\\"unicode-bool\\\", \\\"unicode-case\\\", \\\"unicode-gencat\\\", \\\"unicode-perl\\\", \\\"unicode-script\\\", \\\"unicode-segment\\\", \\\"unstable\\\", \\\"use_std\\\"))\" -C metadata=d0590efaab4b714d -C extra-filename=-83bebd8cc8d52f53 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta --extern memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta --extern regex_automata=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_automata-53e61e69396e7d26.rmeta --extern regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "regex",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\regex-1.11.1\\src\\lib.rs",
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
        "feature=\"perf\"",
        "--cfg",
        "feature=\"perf-backtrack\"",
        "--cfg",
        "feature=\"perf-cache\"",
        "--cfg",
        "feature=\"perf-dfa\"",
        "--cfg",
        "feature=\"perf-inline\"",
        "--cfg",
        "feature=\"perf-literal\"",
        "--cfg",
        "feature=\"perf-onepass\"",
        "--cfg",
        "feature=\"std\"",
        "--cfg",
        "feature=\"unicode\"",
        "--cfg",
        "feature=\"unicode-age\"",
        "--cfg",
        "feature=\"unicode-bool\"",
        "--cfg",
        "feature=\"unicode-case\"",
        "--cfg",
        "feature=\"unicode-gencat\"",
        "--cfg",
        "feature=\"unicode-perl\"",
        "--cfg",
        "feature=\"unicode-script\"",
        "--cfg",
        "feature=\"unicode-segment\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"logging\", \"pattern\", \"perf\", \"perf-backtrack\", \"perf-cache\", \"perf-dfa\", \"perf-dfa-full\", \"perf-inline\", \"perf-literal\", \"perf-onepass\", \"std\", \"unicode\", \"unicode-age\", \"unicode-bool\", \"unicode-case\", \"unicode-gencat\", \"unicode-perl\", \"unicode-script\", \"unicode-segment\", \"unstable\", \"use_std\"))",
        "-C",
        "metadata=d0590efaab4b714d",
        "-C",
        "extra-filename=-83bebd8cc8d52f53",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "aho_corasick=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libaho_corasick-698a890c685b674b.rmeta",
        "--extern",
        "memchr=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libmemchr-67ed63e3e8d56c77.rmeta",
        "--extern",
        "regex_automata=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_automata-53e61e69396e7d26.rmeta",
        "--extern",
        "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:08.447880+00:00",
      "end_time": "2026-07-13T17:04:08.779657+00:00",
      "start_unix_nanos": 1783962248447879900,
      "end_unix_nanos": 1783962248779656900,
      "crate_name": "regex",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 16896,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "binding_rust\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--warn=clippy::pedantic",
        "--warn=clippy::nursery",
        "--warn=clippy::cargo",
        "--allow=clippy::used_underscore_items",
        "--allow=clippy::unused_self",
        "--allow=clippy::unnecessary_wraps",
        "--allow=clippy::transmute_undefined_repr",
        "--allow=clippy::too_many_lines",
        "--deny=clippy::todo",
        "--allow=clippy::struct_field_names",
        "--allow=clippy::struct_excessive_bools",
        "--allow=clippy::string_lit_as_bytes",
        "--allow=clippy::similar_names",
        "--allow=clippy::ref_option",
        "--allow=clippy::redundant_closure_for_method_calls",
        "--allow=clippy::redundant_clone",
        "--allow=clippy::range_plus_one",
        "--allow=clippy::or_fun_call",
        "--allow=clippy::option_if_let_else",
        "--allow=clippy::obfuscated_if_else",
        "--allow=clippy::needless_for_each",
        "--allow=clippy::multiple_crate_versions",
        "--allow=clippy::module_name_repetitions",
        "--allow=clippy::missing_panics_doc",
        "--allow=clippy::missing_errors_doc",
        "--allow=mismatched_lifetime_syntaxes",
        "--allow=clippy::match_wildcard_for_single_variants",
        "--allow=clippy::items_after_statements",
        "--allow=clippy::inline_always",
        "--allow=clippy::if_not_else",
        "--allow=clippy::fn_params_excessive_bools",
        "--allow=clippy::fallible_impl_from",
        "--deny=clippy::dbg_macro",
        "--allow=clippy::collection_is_never_read",
        "--allow=clippy::cognitive_complexity",
        "--allow=clippy::checked_conversions",
        "--allow=clippy::cast_sign_loss",
        "--allow=clippy::cast_precision_loss",
        "--allow=clippy::cast_possible_wrap",
        "--allow=clippy::cast_possible_truncation",
        "--allow=clippy::cast_lossless",
        "--allow=clippy::branches_sharing_code",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"bindgen\", \"default\", \"std\", \"wasm\", \"wasmtime-c-api\"))",
        "-C",
        "metadata=20932890e59f653e",
        "-C",
        "extra-filename=-2d76d60e21575414",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libcc-e7715c40b0b1e5ba.rlib",
        "--extern",
        "serde_json=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde_json-c86d1c8394de6867.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 binding_rust\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps --allow=clippy::transmute_undefined_repr --allow=clippy::too_many_lines --deny=clippy::todo --allow=clippy::struct_field_names --allow=clippy::struct_excessive_bools --allow=clippy::string_lit_as_bytes --allow=clippy::similar_names --allow=clippy::ref_option --allow=clippy::redundant_closure_for_method_calls --allow=clippy::redundant_clone --allow=clippy::range_plus_one --allow=clippy::or_fun_call --allow=clippy::option_if_let_else --allow=clippy::obfuscated_if_else --allow=clippy::needless_for_each --allow=clippy::multiple_crate_versions --allow=clippy::module_name_repetitions --allow=clippy::missing_panics_doc --allow=clippy::missing_errors_doc --allow=mismatched_lifetime_syntaxes --allow=clippy::match_wildcard_for_single_variants --allow=clippy::items_after_statements --allow=clippy::inline_always --allow=clippy::if_not_else --allow=clippy::fn_params_excessive_bools --allow=clippy::fallible_impl_from --deny=clippy::dbg_macro --allow=clippy::collection_is_never_read --allow=clippy::cognitive_complexity --allow=clippy::checked_conversions --allow=clippy::cast_sign_loss --allow=clippy::cast_precision_loss --allow=clippy::cast_possible_wrap --allow=clippy::cast_possible_truncation --allow=clippy::cast_lossless --allow=clippy::branches_sharing_code --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"bindgen\\\", \\\"default\\\", \\\"std\\\", \\\"wasm\\\", \\\"wasmtime-c-api\\\"))\" -C metadata=20932890e59f653e -C extra-filename=-2d76d60e21575414 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libcc-e7715c40b0b1e5ba.rlib --extern serde_json=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde_json-c86d1c8394de6867.rlib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "binding_rust\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--warn=clippy::pedantic",
        "--warn=clippy::nursery",
        "--warn=clippy::cargo",
        "--allow=clippy::used_underscore_items",
        "--allow=clippy::unused_self",
        "--allow=clippy::unnecessary_wraps",
        "--allow=clippy::transmute_undefined_repr",
        "--allow=clippy::too_many_lines",
        "--deny=clippy::todo",
        "--allow=clippy::struct_field_names",
        "--allow=clippy::struct_excessive_bools",
        "--allow=clippy::string_lit_as_bytes",
        "--allow=clippy::similar_names",
        "--allow=clippy::ref_option",
        "--allow=clippy::redundant_closure_for_method_calls",
        "--allow=clippy::redundant_clone",
        "--allow=clippy::range_plus_one",
        "--allow=clippy::or_fun_call",
        "--allow=clippy::option_if_let_else",
        "--allow=clippy::obfuscated_if_else",
        "--allow=clippy::needless_for_each",
        "--allow=clippy::multiple_crate_versions",
        "--allow=clippy::module_name_repetitions",
        "--allow=clippy::missing_panics_doc",
        "--allow=clippy::missing_errors_doc",
        "--allow=mismatched_lifetime_syntaxes",
        "--allow=clippy::match_wildcard_for_single_variants",
        "--allow=clippy::items_after_statements",
        "--allow=clippy::inline_always",
        "--allow=clippy::if_not_else",
        "--allow=clippy::fn_params_excessive_bools",
        "--allow=clippy::fallible_impl_from",
        "--deny=clippy::dbg_macro",
        "--allow=clippy::collection_is_never_read",
        "--allow=clippy::cognitive_complexity",
        "--allow=clippy::checked_conversions",
        "--allow=clippy::cast_sign_loss",
        "--allow=clippy::cast_precision_loss",
        "--allow=clippy::cast_possible_wrap",
        "--allow=clippy::cast_possible_truncation",
        "--allow=clippy::cast_lossless",
        "--allow=clippy::branches_sharing_code",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"bindgen\", \"default\", \"std\", \"wasm\", \"wasmtime-c-api\"))",
        "-C",
        "metadata=20932890e59f653e",
        "-C",
        "extra-filename=-2d76d60e21575414",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libcc-e7715c40b0b1e5ba.rlib",
        "--extern",
        "serde_json=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libserde_json-c86d1c8394de6867.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:08.607595+00:00",
      "end_time": "2026-07-13T17:04:08.979057+00:00",
      "start_unix_nanos": 1783962248607594800,
      "end_unix_nanos": 1783962248979056700,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-2d76d60e21575414"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "tree-sitter:0.25.10:13240",
      "root_process_pid": 19560,
      "pid": 20068,
      "ppid": 18472,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "tree_sitter",
        "--edition=2021",
        "binding_rust\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--warn=clippy::pedantic",
        "--warn=clippy::nursery",
        "--warn=clippy::cargo",
        "--allow=clippy::used_underscore_items",
        "--allow=clippy::unused_self",
        "--allow=clippy::unnecessary_wraps",
        "--allow=clippy::transmute_undefined_repr",
        "--allow=clippy::too_many_lines",
        "--deny=clippy::todo",
        "--allow=clippy::struct_field_names",
        "--allow=clippy::struct_excessive_bools",
        "--allow=clippy::string_lit_as_bytes",
        "--allow=clippy::similar_names",
        "--allow=clippy::ref_option",
        "--allow=clippy::redundant_closure_for_method_calls",
        "--allow=clippy::redundant_clone",
        "--allow=clippy::range_plus_one",
        "--allow=clippy::or_fun_call",
        "--allow=clippy::option_if_let_else",
        "--allow=clippy::obfuscated_if_else",
        "--allow=clippy::needless_for_each",
        "--allow=clippy::multiple_crate_versions",
        "--allow=clippy::module_name_repetitions",
        "--allow=clippy::missing_panics_doc",
        "--allow=clippy::missing_errors_doc",
        "--allow=mismatched_lifetime_syntaxes",
        "--allow=clippy::match_wildcard_for_single_variants",
        "--allow=clippy::items_after_statements",
        "--allow=clippy::inline_always",
        "--allow=clippy::if_not_else",
        "--allow=clippy::fn_params_excessive_bools",
        "--allow=clippy::fallible_impl_from",
        "--deny=clippy::dbg_macro",
        "--allow=clippy::collection_is_never_read",
        "--allow=clippy::cognitive_complexity",
        "--allow=clippy::checked_conversions",
        "--allow=clippy::cast_sign_loss",
        "--allow=clippy::cast_precision_loss",
        "--allow=clippy::cast_possible_wrap",
        "--allow=clippy::cast_possible_truncation",
        "--allow=clippy::cast_lossless",
        "--allow=clippy::branches_sharing_code",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"bindgen\", \"default\", \"std\", \"wasm\", \"wasmtime-c-api\"))",
        "-C",
        "metadata=73a8caa36a17947b",
        "-C",
        "extra-filename=-4398dfe1415a54f2",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "regex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex-83bebd8cc8d52f53.rmeta",
        "--extern",
        "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
        "--extern",
        "streaming_iterator=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libstreaming_iterator-a568802d179ad611.rmeta",
        "--extern",
        "tree_sitter_language=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libtree_sitter_language-53ffe3285be676f2.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
        "-l",
        "static=tree-sitter"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name tree_sitter --edition=2021 binding_rust\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps --allow=clippy::transmute_undefined_repr --allow=clippy::too_many_lines --deny=clippy::todo --allow=clippy::struct_field_names --allow=clippy::struct_excessive_bools --allow=clippy::string_lit_as_bytes --allow=clippy::similar_names --allow=clippy::ref_option --allow=clippy::redundant_closure_for_method_calls --allow=clippy::redundant_clone --allow=clippy::range_plus_one --allow=clippy::or_fun_call --allow=clippy::option_if_let_else --allow=clippy::obfuscated_if_else --allow=clippy::needless_for_each --allow=clippy::multiple_crate_versions --allow=clippy::module_name_repetitions --allow=clippy::missing_panics_doc --allow=clippy::missing_errors_doc --allow=mismatched_lifetime_syntaxes --allow=clippy::match_wildcard_for_single_variants --allow=clippy::items_after_statements --allow=clippy::inline_always --allow=clippy::if_not_else --allow=clippy::fn_params_excessive_bools --allow=clippy::fallible_impl_from --deny=clippy::dbg_macro --allow=clippy::collection_is_never_read --allow=clippy::cognitive_complexity --allow=clippy::checked_conversions --allow=clippy::cast_sign_loss --allow=clippy::cast_precision_loss --allow=clippy::cast_possible_wrap --allow=clippy::cast_possible_truncation --allow=clippy::cast_lossless --allow=clippy::branches_sharing_code --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"bindgen\\\", \\\"default\\\", \\\"std\\\", \\\"wasm\\\", \\\"wasmtime-c-api\\\"))\" -C metadata=73a8caa36a17947b -C extra-filename=-4398dfe1415a54f2 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps --extern regex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex-83bebd8cc8d52f53.rmeta --extern regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta --extern streaming_iterator=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libstreaming_iterator-a568802d179ad611.rmeta --extern tree_sitter_language=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libtree_sitter_language-53ffe3285be676f2.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out -l static=tree-sitter",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "tree_sitter",
        "--edition=2021",
        "binding_rust\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--warn=clippy::pedantic",
        "--warn=clippy::nursery",
        "--warn=clippy::cargo",
        "--allow=clippy::used_underscore_items",
        "--allow=clippy::unused_self",
        "--allow=clippy::unnecessary_wraps",
        "--allow=clippy::transmute_undefined_repr",
        "--allow=clippy::too_many_lines",
        "--deny=clippy::todo",
        "--allow=clippy::struct_field_names",
        "--allow=clippy::struct_excessive_bools",
        "--allow=clippy::string_lit_as_bytes",
        "--allow=clippy::similar_names",
        "--allow=clippy::ref_option",
        "--allow=clippy::redundant_closure_for_method_calls",
        "--allow=clippy::redundant_clone",
        "--allow=clippy::range_plus_one",
        "--allow=clippy::or_fun_call",
        "--allow=clippy::option_if_let_else",
        "--allow=clippy::obfuscated_if_else",
        "--allow=clippy::needless_for_each",
        "--allow=clippy::multiple_crate_versions",
        "--allow=clippy::module_name_repetitions",
        "--allow=clippy::missing_panics_doc",
        "--allow=clippy::missing_errors_doc",
        "--allow=mismatched_lifetime_syntaxes",
        "--allow=clippy::match_wildcard_for_single_variants",
        "--allow=clippy::items_after_statements",
        "--allow=clippy::inline_always",
        "--allow=clippy::if_not_else",
        "--allow=clippy::fn_params_excessive_bools",
        "--allow=clippy::fallible_impl_from",
        "--deny=clippy::dbg_macro",
        "--allow=clippy::collection_is_never_read",
        "--allow=clippy::cognitive_complexity",
        "--allow=clippy::checked_conversions",
        "--allow=clippy::cast_sign_loss",
        "--allow=clippy::cast_precision_loss",
        "--allow=clippy::cast_possible_wrap",
        "--allow=clippy::cast_possible_truncation",
        "--allow=clippy::cast_lossless",
        "--allow=clippy::branches_sharing_code",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"bindgen\", \"default\", \"std\", \"wasm\", \"wasmtime-c-api\"))",
        "-C",
        "metadata=73a8caa36a17947b",
        "-C",
        "extra-filename=-4398dfe1415a54f2",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps",
        "--extern",
        "regex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex-83bebd8cc8d52f53.rmeta",
        "--extern",
        "regex_syntax=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libregex_syntax-c55cad3561091859.rmeta",
        "--extern",
        "streaming_iterator=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libstreaming_iterator-a568802d179ad611.rmeta",
        "--extern",
        "tree_sitter_language=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps\\libtree_sitter_language-53ffe3285be676f2.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\build\\tree-sitter-05d9b3bfa86b88b1\\out",
        "-l",
        "static=tree-sitter"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T17:04:10.602295+00:00",
      "end_time": "2026-07-13T17:04:11.442754+00:00",
      "start_unix_nanos": 1783962250602295400,
      "end_unix_nanos": 1783962251442753800,
      "crate_name": "tree_sitter",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-q8vp_7qg\\src\\tree-sitter-0.25.10\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 3565,
    "crate": "tree-sitter",
    "version": "0.25.10",
    "crate_id": "66032",
    "version_id": "1741500",
    "downloads": 2730854,
    "cumulative_downloads": 108672096094,
    "cumulative_share_of_global": 0.4062998797101359,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "binding_rust/build.rs",
    "build_script_exists": true,
    "package_build_field": "binding_rust/build.rs",
    "build_script_reason": "package_build_path",
    "download_source": "local"
  }
}
```
