# `libmimalloc-sys` `0.1.44`

Platform: Windows x86_64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/target/debug/build/libmimalloc-sys-215aebaae69fb964/out/libmimalloc.a`

Owner: `libmimalloc-sys` `0.1.44`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src/static.c`

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
    "c_src/mimalloc/v2/include",
    "-I",
    "c_src/mimalloc/v2/src",
    "-W4",
    "-DMI_DEBUG=0",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
    "-c",
    "c_src/mimalloc/v2/src/static.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
  "src": "c_src/mimalloc/v2/src/static.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.34",
      "name": "cc",
      "version": "1.2.34",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
      "name": "libc",
      "version": "0.2.175",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175"
    },
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
      "name": "libmimalloc-sys",
      "version": "0.1.44",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
      "name": "shlex",
      "version": "1.3.0",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "exit_code": 0,
  "kind": "exec",
  "pid": 21472,
  "ppid": 18736,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:6d6d935f270dfbfd:b25e576b645e1765",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
  "pid": 21472,
  "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:24484309caf07111:b25e576b645e1765",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
  "pid": 21472,
  "sha256": "2329b28eca8ddcf5bb056a04cff1a8d1bb63bb6b0e159b02403c1da744bdbc92",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:582b96f334a07129:b25e576b645e1765",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
  "pid": 21472,
  "sha256": "29652183e0a00cbf3644aafbe0dd917f6adff0e6157c655f40ed62314f1603ba",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:e67c2712a19037ad:b25e576b645e1765",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
  "pid": 21472,
  "sha256": "d447dea18f17407560cab10501efee4f9e55e88d025232e89ebb60e7f1afced4",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:0e8388510dd9d800:b25e576b645e1765",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
  "pid": 21472,
  "sha256": "96cee6e92452e10ec1baf9ece532ec50704c807d04a15bdeabf5d79b40d482db",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:6c8328293ea5aa1f:b25e576b645e1765",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
  "pid": 21472,
  "sha256": "be9114ff19349efe19e3f41812925e1a09978d7b63aff9412a87eed7f2904364",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:1ceda9c220daf075:b25e576b645e1765",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "kernel32.lib",
  "pid": 21472,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:1ceda9c220daf075:b25e576b645e1765",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "kernel32.lib",
  "pid": 21472,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:1ceda9c220daf075:b25e576b645e1765",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "kernel32.lib",
  "pid": 21472,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:1db9512c4d5c31e6:b25e576b645e1765",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "ntdll.lib",
  "pid": 21472,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:861f0814f9c52599:b25e576b645e1765",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "userenv.lib",
  "pid": 21472,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:50848825683fdca9:b25e576b645e1765",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "ws2_32.lib",
  "pid": 21472,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "used:link:50b281732a322d11:df7d4e53c08047f7:b25e576b645e1765",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "path": "dbghelp.lib",
  "pid": 21472,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o"
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
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.175",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 21472,
  "ppid": 18736,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "directories": [
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000200       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000250       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000270       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000288       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000298       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000340       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000358       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140038200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140038250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140038270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140038288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140038298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400382a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140038340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140038358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140038388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-link-link-21472-1783954824389034000.map",
  "pid": 21472,
  "ppid": 18736,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-link-link-21472-1783954824389034000.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\rustco57ypk\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "kind": "exec",
  "pid": 8580,
  "ppid": 20116,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\rustco57ypk\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\rustco57ypk\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\rustco57ypk\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 8580,
  "ppid": 20116,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\rustco57ypk\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400c5020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400c5298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400c52b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400c5300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400c5320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400c5338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400c5348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400c5358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400c53f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400c5408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400c5418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400c5448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400c5460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-link-link-8580-1783954825246665400.map",
  "pid": 8580,
  "ppid": 20116,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-link-link-8580-1783954825246665400.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "kind": "exec",
  "pid": 18668,
  "ppid": 13124,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c"
  ],
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "event_id": "used:cl:c6cdd849d77512e0:49a37e82575f1c52:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c",
  "pid": 18668,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c"
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
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
  "pid": 18668,
  "ppid": 13124,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "kind": "exec",
  "pid": 9280,
  "ppid": 13124,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
  "pid": 9280,
  "ppid": 13124,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 29

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "c_src/mimalloc/v2/include",
    "-I",
    "c_src/mimalloc/v2/src",
    "-W4",
    "-DMI_DEBUG=0",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
    "-c",
    "c_src/mimalloc/v2/src/static.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "kind": "exec",
  "pid": 7436,
  "ppid": 13124,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "c_src/mimalloc/v2/include",
    "-I",
    "c_src/mimalloc/v2/src",
    "-W4",
    "-DMI_DEBUG=0",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
    "-c",
    "c_src/mimalloc/v2/src/static.c"
  ],
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "event_id": "used:cl:c6cdd849d77512e0:cb18d1e13c079560:1859776464a49585",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
  "path": "c_src/mimalloc/v2/src/static.c",
  "pid": 7436,
  "sha256": "81e27487e494d2b32cb16a2605d61ee64fe3a71c409d5be3a673950ff769bd73",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 31

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "c_src/mimalloc/v2/include",
    "-I",
    "c_src/mimalloc/v2/src",
    "-W4",
    "-DMI_DEBUG=0",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
    "-c",
    "c_src/mimalloc/v2/src/static.c"
  ],
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "event_id": "used:cl:c6cdd849d77512e0:39fbf236f3006dbd:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
  "pid": 7436,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 32

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "c_src/mimalloc/v2/include",
    "-I",
    "c_src/mimalloc/v2/src",
    "-W4",
    "-DMI_DEBUG=0",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
    "-c",
    "c_src/mimalloc/v2/src/static.c"
  ],
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "event_id": "used:cl:c6cdd849d77512e0:cb18d1e13c079560:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "c_src/mimalloc/v2/src/static.c",
  "pid": 7436,
  "sha256": "81e27487e494d2b32cb16a2605d61ee64fe3a71c409d5be3a673950ff769bd73",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
    "-I",
    "c_src/mimalloc/v2/include",
    "-I",
    "c_src/mimalloc/v2/src",
    "-W4",
    "-DMI_DEBUG=0",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
    "-c",
    "c_src/mimalloc/v2/src/static.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
  "src": "c_src/mimalloc/v2/src/static.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
    "-I",
    "c_src/mimalloc/v2/include",
    "-I",
    "c_src/mimalloc/v2/src",
    "-W4",
    "-DMI_DEBUG=0",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
    "-c",
    "c_src/mimalloc/v2/src/static.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
    "c_src/mimalloc/v2/src/static.c"
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
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
    "-I",
    "c_src/mimalloc/v2/include",
    "-I",
    "c_src/mimalloc/v2/src",
    "-W4",
    "-DMI_DEBUG=0",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
    "-c",
    "c_src/mimalloc/v2/src/static.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
  "pid": 7436,
  "ppid": 13124,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17108,
  "ppid": 13124,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 37

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
  ],
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "event_id": "used:lib:c6cdd849d77512e0:1859776464a49585:5bfc4e7aabcb8491",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
  "pid": 17108,
  "sha256": "c99e5bd914fdd61bb66ff32b3b7f688a47ad5aefe1821744ae462268c78e8703",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 38

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
  ],
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "event_id": "used:lib:c6cdd849d77512e0:1859776464a49585:62505024992a3d7e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
  "pid": 17108,
  "sha256": "c99e5bd914fdd61bb66ff32b3b7f688a47ad5aefe1821744ae462268c78e8703",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 39

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 40

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 41

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "cargo_pkg_name": "libmimalloc-sys",
  "cargo_pkg_version": "0.1.44",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
  "pid": 17108,
  "ppid": 13124,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 42

```json
{
  "crate": "libmimalloc-sys",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "event_id": "bsrun:0afebe8257a9a86b:b14c63d2611fdb92:f369cf30dbf7dc18",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "0.1.44",
  "_owner": {
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
    "source": "cwd_prefix"
  }
}
```

#### Record 43

```json
{
  "crate": "libc",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "event_id": "bsrun:0e1b181b8bf4bbf6:6cea0e64599dc2fa:d4339d94c7df18fa",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/target/debug/build/libc-b3fe1a0a886550a6\\build-script-build.exe",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/target/debug/build/libc-b3fe1a0a886550a6/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
  "success": true,
  "target": null,
  "version": "0.2.175",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cwd_prefix"
  }
}
```

#### Record 44

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
  "raw_event_count": 31623,
  "parsed_event_count": 31623,
  "parse_error_count": 0,
  "command_line_event_count": 31623,
  "build_script_root_event_count": 598,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 4885,
  "dropped_event_count": 16430
}
```

#### Record 45

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 2672,
  "ppid": 18056,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T15:00:24.600964+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build-script-build.exe",
  "root_cargo_pid": 11064,
  "build_script_root_pid": 2672,
  "build_script_related": true,
  "build_script_target_dir": "libc-b3fe1a0a886550a6",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/target/debug/build/libc-b3fe1a0a886550a6/out"
}
```

#### Record 46

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 20012,
  "ppid": 2672,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
  ],
  "comm": "rustc-trace-wrapper.exe",
  "time": "2026-07-13T15:00:24.610005+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "root_cargo_pid": 11064,
  "build_script_root_pid": 2672,
  "build_script_related": true,
  "build_script_target_dir": "libc-b3fe1a0a886550a6",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/target/debug/build/libc-b3fe1a0a886550a6/out",
  "_direct_build_script_child": true,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 47

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 18976,
  "ppid": 20012,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T15:00:24.620531+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 11064,
  "build_script_root_pid": 2672,
  "build_script_related": true,
  "build_script_target_dir": "libc-b3fe1a0a886550a6",
  "_owner": {
    "crate": "libc",
    "version": "0.2.175",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/target/debug/build/libc-b3fe1a0a886550a6/out"
}
```

#### Record 48

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13124,
  "ppid": 18056,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T15:00:25.589623+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\build-script-build.exe",
  "root_cargo_pid": 11064,
  "build_script_root_pid": 13124,
  "build_script_related": true,
  "build_script_target_dir": "libmimalloc-sys-524f41214193c3d1"
}
```

#### Record 49

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 15584,
  "ppid": 19636,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
  "time": "2026-07-13T15:00:23.983268+00:00",
  "end_time": "2026-07-13T15:00:24.003819+00:00",
  "start_unix_nanos": 1783954823983268400,
  "end_unix_nanos": 1783954824003818800,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 50

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 19956,
  "ppid": 19636,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
  "time": "2026-07-13T15:00:24.011786+00:00",
  "end_time": "2026-07-13T15:00:24.035199+00:00",
  "start_unix_nanos": 1783954824011786500,
  "end_unix_nanos": 1783954824035199000,
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

#### Record 51

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 21336,
  "ppid": 18056,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
  "time": "2026-07-13T15:00:24.099985+00:00",
  "end_time": "2026-07-13T15:00:24.121067+00:00",
  "start_unix_nanos": 1783954824099985100,
  "end_unix_nanos": 1783954824121066700,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 52

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 15884,
  "ppid": 18056,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
  "time": "2026-07-13T15:00:24.129120+00:00",
  "end_time": "2026-07-13T15:00:24.154026+00:00",
  "start_unix_nanos": 1783954824129120200,
  "end_unix_nanos": 1783954824154025800,
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

#### Record 53

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 12632,
  "ppid": 18056,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
  "time": "2026-07-13T15:00:24.166600+00:00",
  "end_time": "2026-07-13T15:00:24.187845+00:00",
  "start_unix_nanos": 1783954824166599900,
  "end_unix_nanos": 1783954824187845300,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 54

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 21408,
  "ppid": 18056,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=f9b15d7751a7b186 -C extra-filename=-8a85cb2cd59e9679 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:00:24.210058+00:00",
  "end_time": "2026-07-13T15:00:24.333772+00:00",
  "start_unix_nanos": 1783954824210058400,
  "end_unix_nanos": 1783954824333772400,
  "crate_name": "shlex",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps"
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
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 18664,
  "ppid": 18056,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=2c2c20fd7bde7f69",
    "-C",
    "extra-filename=-b3fe1a0a886550a6",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=2c2c20fd7bde7f69 -C extra-filename=-b3fe1a0a886550a6 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6 -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=2c2c20fd7bde7f69",
    "-C",
    "extra-filename=-b3fe1a0a886550a6",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:00:24.212862+00:00",
  "end_time": "2026-07-13T15:00:24.510017+00:00",
  "start_unix_nanos": 1783954824212861500,
  "end_unix_nanos": 1783954824510017500,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6"
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
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 16844,
  "ppid": 18056,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34\\src\\lib.rs",
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
    "metadata=88301a1d3ea28166",
    "-C",
    "extra-filename=-fcfbeeaf61d3a45b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=88301a1d3ea28166 -C extra-filename=-fcfbeeaf61d3a45b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34\\src\\lib.rs",
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
    "metadata=88301a1d3ea28166",
    "-C",
    "extra-filename=-fcfbeeaf61d3a45b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:00:24.289457+00:00",
  "end_time": "2026-07-13T15:00:25.118007+00:00",
  "start_unix_nanos": 1783954824289456700,
  "end_unix_nanos": 1783954825118007100,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps"
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
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 20012,
  "ppid": 2672,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--version"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --version",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--version"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:00:24.614838+00:00",
  "end_time": "2026-07-13T15:00:24.633984+00:00",
  "start_unix_nanos": 1783954824614838300,
  "end_unix_nanos": 1783954824633983700,
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
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 21400,
  "ppid": 18056,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libc",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=f9c6ff215309a4c2",
    "-C",
    "extra-filename=-5d5a70abe056473f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "--cfg",
    "freebsd11",
    "--cfg",
    "libc_const_extern_fn",
    "--check-cfg",
    "cfg(emscripten_old_stat_abi)",
    "--check-cfg",
    "cfg(espidf_time32)",
    "--check-cfg",
    "cfg(freebsd10)",
    "--check-cfg",
    "cfg(freebsd11)",
    "--check-cfg",
    "cfg(freebsd12)",
    "--check-cfg",
    "cfg(freebsd13)",
    "--check-cfg",
    "cfg(freebsd14)",
    "--check-cfg",
    "cfg(freebsd15)",
    "--check-cfg",
    "cfg(gnu_file_offset_bits64)",
    "--check-cfg",
    "cfg(gnu_time_bits64)",
    "--check-cfg",
    "cfg(libc_const_extern_fn)",
    "--check-cfg",
    "cfg(libc_deny_warnings)",
    "--check-cfg",
    "cfg(libc_thread_local)",
    "--check-cfg",
    "cfg(libc_ctest)",
    "--check-cfg",
    "cfg(linux_time_bits64)",
    "--check-cfg",
    "cfg(musl_v1_2_3)",
    "--check-cfg",
    "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\"))",
    "--check-cfg",
    "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
    "--check-cfg",
    "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=f9c6ff215309a4c2 -C extra-filename=-5d5a70abe056473f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --cap-lints allow --cfg freebsd11 --cfg libc_const_extern_fn --check-cfg cfg(emscripten_old_stat_abi) --check-cfg cfg(espidf_time32) --check-cfg cfg(freebsd10) --check-cfg cfg(freebsd11) --check-cfg cfg(freebsd12) --check-cfg cfg(freebsd13) --check-cfg cfg(freebsd14) --check-cfg cfg(freebsd15) --check-cfg cfg(gnu_file_offset_bits64) --check-cfg cfg(gnu_time_bits64) --check-cfg cfg(libc_const_extern_fn) --check-cfg cfg(libc_deny_warnings) --check-cfg cfg(libc_thread_local) --check-cfg cfg(libc_ctest) --check-cfg cfg(linux_time_bits64) --check-cfg cfg(musl_v1_2_3) --check-cfg \"cfg(target_os,values(\\\"switch\\\",\\\"aix\\\",\\\"ohos\\\",\\\"hurd\\\",\\\"rtems\\\",\\\"visionos\\\",\\\"nuttx\\\",\\\"cygwin\\\"))\" --check-cfg \"cfg(target_env,values(\\\"illumos\\\",\\\"wasi\\\",\\\"aix\\\",\\\"ohos\\\",\\\"nto71_iosock\\\",\\\"nto80\\\"))\" --check-cfg \"cfg(target_arch,values(\\\"loongarch64\\\",\\\"mips32r6\\\",\\\"mips64r6\\\",\\\"csky\\\"))\"",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libc",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=f9c6ff215309a4c2",
    "-C",
    "extra-filename=-5d5a70abe056473f",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "--cfg",
    "freebsd11",
    "--cfg",
    "libc_const_extern_fn",
    "--check-cfg",
    "cfg(emscripten_old_stat_abi)",
    "--check-cfg",
    "cfg(espidf_time32)",
    "--check-cfg",
    "cfg(freebsd10)",
    "--check-cfg",
    "cfg(freebsd11)",
    "--check-cfg",
    "cfg(freebsd12)",
    "--check-cfg",
    "cfg(freebsd13)",
    "--check-cfg",
    "cfg(freebsd14)",
    "--check-cfg",
    "cfg(freebsd15)",
    "--check-cfg",
    "cfg(gnu_file_offset_bits64)",
    "--check-cfg",
    "cfg(gnu_time_bits64)",
    "--check-cfg",
    "cfg(libc_const_extern_fn)",
    "--check-cfg",
    "cfg(libc_deny_warnings)",
    "--check-cfg",
    "cfg(libc_thread_local)",
    "--check-cfg",
    "cfg(libc_ctest)",
    "--check-cfg",
    "cfg(linux_time_bits64)",
    "--check-cfg",
    "cfg(musl_v1_2_3)",
    "--check-cfg",
    "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\"))",
    "--check-cfg",
    "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
    "--check-cfg",
    "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:00:24.647295+00:00",
  "end_time": "2026-07-13T15:00:24.720789+00:00",
  "start_unix_nanos": 1783954824647295500,
  "end_unix_nanos": 1783954824720788800,
  "crate_name": "libc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps"
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
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 19176,
  "ppid": 18056,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
    "cfg(feature, values(\"arena\", \"cty\", \"debug\", \"debug_in_debug\", \"extended\", \"local_dynamic_tls\", \"no_thp\", \"override\", \"secure\", \"v3\"))",
    "-C",
    "metadata=ea213bd661f48a8b",
    "-C",
    "extra-filename=-524f41214193c3d1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libcc-fcfbeeaf61d3a45b.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arena\\\", \\\"cty\\\", \\\"debug\\\", \\\"debug_in_debug\\\", \\\"extended\\\", \\\"local_dynamic_tls\\\", \\\"no_thp\\\", \\\"override\\\", \\\"secure\\\", \\\"v3\\\"))\" -C metadata=ea213bd661f48a8b -C extra-filename=-524f41214193c3d1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libcc-fcfbeeaf61d3a45b.rlib",
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
    "cfg(feature, values(\"arena\", \"cty\", \"debug\", \"debug_in_debug\", \"extended\", \"local_dynamic_tls\", \"no_thp\", \"override\", \"secure\", \"v3\"))",
    "-C",
    "metadata=ea213bd661f48a8b",
    "-C",
    "extra-filename=-524f41214193c3d1",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libcc-fcfbeeaf61d3a45b.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:00:25.133584+00:00",
  "end_time": "2026-07-13T15:00:25.451113+00:00",
  "start_unix_nanos": 1783954825133583800,
  "end_unix_nanos": 1783954825451113500,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1"
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
  "run_id": "libmimalloc-sys:0.1.44:5536",
  "root_process_pid": 11064,
  "pid": 15676,
  "ppid": 18056,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libmimalloc_sys",
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
    "cfg(feature, values(\"arena\", \"cty\", \"debug\", \"debug_in_debug\", \"extended\", \"local_dynamic_tls\", \"no_thp\", \"override\", \"secure\", \"v3\"))",
    "-C",
    "metadata=55c77d3e9c4d6db0",
    "-C",
    "extra-filename=-961d3444c2719c7b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--extern",
    "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\liblibc-5d5a70abe056473f.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
    "-l",
    "static=mimalloc",
    "-l",
    "psapi",
    "-l",
    "shell32",
    "-l",
    "user32",
    "-l",
    "advapi32",
    "-l",
    "bcrypt"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libmimalloc_sys --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arena\\\", \\\"cty\\\", \\\"debug\\\", \\\"debug_in_debug\\\", \\\"extended\\\", \\\"local_dynamic_tls\\\", \\\"no_thp\\\", \\\"override\\\", \\\"secure\\\", \\\"v3\\\"))\" -C metadata=55c77d3e9c4d6db0 -C extra-filename=-961d3444c2719c7b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --extern libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\liblibc-5d5a70abe056473f.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out -l static=mimalloc -l psapi -l shell32 -l user32 -l advapi32 -l bcrypt",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libmimalloc_sys",
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
    "cfg(feature, values(\"arena\", \"cty\", \"debug\", \"debug_in_debug\", \"extended\", \"local_dynamic_tls\", \"no_thp\", \"override\", \"secure\", \"v3\"))",
    "-C",
    "metadata=55c77d3e9c4d6db0",
    "-C",
    "extra-filename=-961d3444c2719c7b",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
    "--extern",
    "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\liblibc-5d5a70abe056473f.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
    "-l",
    "static=mimalloc",
    "-l",
    "psapi",
    "-l",
    "shell32",
    "-l",
    "user32",
    "-l",
    "advapi32",
    "-l",
    "bcrypt"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T15:00:26.332024+00:00",
  "end_time": "2026-07-13T15:00:26.402161+00:00",
  "start_unix_nanos": 1783954826332024300,
  "end_unix_nanos": 1783954826402160600,
  "crate_name": "libmimalloc_sys",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T15:00:27.347717+00:00",
  "crate": "libmimalloc-sys",
  "version": "0.1.44",
  "duration_seconds": 26.495293900021352,
  "trace_record_count": 48,
  "trace_owner_summary": {
    "owner_package_count": 4,
    "owner_packages": [
      {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "1.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.34",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.34",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.34",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.34/Cargo.toml"
      }
    ],
    "attributed_event_count": 42,
    "unattributed_event_count": 6,
    "owners": [
      {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "event_count": 24,
        "kind_counts": {
          "exec": 5,
          "link": 4,
          "exec_context": 5,
          "resolved_link": 1,
          "used_input": 6,
          "compile": 1,
          "archive": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "libc",
        "version": "0.2.175",
        "event_count": 18,
        "kind_counts": {
          "exec": 1,
          "used_input": 13,
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.34",
          "name": "cc",
          "version": "1.2.34",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
          "name": "libc",
          "version": "0.2.175",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175"
        },
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
          "name": "libmimalloc-sys",
          "version": "0.1.44",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
          "name": "shlex",
          "version": "1.3.0",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "exit_code": 0,
      "kind": "exec",
      "pid": 21472,
      "ppid": 18736,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:6d6d935f270dfbfd:b25e576b645e1765",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
      "pid": 21472,
      "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:24484309caf07111:b25e576b645e1765",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
      "pid": 21472,
      "sha256": "2329b28eca8ddcf5bb056a04cff1a8d1bb63bb6b0e159b02403c1da744bdbc92",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:582b96f334a07129:b25e576b645e1765",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
      "pid": 21472,
      "sha256": "29652183e0a00cbf3644aafbe0dd917f6adff0e6157c655f40ed62314f1603ba",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:e67c2712a19037ad:b25e576b645e1765",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
      "pid": 21472,
      "sha256": "d447dea18f17407560cab10501efee4f9e55e88d025232e89ebb60e7f1afced4",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:0e8388510dd9d800:b25e576b645e1765",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
      "pid": 21472,
      "sha256": "96cee6e92452e10ec1baf9ece532ec50704c807d04a15bdeabf5d79b40d482db",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:6c8328293ea5aa1f:b25e576b645e1765",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
      "pid": 21472,
      "sha256": "be9114ff19349efe19e3f41812925e1a09978d7b63aff9412a87eed7f2904364",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:1ceda9c220daf075:b25e576b645e1765",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "kernel32.lib",
      "pid": 21472,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:1ceda9c220daf075:b25e576b645e1765",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "kernel32.lib",
      "pid": 21472,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:1ceda9c220daf075:b25e576b645e1765",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "kernel32.lib",
      "pid": 21472,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:1db9512c4d5c31e6:b25e576b645e1765",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "ntdll.lib",
      "pid": 21472,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:861f0814f9c52599:b25e576b645e1765",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "userenv.lib",
      "pid": 21472,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:50848825683fdca9:b25e576b645e1765",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "ws2_32.lib",
      "pid": 21472,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "used:link:50b281732a322d11:df7d4e53c08047f7:b25e576b645e1765",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "path": "dbghelp.lib",
      "pid": 21472,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o"
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
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.175",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 21472,
      "ppid": 18736,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\rustc0SdXhw\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.build_script_build.d322bf7b5c9256ee-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.87kq5urjqndxntxrqbhmtek6i.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build_script_build-b3fe1a0a886550a6.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "directories": [
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000200       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000250       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000270       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000288       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000298       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000340       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000358       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000388       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140038200     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000250       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140038250     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000270       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140038270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140038288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140038298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400382a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000340       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140038340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140038358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000388       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140038388     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-link-link-21472-1783954824389034000.map",
      "pid": 21472,
      "ppid": 18736,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-link-link-21472-1783954824389034000.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\rustco57ypk\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "kind": "exec",
      "pid": 8580,
      "ppid": 20116,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\rustco57ypk\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\rustco57ypk\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\rustco57ypk\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 8580,
      "ppid": 20116,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\rustco57ypk\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000300       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000320       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000003f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000418       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000448       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000460       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400c5020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400c5298     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400c52b0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000300       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400c5300     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000320       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400c5320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400c5338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400c5348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400c5358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000003f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400c53f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400c5408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000418       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400c5418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000448       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400c5448     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000460       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400c5460     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-link-link-8580-1783954825246665400.map",
      "pid": 8580,
      "ppid": 20116,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-link-link-8580-1783954825246665400.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "kind": "exec",
      "pid": 18668,
      "ppid": 13124,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c"
      ],
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "event_id": "used:cl:c6cdd849d77512e0:49a37e82575f1c52:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c",
      "pid": 18668,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c"
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
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\7470993287477488415detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
      "pid": 18668,
      "ppid": 13124,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "kind": "exec",
      "pid": 9280,
      "ppid": 13124,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
      "pid": 9280,
      "ppid": 13124,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
        "c_src/mimalloc/v2/include",
        "-I",
        "c_src/mimalloc/v2/src",
        "-W4",
        "-DMI_DEBUG=0",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
        "-c",
        "c_src/mimalloc/v2/src/static.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "kind": "exec",
      "pid": 7436,
      "ppid": 13124,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
        "c_src/mimalloc/v2/include",
        "-I",
        "c_src/mimalloc/v2/src",
        "-W4",
        "-DMI_DEBUG=0",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
        "-c",
        "c_src/mimalloc/v2/src/static.c"
      ],
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "event_id": "used:cl:c6cdd849d77512e0:cb18d1e13c079560:1859776464a49585",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
      "path": "c_src/mimalloc/v2/src/static.c",
      "pid": 7436,
      "sha256": "81e27487e494d2b32cb16a2605d61ee64fe3a71c409d5be3a673950ff769bd73",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
        "c_src/mimalloc/v2/include",
        "-I",
        "c_src/mimalloc/v2/src",
        "-W4",
        "-DMI_DEBUG=0",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
        "-c",
        "c_src/mimalloc/v2/src/static.c"
      ],
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "event_id": "used:cl:c6cdd849d77512e0:39fbf236f3006dbd:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
      "pid": 7436,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
        "c_src/mimalloc/v2/include",
        "-I",
        "c_src/mimalloc/v2/src",
        "-W4",
        "-DMI_DEBUG=0",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
        "-c",
        "c_src/mimalloc/v2/src/static.c"
      ],
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "event_id": "used:cl:c6cdd849d77512e0:cb18d1e13c079560:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "c_src/mimalloc/v2/src/static.c",
      "pid": 7436,
      "sha256": "81e27487e494d2b32cb16a2605d61ee64fe3a71c409d5be3a673950ff769bd73",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
        "c_src/mimalloc/v2/include",
        "-I",
        "c_src/mimalloc/v2/src",
        "-W4",
        "-DMI_DEBUG=0",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
        "-c",
        "c_src/mimalloc/v2/src/static.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
      "src": "c_src/mimalloc/v2/src/static.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
        "c_src/mimalloc/v2/include",
        "-I",
        "c_src/mimalloc/v2/src",
        "-W4",
        "-DMI_DEBUG=0",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
        "-c",
        "c_src/mimalloc/v2/src/static.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
        "c_src/mimalloc/v2/src/static.c"
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
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
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
        "c_src/mimalloc/v2/include",
        "-I",
        "c_src/mimalloc/v2/src",
        "-W4",
        "-DMI_DEBUG=0",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
        "-c",
        "c_src/mimalloc/v2/src/static.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
      "pid": 7436,
      "ppid": 13124,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17108,
      "ppid": 13124,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
      ],
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "event_id": "used:lib:c6cdd849d77512e0:1859776464a49585:5bfc4e7aabcb8491",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
      "pid": 17108,
      "sha256": "c99e5bd914fdd61bb66ff32b3b7f688a47ad5aefe1821744ae462268c78e8703",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
      ],
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "event_id": "used:lib:c6cdd849d77512e0:1859776464a49585:62505024992a3d7e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o",
      "pid": 17108,
      "sha256": "c99e5bd914fdd61bb66ff32b3b7f688a47ad5aefe1821744ae462268c78e8703",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\libmimalloc.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out\\077ae3504b1c7768-static.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "cargo_pkg_name": "libmimalloc-sys",
      "cargo_pkg_version": "0.1.44",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\.tmp\\native-trace-17988-1783954823744\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
      "pid": 17108,
      "ppid": 13124,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "libmimalloc-sys",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "event_id": "bsrun:0afebe8257a9a86b:b14c63d2611fdb92:f369cf30dbf7dc18",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "0.1.44",
      "_owner": {
        "crate": "libmimalloc-sys",
        "version": "0.1.44",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44#libmimalloc-sys@0.1.44",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "event_id": "bsrun:0e1b181b8bf4bbf6:6cea0e64599dc2fa:d4339d94c7df18fa",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/target/debug/build/libc-b3fe1a0a886550a6\\build-script-build.exe",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-f1_wanlw/src/libmimalloc-sys-0.1.44/target/debug/build/libc-b3fe1a0a886550a6/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
      "success": true,
      "target": null,
      "version": "0.2.175",
      "_owner": {
        "crate": "libc",
        "version": "0.2.175",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.175",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.175",
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
      "raw_event_count": 31623,
      "parsed_event_count": 31623,
      "parse_error_count": 0,
      "command_line_event_count": 31623,
      "build_script_root_event_count": 598,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 4885,
      "dropped_event_count": 16430
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 2672,
      "ppid": 18056,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T15:00:24.600964+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6\\build-script-build.exe",
      "root_cargo_pid": 11064,
      "build_script_root_pid": 2672,
      "build_script_related": true,
      "build_script_target_dir": "libc-b3fe1a0a886550a6"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 20012,
      "ppid": 2672,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
      ],
      "comm": "rustc-trace-wrapper.exe",
      "time": "2026-07-13T15:00:24.610005+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "root_cargo_pid": 11064,
      "build_script_root_pid": 2672,
      "build_script_related": true,
      "build_script_target_dir": "libc-b3fe1a0a886550a6"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 18976,
      "ppid": 20012,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T15:00:24.620531+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 11064,
      "build_script_root_pid": 2672,
      "build_script_related": true,
      "build_script_target_dir": "libc-b3fe1a0a886550a6"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13124,
      "ppid": 18056,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T15:00:25.589623+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1\\build-script-build.exe",
      "root_cargo_pid": 11064,
      "build_script_root_pid": 13124,
      "build_script_related": true,
      "build_script_target_dir": "libmimalloc-sys-524f41214193c3d1"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 15584,
      "ppid": 19636,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
      "time": "2026-07-13T15:00:23.983268+00:00",
      "end_time": "2026-07-13T15:00:24.003819+00:00",
      "start_unix_nanos": 1783954823983268400,
      "end_unix_nanos": 1783954824003818800,
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
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 19956,
      "ppid": 19636,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
      "time": "2026-07-13T15:00:24.011786+00:00",
      "end_time": "2026-07-13T15:00:24.035199+00:00",
      "start_unix_nanos": 1783954824011786500,
      "end_unix_nanos": 1783954824035199000,
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
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 21336,
      "ppid": 18056,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
      "time": "2026-07-13T15:00:24.099985+00:00",
      "end_time": "2026-07-13T15:00:24.121067+00:00",
      "start_unix_nanos": 1783954824099985100,
      "end_unix_nanos": 1783954824121066700,
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
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 15884,
      "ppid": 18056,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
      "time": "2026-07-13T15:00:24.129120+00:00",
      "end_time": "2026-07-13T15:00:24.154026+00:00",
      "start_unix_nanos": 1783954824129120200,
      "end_unix_nanos": 1783954824154025800,
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
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 12632,
      "ppid": 18056,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
      "time": "2026-07-13T15:00:24.166600+00:00",
      "end_time": "2026-07-13T15:00:24.187845+00:00",
      "start_unix_nanos": 1783954824166599900,
      "end_unix_nanos": 1783954824187845300,
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
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 21408,
      "ppid": 18056,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2015 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-1.3.0\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=f9b15d7751a7b186 -C extra-filename=-8a85cb2cd59e9679 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:00:24.210058+00:00",
      "end_time": "2026-07-13T15:00:24.333772+00:00",
      "start_unix_nanos": 1783954824210058400,
      "end_unix_nanos": 1783954824333772400,
      "crate_name": "shlex",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 18664,
      "ppid": 18056,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=2c2c20fd7bde7f69",
        "-C",
        "extra-filename=-b3fe1a0a886550a6",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=2c2c20fd7bde7f69 -C extra-filename=-b3fe1a0a886550a6 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6 -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=2c2c20fd7bde7f69",
        "-C",
        "extra-filename=-b3fe1a0a886550a6",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:00:24.212862+00:00",
      "end_time": "2026-07-13T15:00:24.510017+00:00",
      "start_unix_nanos": 1783954824212861500,
      "end_unix_nanos": 1783954824510017500,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libc-b3fe1a0a886550a6"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 16844,
      "ppid": 18056,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34\\src\\lib.rs",
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
        "metadata=88301a1d3ea28166",
        "-C",
        "extra-filename=-fcfbeeaf61d3a45b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=88301a1d3ea28166 -C extra-filename=-fcfbeeaf61d3a45b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.34\\src\\lib.rs",
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
        "metadata=88301a1d3ea28166",
        "-C",
        "extra-filename=-fcfbeeaf61d3a45b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libshlex-8a85cb2cd59e9679.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:00:24.289457+00:00",
      "end_time": "2026-07-13T15:00:25.118007+00:00",
      "start_unix_nanos": 1783954824289456700,
      "end_unix_nanos": 1783954825118007100,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 20012,
      "ppid": 2672,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--version"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --version",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--version"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:00:24.614838+00:00",
      "end_time": "2026-07-13T15:00:24.633984+00:00",
      "start_unix_nanos": 1783954824614838300,
      "end_unix_nanos": 1783954824633983700,
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
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 21400,
      "ppid": 18056,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libc",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=f9c6ff215309a4c2",
        "-C",
        "extra-filename=-5d5a70abe056473f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "--cfg",
        "freebsd11",
        "--cfg",
        "libc_const_extern_fn",
        "--check-cfg",
        "cfg(emscripten_old_stat_abi)",
        "--check-cfg",
        "cfg(espidf_time32)",
        "--check-cfg",
        "cfg(freebsd10)",
        "--check-cfg",
        "cfg(freebsd11)",
        "--check-cfg",
        "cfg(freebsd12)",
        "--check-cfg",
        "cfg(freebsd13)",
        "--check-cfg",
        "cfg(freebsd14)",
        "--check-cfg",
        "cfg(freebsd15)",
        "--check-cfg",
        "cfg(gnu_file_offset_bits64)",
        "--check-cfg",
        "cfg(gnu_time_bits64)",
        "--check-cfg",
        "cfg(libc_const_extern_fn)",
        "--check-cfg",
        "cfg(libc_deny_warnings)",
        "--check-cfg",
        "cfg(libc_thread_local)",
        "--check-cfg",
        "cfg(libc_ctest)",
        "--check-cfg",
        "cfg(linux_time_bits64)",
        "--check-cfg",
        "cfg(musl_v1_2_3)",
        "--check-cfg",
        "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\"))",
        "--check-cfg",
        "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
        "--check-cfg",
        "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=f9c6ff215309a4c2 -C extra-filename=-5d5a70abe056473f --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --cap-lints allow --cfg freebsd11 --cfg libc_const_extern_fn --check-cfg cfg(emscripten_old_stat_abi) --check-cfg cfg(espidf_time32) --check-cfg cfg(freebsd10) --check-cfg cfg(freebsd11) --check-cfg cfg(freebsd12) --check-cfg cfg(freebsd13) --check-cfg cfg(freebsd14) --check-cfg cfg(freebsd15) --check-cfg cfg(gnu_file_offset_bits64) --check-cfg cfg(gnu_time_bits64) --check-cfg cfg(libc_const_extern_fn) --check-cfg cfg(libc_deny_warnings) --check-cfg cfg(libc_thread_local) --check-cfg cfg(libc_ctest) --check-cfg cfg(linux_time_bits64) --check-cfg cfg(musl_v1_2_3) --check-cfg \"cfg(target_os,values(\\\"switch\\\",\\\"aix\\\",\\\"ohos\\\",\\\"hurd\\\",\\\"rtems\\\",\\\"visionos\\\",\\\"nuttx\\\",\\\"cygwin\\\"))\" --check-cfg \"cfg(target_env,values(\\\"illumos\\\",\\\"wasi\\\",\\\"aix\\\",\\\"ohos\\\",\\\"nto71_iosock\\\",\\\"nto80\\\"))\" --check-cfg \"cfg(target_arch,values(\\\"loongarch64\\\",\\\"mips32r6\\\",\\\"mips64r6\\\",\\\"csky\\\"))\"",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libc",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.175\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=f9c6ff215309a4c2",
        "-C",
        "extra-filename=-5d5a70abe056473f",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "--cfg",
        "freebsd11",
        "--cfg",
        "libc_const_extern_fn",
        "--check-cfg",
        "cfg(emscripten_old_stat_abi)",
        "--check-cfg",
        "cfg(espidf_time32)",
        "--check-cfg",
        "cfg(freebsd10)",
        "--check-cfg",
        "cfg(freebsd11)",
        "--check-cfg",
        "cfg(freebsd12)",
        "--check-cfg",
        "cfg(freebsd13)",
        "--check-cfg",
        "cfg(freebsd14)",
        "--check-cfg",
        "cfg(freebsd15)",
        "--check-cfg",
        "cfg(gnu_file_offset_bits64)",
        "--check-cfg",
        "cfg(gnu_time_bits64)",
        "--check-cfg",
        "cfg(libc_const_extern_fn)",
        "--check-cfg",
        "cfg(libc_deny_warnings)",
        "--check-cfg",
        "cfg(libc_thread_local)",
        "--check-cfg",
        "cfg(libc_ctest)",
        "--check-cfg",
        "cfg(linux_time_bits64)",
        "--check-cfg",
        "cfg(musl_v1_2_3)",
        "--check-cfg",
        "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\"))",
        "--check-cfg",
        "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
        "--check-cfg",
        "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:00:24.647295+00:00",
      "end_time": "2026-07-13T15:00:24.720789+00:00",
      "start_unix_nanos": 1783954824647295500,
      "end_unix_nanos": 1783954824720788800,
      "crate_name": "libc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 19176,
      "ppid": 18056,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
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
        "cfg(feature, values(\"arena\", \"cty\", \"debug\", \"debug_in_debug\", \"extended\", \"local_dynamic_tls\", \"no_thp\", \"override\", \"secure\", \"v3\"))",
        "-C",
        "metadata=ea213bd661f48a8b",
        "-C",
        "extra-filename=-524f41214193c3d1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libcc-fcfbeeaf61d3a45b.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arena\\\", \\\"cty\\\", \\\"debug\\\", \\\"debug_in_debug\\\", \\\"extended\\\", \\\"local_dynamic_tls\\\", \\\"no_thp\\\", \\\"override\\\", \\\"secure\\\", \\\"v3\\\"))\" -C metadata=ea213bd661f48a8b -C extra-filename=-524f41214193c3d1 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libcc-fcfbeeaf61d3a45b.rlib",
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
        "cfg(feature, values(\"arena\", \"cty\", \"debug\", \"debug_in_debug\", \"extended\", \"local_dynamic_tls\", \"no_thp\", \"override\", \"secure\", \"v3\"))",
        "-C",
        "metadata=ea213bd661f48a8b",
        "-C",
        "extra-filename=-524f41214193c3d1",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\libcc-fcfbeeaf61d3a45b.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:00:25.133584+00:00",
      "end_time": "2026-07-13T15:00:25.451113+00:00",
      "start_unix_nanos": 1783954825133583800,
      "end_unix_nanos": 1783954825451113500,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-524f41214193c3d1"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "libmimalloc-sys:0.1.44:5536",
      "root_process_pid": 11064,
      "pid": 15676,
      "ppid": 18056,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libmimalloc_sys",
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
        "cfg(feature, values(\"arena\", \"cty\", \"debug\", \"debug_in_debug\", \"extended\", \"local_dynamic_tls\", \"no_thp\", \"override\", \"secure\", \"v3\"))",
        "-C",
        "metadata=55c77d3e9c4d6db0",
        "-C",
        "extra-filename=-961d3444c2719c7b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--extern",
        "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\liblibc-5d5a70abe056473f.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
        "-l",
        "static=mimalloc",
        "-l",
        "psapi",
        "-l",
        "shell32",
        "-l",
        "user32",
        "-l",
        "advapi32",
        "-l",
        "bcrypt"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libmimalloc_sys --edition=2018 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"arena\\\", \\\"cty\\\", \\\"debug\\\", \\\"debug_in_debug\\\", \\\"extended\\\", \\\"local_dynamic_tls\\\", \\\"no_thp\\\", \\\"override\\\", \\\"secure\\\", \\\"v3\\\"))\" -C metadata=55c77d3e9c4d6db0 -C extra-filename=-961d3444c2719c7b --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps --extern libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\liblibc-5d5a70abe056473f.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out -l static=mimalloc -l psapi -l shell32 -l user32 -l advapi32 -l bcrypt",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libmimalloc_sys",
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
        "cfg(feature, values(\"arena\", \"cty\", \"debug\", \"debug_in_debug\", \"extended\", \"local_dynamic_tls\", \"no_thp\", \"override\", \"secure\", \"v3\"))",
        "-C",
        "metadata=55c77d3e9c4d6db0",
        "-C",
        "extra-filename=-961d3444c2719c7b",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps",
        "--extern",
        "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps\\liblibc-5d5a70abe056473f.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\build\\libmimalloc-sys-215aebaae69fb964\\out",
        "-l",
        "static=mimalloc",
        "-l",
        "psapi",
        "-l",
        "shell32",
        "-l",
        "user32",
        "-l",
        "advapi32",
        "-l",
        "bcrypt"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T15:00:26.332024+00:00",
      "end_time": "2026-07-13T15:00:26.402161+00:00",
      "start_unix_nanos": 1783954826332024300,
      "end_unix_nanos": 1783954826402160600,
      "crate_name": "libmimalloc_sys",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-f1_wanlw\\src\\libmimalloc-sys-0.1.44\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 1586,
    "crate": "libmimalloc-sys",
    "version": "0.1.44",
    "crate_id": "143295",
    "version_id": "1700858",
    "downloads": 10598886,
    "cumulative_downloads": 98133345024,
    "cumulative_share_of_global": 0.3668979223913751,
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
