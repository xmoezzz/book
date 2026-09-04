# `brotli-sys` `0.3.2`

Platform: Linux aarch64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned native flows

## Flow 001

Artifact: `/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/libbrotli.a`

Owner: `brotli-sys` `0.3.2`

### Source files

* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/common/dictionary.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/dec/bit_reader.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/dec/decode.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/dec/huffman.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/dec/state.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/backward_references.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/backward_references_hq.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/bit_cost.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/block_splitter.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/brotli_bit_stream.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/cluster.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/compress_fragment.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/compress_fragment_two_pass.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/dictionary_hash.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/encode.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/entropy_encode.c`
* `/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/brotli/enc/histogram.c`

### Source acquisition records

#### Record 1

```json
{
  "acquisition_kind": "git_submodule",
  "argv": [
    "git",
    "submodule",
    "update",
    "--init"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "checkout_root": null,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "acq-ext:git:f233c38d147b3728:e3b0c44298fc1c14",
  "exit_code": 128,
  "kind": "acquisition",
  "output": null,
  "pid": 463550,
  "success": false,
  "tool": "git",
  "url": null,
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

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
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/backward_references.c",
    "-quiet",
    "-dumpbase",
    "backward_references.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/backward_references.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 464500,
  "ppid": 464496,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 2

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/common/dictionary.c",
    "-quiet",
    "-dumpbase",
    "dictionary.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/common/dictionary.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 463669,
  "ppid": 463667,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 3

```json
{
  "event": "compile",
  "tool": "/usr/bin/aarch64-linux-gnu-gcc",
  "real_tool": "/usr/bin/aarch64-linux-gnu-gcc",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
    "-c",
    "brotli/dec/huffman.c"
  ],
  "src": "brotli/dec/huffman.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "pid": 464311,
  "ppid": 463549,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 4

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/dec/bit_reader.c",
    "-quiet",
    "-dumpbase",
    "bit_reader.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/dec/bit_reader.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 463756,
  "ppid": 463754,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 5

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/encode.c",
    "-quiet",
    "-dumpbase",
    "encode.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/encode.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466045,
  "ppid": 466044,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 6

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/histogram.c",
    "-quiet",
    "-dumpbase",
    "histogram.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/histogram.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466212,
  "ppid": 466209,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 7

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/compress_fragment.c",
    "-quiet",
    "-dumpbase",
    "compress_fragment.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/compress_fragment.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465652,
  "ppid": 465649,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 8

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/dictionary_hash.c",
    "-quiet",
    "-dumpbase",
    "dictionary_hash.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/dictionary_hash.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466020,
  "ppid": 466017,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 9

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/dec/decode.c",
    "-quiet",
    "-dumpbase",
    "decode.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/dec/decode.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 463856,
  "ppid": 463847,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 10

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/cluster.c",
    "-quiet",
    "-dumpbase",
    "cluster.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/cluster.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465576,
  "ppid": 465573,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 11

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/compress_fragment_two_pass.c",
    "-quiet",
    "-dumpbase",
    "compress_fragment_two_pass.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/compress_fragment_two_pass.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465909,
  "ppid": 465908,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 12

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/bit_cost.c",
    "-quiet",
    "-dumpbase",
    "bit_cost.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/bit_cost.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465268,
  "ppid": 465266,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 13

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/block_splitter.c",
    "-quiet",
    "-dumpbase",
    "block_splitter.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/block_splitter.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465306,
  "ppid": 465305,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 14

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/brotli_bit_stream.c",
    "-quiet",
    "-dumpbase",
    "brotli_bit_stream.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/brotli_bit_stream.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465349,
  "ppid": 465348,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 15

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/entropy_encode.c",
    "-quiet",
    "-dumpbase",
    "entropy_encode.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/entropy_encode.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466181,
  "ppid": 466180,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 16

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/backward_references_hq.c",
    "-quiet",
    "-dumpbase",
    "backward_references_hq.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/backward_references_hq.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465120,
  "ppid": 465117,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 17

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/dec/state.c",
    "-quiet",
    "-dumpbase",
    "state.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/dec/state.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 464410,
  "ppid": 464407,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
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
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/libbrotli.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
    "..."
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/libbrotli.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": true,
  "pid": 466636,
  "ppid": 463549,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
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
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "workspace_root": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
      "name": "brotli-sys",
      "version": "0.3.2",
      "manifest_path": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
      "name": "cc",
      "version": "1.2.67",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
      "name": "find-msvc-tools",
      "version": "0.1.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
    }
  ],
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "kind": "exec",
  "pid": 462442,
  "ppid": 462247,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:b4fed19ec505f12e:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
  "pid": 462442,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:c5eb16742d92300e:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
  "pid": 462442,
  "sha256": "750e5b687b769ef8e1f6a9de3b3b4cc39d771526f669d42b53a924666b856dae",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:135ba558c9da774d:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
  "pid": 462442,
  "sha256": "53140dc43536033138eb06a34e55a6a0ff33641d1e3937f2ad7a716aa3ee683a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:2a8f9787c6af6fe7:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
  "pid": 462442,
  "sha256": "d07a13370e4d6a6a6abdcfd76827ef7c0991362bd0043ae1f902898148c0a6fb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:e37cae5c272f2a12:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
  "pid": 462442,
  "sha256": "c1d04af73990d492aeddeae1678948453dcb03afe9564782fafda521716fd66f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:759cfb97b73257cf:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
  "pid": 462442,
  "sha256": "8ef6a5d57a020f215781ab0bc6a156213342dbd5f757c677fe270d0bad9c7795",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
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
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "context_path": "/tmp/native-trace-460526-1783994514766/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-460526-1783994514766/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 462442,
  "ppid": 462247,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11",
    "/target/debug/build/libc-8a22300c8f78b6db",
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
      "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-462442-1783994521136353534.map",
  "pid": 462442,
  "ppid": 462247,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-462442-1783994521136353534.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 463431,
  "ppid": 463347,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:f9598343693f9dc2:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
  "pid": 463431,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:fe69b3de69a443d0:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "066906ba68ec21b810aaa3c0517c0308a534e30fca9c3622c3d0950704428a71",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:674e5c441859ff5b:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "06f17cd715816b7411d31a79b8580c86dfcb3e9057e3a3222403e197094eb5d7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:c5f8ad7a7509399b:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "07dcc9020fb6262a403e53b1805048b8971d6a80204fc6c16b690fdb746d3469",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:b08d43b4fc18ac68:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "9d6f6f42a20e945b7350fcd9fe5e73d466e4844c7001683c097f7d872ea63a19",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:9c70f17e65921a88:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "eb4737e86588cd368203f578ae6862356cf3d741b2aa882c5e2005f583e3a12e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:f2ad538339242aae:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "454f319e4b32ffdef131dea8c5f675f0161e9a9720142b3af9a7ec932a7075bb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:8a7c13e4f82cdb1a:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "118b1d3cca9156d424875c26b30b1728b308cc10139f734231792604fe721e45",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:0aa834dfd777b434:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "ca1854b8cacbb691d5f22f581deada73bf400d9c3e5add751eb0734016dbaff1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:f0e425713f9f67a7:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "7c405faedd91a8c11780a97ff4ebd6acafbea1912796b04df58005993766446f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:0569919e222832b5:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "d5161492432dd4dd3191a599276f42a0c5a1e9f2dc0c0c687421a6d505c69c50",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:e6e0023477a70c32:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "1dad8e6f0bf8913023efe3a29f9a80671391170ca0fb57b9d712435586fb8fbf",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:b41c97349864bf0f:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "a4ede0d9fd60a4a3a93c21ea33624039eb713acb0ee4de1eeea7c08ef4ddc843",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "used:cc:f233c38d147b3728:327ce420b9f9e7cb:5484f17373dac776",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
  "pid": 463431,
  "sha256": "beef5da5a6c1990c62ffa6870030b80fca74e235a45ee672440764f3d7b85ad9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 27

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
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
  "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "context_path": "/tmp/native-trace-460526-1783994514766/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-460526-1783994514766/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 463431,
  "ppid": 463347,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 29

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus",
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
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
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
      "kind": "object",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-463431-1783994523506733384.map",
  "pid": 463431,
  "ppid": 463347,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-463431-1783994523506733384.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "git",
    "submodule",
    "update",
    "--init"
  ],
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "exit_code": 128,
  "kind": "exec",
  "pid": 463550,
  "ppid": 463549,
  "success": false,
  "tool": "git",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 31

```json
{
  "acquisition_kind": "git_submodule",
  "argv": [
    "git",
    "submodule",
    "update",
    "--init"
  ],
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "checkout_root": null,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "acq-ext:git:f233c38d147b3728:e3b0c44298fc1c14",
  "exit_code": 128,
  "kind": "acquisition",
  "output": null,
  "pid": 463550,
  "success": false,
  "tool": "git",
  "url": null,
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 32

```json
{
  "argv": [
    "git",
    "submodule",
    "update",
    "--init"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "cargo_pkg_name": "brotli-sys",
  "cargo_pkg_version": "0.3.2",
  "context_path": "/tmp/native-trace-460526-1783994514766/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "exit_code": 128,
  "host": "x86_64-unknown-linux-gnu",
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-460526-1783994514766/events/00000000-cargo-metadata.json",
  "num_jobs": "16",
  "opt_level": "0",
  "out_dir": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out",
  "pid": 463550,
  "ppid": 463549,
  "profile": "debug",
  "real_tool": "/usr/bin/git",
  "root_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "success": false,
  "target": "aarch64-unknown-linux-gnu",
  "tool": "git",
  "workspace_root": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 33

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

#### Record 34

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 1556,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1558,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "tc            468006 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.760  rustc            468007 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.772  rustc            468010 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.772  rustc            468011 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.786  execsnoop        468018 468002   0 /usr/local/bin/execsnoop -t\n16.786  python3          468018 468002   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.787  execsnoop        468021 468003   0 /usr/local/bin/execsnoop -t\n16.787  python3          468021 468003   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.281  runc             468024 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2801572281 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n17.287  exe              468031 468024   0 /proc/self/exe init\n17.304  curl             468034 468024   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n17.538  sh               468040 2147557   0 /bin/sh -c which ps\n17.539  which            468040 2147557   0 /usr/bin/which ps\n17.541  sh               468041 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.543  ps               468041 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.569  sh               468042 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.571  cpuUsage.sh      468042 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.572  sed              468043 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.574  cat              468044 468042   0 /usr/bin/cat /proc/2240539/stat\n17.576  cat              468045 468042   0 /usr/bin/cat /proc/4193716/stat\n17.577  sleep            468046 468042   0 /usr/bin/sleep 1\n18.579  sed              468047 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.581  cat              468048 468042   0 /usr/bin/cat /proc/2240539/stat\n18.583  cat              468050 468042   0 /usr/bin/cat /proc/4193716/stat\n18.651  cargo            468052 468002   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n18.664  rustc            468053 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.683  rustc            468059 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n18.726  cc               468079 468059   0 /tmp/native-trace-468002-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.727  cc               468080 468079   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.730  collect2         468081 468080   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.731  ld.lld           468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n18.733  rust-lld         468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.769  build-script-bu  468100 468052   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n18.774  rustc            468102 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=01dbfa75f86e934e ...\n18.922  cargo            468109 468003   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.935  rustc            468110 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.954  rustc            468116 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n18.976  runc             468120 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup kill --all c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 9\n18.994  runc             468143 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup delete c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n18.996  cc               468142 468116   0 /tmp/native-trace-468003-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.997  cc               468149 468142   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n19.000  collect2         468150 468149   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.001  ld.lld           468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n19.003  rust-lld         468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.047  build-script-bu  468169 468109   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n19.053  rustc            468171 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=eb508d71aca425cd ...\n19.189  containerd-shim  468178 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d delete\n19.191  runc             468184 468178   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b7 --log-format json delete --force c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n19.252  systemd-sysctl   468190 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth26ae1bd --prefix=/net/ipv4/neigh/veth26ae1bd --prefix=/net/ipv6/conf/veth26ae1bd --prefix=/net/ipv6/neigh/veth26ae1bd\n19.263  runc             468191 461041   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb --log-format json --systemd-cgroup kill --all 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468 9\n19.280  runc             468197 461041   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb --log-format json --systemd-cgroup delete 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468\n19.485  containerd-shim  468203 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb delete\n19.487  runc             468209 468203   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed46 --log-format json delete --force 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468\n19.527  sh               468217 467838   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth83795da\n19.528  ethtool          468218 468217   0 /usr/sbin/ethtool -i veth83795da\n19.529  sed              468219 468217   0 /usr/bin/sed -n s/^driver: //p\n19.534  systemd-sysctl   468222 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth83795da --prefix=/net/ipv4/neigh/veth83795da --prefix=/net/ipv6/conf/veth83795da --prefix=/net/ipv6/neigh/veth83795da\n19.681  runc             468224 461102   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c --log-format json --systemd-cgroup kill --all aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358 9\n19.699  runc             468230 461102   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c --log-format json --systemd-cgroup delete aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358\n19.779  runc             468236 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process812323305 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n19.784  exe              468243 468236   0 /proc/self/exe init\n19.793  curl             468245 468236   0 /usr/bin/curl -f http://localhost:9091/healthz\n19.875  containerd-shim  468252 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c delete\n19.877  runc             468259 468252   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a35 --log-format json delete --force aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358\n19.921  systemd-sysctl   468264 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth61a52e7 --prefix=/net/ipv4/neigh/veth61a52e7 --prefix=/net/ipv6/conf/veth61a52e7 --prefix=/net/ipv6/neigh/veth61a52e7\n20.626  runc             468266 461203   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3 --log-format json --systemd-cgroup kill --all 1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3a8219 9\n20.643  runc             468272 461203   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3 --log-format json --systemd-cgroup delete 1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3a8219\n20.834  containerd-shim  468279 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3a8219 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3 delete\n20.837  runc             468285 468279   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3a821 --log-format json delete --force 1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3a8219\n20.879  systemd-sysctl   468291 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethac32133 --prefix=/net/ipv4/neigh/vethac32133 --prefix=/net/ipv6/conf/vethac32133 --prefix=/net/ipv6/neigh/vethac32133\n21.031  runc             468292 430091   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e80230344 --log-format json --systemd-cgroup kill --all 99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e8023034471195 9\n21.048  runc             468298 430091   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e80230344 --log-format json --systemd-cgroup delete 99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e8023034471195\n21.213  containerd-shim  468304 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e8023034471195 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e80230344 delete\n21.216  runc             468311 468304   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e802303447119 --log-format json delete --force 99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e8023034471195\n21.249  systemd-sysctl   468316 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha43ea2d --prefix=/net/ipv4/neigh/vetha43ea2d --prefix=/net/ipv6/conf/vetha43ea2d --prefix=/net/ipv6/neigh/vetha43ea2d\n22.537  sh               468319 2147557   0 /bin/sh -c which ps\n22.538  which            468319 2147557   0 \n22.540  sh               468320 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.541  ps               468320 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.542  git              468318 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n22.563  sh               468321 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n22.565  cpuUsage.sh      468321 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n22.566  sed              468322 468321   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n22.568  cat              468323 468321   0 /usr/bin/cat /proc/2240539/stat\n22.569  cat              468324 468321   0 /usr/bin/cat /proc/4193716/stat\n22.570  sleep            468325 468321   0 /usr/bin/sleep 1\n23.005  cross            468326 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n23.006  rustc            468328 468326   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.013  rustc            468328 468326   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.028  rustc            468341 468326   0 /home/xmoe/.cargo/bin/rustc -vV\n23.034  rustc            468341 468326   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.045  cargo            468351 468326   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n23.052  cargo            468351 468326   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n23.066  rustc            468360 468351   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.078  rustc            468362 468351   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.091  rustc            468366 468351   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n23.095  cross            468367 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n23.096  rustc            468370 468367   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.102  rustc            468370 468367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.113  rustc            468385 468367   0 /home/xmoe/.cargo/bin/rustc -vV\n23.118  rustc            468385 468367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.128  cargo            468396 468367   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n23.133  cargo            468396 468367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n23.142  rustc            468405 468396   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.151  rustc            468407 468396   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.163  rustc            468411 468396   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n23.543  cross            468415 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n23.544  rustc            468418 468415   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.550  rustc            468418 468415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.564  rustc            468431 468415   0 /home/xmoe/.cargo/bin/rustc -vV\n23.571  rustc            468431 468415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.572  sed              468440 468321   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n23.574  cat              468441 468321   0 /usr/bin/cat /proc/2240539/stat\n23.576  cat              468443 468321   0 /usr/bin/cat /proc/4193716/stat\n23.583  cargo            468446 468415   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n23.590  cargo            468446 468415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n23.603  rustc            468455 468446   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.616  rustc            468458 468446   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.631  rustc            468462 468446   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n23.643  cross            468466 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n23.644  rustc            468469 468466   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.651  rustc            468469 468466   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.665  rustc            468481 468466   0 /home/xmoe/.cargo/bin/rustc -vV\n23.671  rustc            468481 468466   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.682  cargo            468491 468466   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n23.689  cargo            468491 468466   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n23.702  rustc            468500 468491   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.714  rustc            468502 468491   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.728  rustc            468506 468491   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n23.732  cross            468507 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n23.733  rustc            468510 468507   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.738  rustc            468510 468507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.750  rustc            468525 468507   0 /home/xmoe/.cargo/bin/rustc -vV\n23.756  rustc            468525 468507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.765  cargo            468535 468507   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n23.769  cargo            468535 468507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n23.779  rustc            468544 468535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.789  rustc            468546 468535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.801  rustc            468550 468535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n24.268  runc             468554 460030   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6 --log-format json --systemd-cgroup kill --all bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6b44bb 9\n24.287  runc             468560 460030   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6 --log-format json --systemd-cgroup delete bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6b44bb\n24.444  containerd-shim  468567 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6b44bb -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6 delete\n24.447  runc             468574 468567   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6b44b --log-format json delete --force bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6b44bb\n24.492  sh               468582 468579   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth64e3490\n24.493  ethtool          468583 468582   0 /usr/sbin/ethtool -i veth64e3490\n24.493  sed              468584 468582   0 /usr/bin/sed -n s/^driver: //p\n24.500  systemd-sysctl   468587 468579   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth64e3490 --prefix=/net/ipv4/neigh/veth64e3490 --prefix=/net/ipv6/conf/veth64e3490 --prefix=/net/ipv6/neigh/veth64e3490\n24.529  rustup           468589 459404   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n25.362  runc             468599 427640   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883dda --log-format json --systemd-cgroup kill --all 68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883ddaafa5c 9\n25.378  runc             468605 427640   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883dda --log-format json --systemd-cgroup delete 68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883ddaafa5c\n25.576  containerd-shim  468611 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883ddaafa5c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883dda delete\n25.578  runc             468618 468611   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883ddaafa5 --log-format json delete --force 68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883ddaafa5c\n25.614  systemd-sysctl   468623 468579   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth46be2bd --prefix=/net/ipv4/neigh/veth46be2bd --prefix=/net/ipv6/conf/veth46be2bd --prefix=/net/ipv6/neigh/veth46be2bd\n26.542  rustc            468626 468351   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n26.656  rustc            468628 468446   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n26.768  rustc            468630 468491   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.029  rustc            468632 468367   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n27.034  rustc            468632 468367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n27.046  docker           468644 468367   0 /usr/bin/docker --help\n27.049  rustc            468650 468326   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n27.051  rustc            468651 468507   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n27.054  rustc            468650 468326   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n27.056  rustc            468651 468507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n27.061  docker           468673 468367   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n27.066  docker           468685 468326   0 /usr/bin/docker --help\n27.067  docker           468686 468507   0 /usr/bin/docker --help\n27.073  runc             468705 1599     0 /usr/bin/runc --version\n27.076  docker-init      468716 1599     0 /usr/bin/docker-init --version\n27.078  docker           468721 468367   0 /usr/bin/docker info -f {{.SecurityOptions}}\n27.079  docker           468722 468326   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n27.080  docker           468723 468507   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n27.089  runc             468752 1599     0 /usr/bin/runc --version\n27.090  runc             468753 1599     0 /usr/bin/runc --version\n27.091  runc             468756 1599     0 /usr/bin/runc --version\n27.093  docker-init      468770 1599     0 /usr/bin/docker-init --version\n27.093  docker-init      468771 1599     0 /usr/bin/docker-init --version\n27.094  docker-init      468772 1599     0 /usr/bin/docker-init --version\n27.095  docker           468773 468326   0 /usr/bin/docker info -f {{.SecurityOptions}}\n27.096  rustc            468774 468415   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n27.097  docker           468779 468507   0 /usr/bin/docker info -f {{.SecurityOptions}}\n27.101  rustc            468774 468415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n27.108  runc             468803 1599     0 /usr/bin/runc --version\n27.109  runc             468804 1599     0 /usr/bin/runc --version\n27.111  docker-init      468818 1599     0 /usr/bin/docker-init --version\n27.112  docker-init      468819 1599     0 /usr/bin/docker-init --version\n27.115  docker           468820 468415   0 /usr/bin/docker --help\n27.117  rustup           468826 468367   0 /home/xmoe/.cargo/bin/rustup toolchain list\n27.123  rustup           468835 468367   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n27.126  rustc            468843 468466   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n27.129  docker           468849 468415   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n27.132  rustc            468843 468466   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n27.135  rustup           468863 468326   0 /home/xmoe/.cargo/bin/rustup toolchain list\n27.136  rustup           468864 468507   0 /home/xmoe/.cargo/bin/rustup toolchain list\n27.141  rustup           468887 468326   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n27.141  rustup           468888 468507   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n27.142  runc             468889 1599     0 /usr/bin/runc --version\n27.145  docker           468911 468466   0 /usr/bin/docker --help\n27.145  docker-init      468912 1599     0 /usr/bin/docker-init --version\n27.146  docker           468913 468415   0 /usr/bin/docker info -f {{.SecurityOptions}}\n27.154  rustup           468929 468367   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n27.157  docker           468945 468466   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n27.160  runc             468951 1599     0 /usr/bin/runc --version\n27.163  docker-init      468957 1599     0 /usr/bin/docker-init --version\n27.169  rustup           468963 468507   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n27.169  rustup           468964 468326   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n27.171  runc             468965 1599     0 /usr/bin/runc --version\n27.174  docker-init      468987 1599     0 /usr/bin/docker-init --version\n27.175  docker           468988 468466   0 /usr/bin/docker info -f {{.SecurityOptions}}\n27.183  uname            468994 468367   0 /usr/bin/uname -r\n27.188  runc             469000 1599     0 /usr/bin/runc --version\n27.189  rustup           469001 468415   0 /home/xmoe/.cargo/bin/rustup toolchain list\n27.192  docker-init      469007 1599     0 /usr/bin/docker-init --version\n27.196  rustup           469016 468415   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n27.197  uname            469017 468326   0 /usr/bin/uname -r\n27.198  uname            469018 468507   0 /usr/bin/uname -r\n27.204  docker           469027 468367   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n27.214  rustup           469036 468466   0 /home/xmoe/.cargo/bin/rustup toolchain list\n27.215  docker           469037 468507   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n27.218  docker           469051 468326   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n27.221  rustup           469061 468466   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n27.222  rustup           469062 468415   0 \n27.246  uname            469090 468415   0 /usr/bin/uname -r\n27.247  rustup           469091 468466   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n27.249  systemd-sysctl   469092 468624   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth426010c --prefix=/net/ipv4/neigh/veth426010c --prefix=/net/ipv6/conf/veth426010c --prefix=/net/ipv6/neigh/veth426010c\n27.249  systemd-sysctl   469093 468579   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth678d0c0 --prefix=/net/ipv4/neigh/veth678d0c0 --prefix=/net/ipv6/conf/veth678d0c0 --prefix=/net/ipv6/neigh/veth678d0c0\n27.266  docker           469129 468415   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n27.272  systemd-sysctl   469140 469139   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth944d10a --prefix=/net/ipv4/neigh/veth944d10a --prefix=/net/ipv6/conf/veth944d10a --prefix=/net/ipv6/neigh/veth944d10a\n27.273  containerd-shim  469141 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a9c1e2 start\n27.277  containerd-shim  469150 469141   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a9c1e2 -address /var/run/docker/containerd/containerd.sock\n27.279  systemd-sysctl   469156 469124   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth79b31cf --prefix=/net/ipv4/neigh/veth79b31cf --prefix=/net/ipv6/conf/veth79b31cf --prefix=/net/ipv6/neigh/veth79b31cf\n27.279  uname            469157 468466   0 /usr/bin/uname -r\n27.283  runc             469162 469150   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a 6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a9c1e2\n27.289  exe              469170 469162   0 /proc/self/exe init\n27.299  docker           469172 468466   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n27.319  exe              469194 469162   0 /proc/1599/exe -exec-root=/var/run/docker 6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a9c1e2 d7da31e8f8e1\n27.321  systemd-sysctl   469195 469130   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth669b94c --prefix=/net/ipv4/neigh/veth669b94c --prefix=/net/ipv6/conf/veth669b94c --prefix=/net/ipv6/neigh/veth669b94c\n27.322  systemd-sysctl   469201 469115   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethbf12c7b --prefix=/net/ipv4/neigh/vethbf12c7b --prefix=/net/ipv6/conf/vethbf12c7b --prefix=/net/ipv6/neigh/vethbf12c7b\n27.327  systemd-sysctl   469202 469131   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth55737ad --prefix=/net/ipv4/neigh/veth55737ad --prefix=/net/ipv6/conf/veth55737ad --prefix=/net/ipv6/neigh/veth55737ad\n27.329  systemd-sysctl   469204 469102   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3a82b94 --prefix=/net/ipv4/neigh/veth3a82b94 --prefix=/net/ipv6/conf/veth3a82b94 --prefix=/net/ipv6/neigh/veth3a82b94\n27.335  containerd-shim  469206 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba26ba4 start\n27.342  containerd-shim  469213 469206   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba26ba4 -address /var/run/docker/containerd/containerd.sock\n27.346  runc             469224 469213   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba26ba4\n27.351  exe              469232 469224   0 /proc/self/exe init\n27.352  exe              469234 1599     0 /proc/self/exe /var/run/docker/netns/3c1d4ba953c1 all false\n27.383  exe              469256 469224   0 /proc/1599/exe -exec-root=/var/run/docker e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba26ba4 d7da31e8f8e1\n27.392  systemd-sysctl   469265 469115   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth60773cd --prefix=/net/ipv4/neigh/veth60773cd --prefix=/net/ipv6/conf/veth60773cd --prefix=/net/ipv6/neigh/veth60773cd\n27.394  systemd-sysctl   469266 469130   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2475756 --prefix=/net/ipv4/neigh/veth2475756 --prefix=/net/ipv6/conf/veth2475756 --prefix=/net/ipv6/neigh/veth2475756\n27.396  runc             469268 469150   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a --log-format json --systemd-cgroup start 6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a9c1e2\n27.402  sh               469179 469150   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n27.404  cargo            469275 469179   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n27.406  exe              469276 1599     0 /proc/self/exe /var/run/docker/netns/07892d955a62 all false\n27.416  cargo-native-tr  469275 469179   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n27.419  cargo            469290 469275   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n27.430  rustc            469296 469290   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.441  rustc            469298 469290   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n27.456  runc             469302 469213   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba --log-format json --systemd-cgroup start e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba26ba4\n27.461  sh               469250 469213   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n27.463  cargo            469308 469250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n27.470  containerd-shim  469309 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e81c1e start\n27.473  containerd-shim  469316 469309   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e81c1e -address /var/run/docker/containerd/containerd.sock\n27.473  cargo-native-tr  469308 469250   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n27.476  runc             469326 469316   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e 57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e81c1e\n27.477  cargo            469325 469308   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n27.483  exe              469334 469326   0 /proc/self/exe init\n27.487  rustc            469336 469325   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.499  rustc            469338 469325   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n27.513  containerd-shim  469349 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb3844bf1 start\n27.514  exe              469350 469326   0 /proc/1599/exe -exec-root=/var/run/docker 57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e81c1e d7da31e8f8e1\n27.517  containerd-shim  469362 469349   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb3844bf1 -address /var/run/docker/containerd/containerd.sock\n27.520  runc             469371 469362   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb38 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb38 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb38 061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb3844bf1\n27.525  exe              469379 469371   0 /proc/self/exe init\n27.532  exe              469383 1599     0 /proc/self/exe /var/run/docker/netns/6cec44d0fe2b all false\n27.537  sh               469396 2147557   0 /bin/sh -c which ps\n27.538  which            469396 2147557   0 /usr/bin/which ps\n27.540  sh               469399 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n27.541  ps               469399 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n27.547  containerd-shim  469409 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef64750d8b start\n27.551  containerd-shim  469417 469409   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef64750d8b -address /var/run/docker/containerd/containerd.sock\n27.552  exe              469422 469371   0 /proc/1599/exe -exec-root=/var/run/docker 061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb3844bf1 d7da31e8f8e1\n27.554  runc             469433 469417   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef647 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef647 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef647 6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef64750d8b\n27.559  exe              469441 469433   0 /proc/self/exe init\n27.567  sh               469443 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n27.568  cpuUsage.sh      469443 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n27.569  sed              469445 469443   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n27.571  exe              469448 1599     0 /proc/self/exe /var/run/docker/netns/ba96595b5719 all false\n27.571  cat              469447 469443   0 /usr/bin/cat /proc/2240539/stat\n27.572  runc             469449 469316   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e --log-format json --systemd-cgroup start 57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e81c1e\n27.573  cat              469450 469443   0 /usr/bin/cat /proc/4193716/stat\n27.574  sleep            469459 469443   0 /usr/bin/sleep 1\n27.578  sh               469340 469316   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n27.579  cargo            469469 469340   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n27.589  cargo-native-tr  469469 469340   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n27.592  exe              469483 469433   0 /proc/1599/exe -exec-root=/var/run/docker 6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef64750d8b d7da31e8f8e1\n27.593  cargo            469482 469469   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n27.605  rustc            469491 469482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.612  exe              469493 1599     0 /proc/self/exe /var/run/docker/netns/1bf4b29d05d5 all false\n27.612  execsnoop        469494 469275   0 /usr/local/bin/execsnoop -t\n27.613  python3          469494 469275   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n27.617  runc             469505 469362   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb38 --log-format json --systemd-cgroup start 061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb3844bf1\n27.617  rustc            469504 469482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n27.623  sh               469390 469362   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n27.624  cargo            469516 469390   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n27.626  execsnoop        469517 469308   0 /usr/local/bin/execsnoop -t\n27.627  python3          469517 469308   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n27.636  cargo-native-tr  469516 469390   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n27.639  cargo            469528 469516   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n27.650  rustc            469529 469528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.661  rustc            469531 469528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n27.664  runc             469532 469417   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef647 --log-format json --systemd-cgroup start 6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef64750d8b\n27.669  sh               469457 469417   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n27.670  cargo            469541 469457   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n27.680  cargo-native-tr  469541 469457   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n27.683  cargo            469542 469541   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n27.695  rustc            469543 469542   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.706  rustc            469545 469542   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n"
}
```

#### Record 35

```json
{
  "argv": [
    "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 462480,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
  "pid": 462480,
  "ppid": 462219,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out"
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
  "build_script_root_pid": 462480,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 462483,
  "ppid": 462480,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 37

```json
{
  "argv": [
    "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
  "pid": 463549,
  "ppid": 462219,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 38

```json
{
  "argv": [
    "/tmp/native-trace-460526-1783994514766/shims/git",
    "submodule",
    "update",
    "--init"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/tmp/native-trace-460526-1783994514766/shims/git",
  "pid": 463550,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 39

```json
{
  "argv": [
    "/usr/bin/git",
    "submodule",
    "update",
    "--init"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/bin/git",
  "pid": 463564,
  "ppid": 463550,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 40

```json
{
  "argv": [
    "/usr/lib/git-core/git-submodule",
    "update",
    "--init"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git-submodule",
  "event": "process_exec",
  "image": "/usr/lib/git-core/git-submodule",
  "pid": 463565,
  "ppid": 463564,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 41

```json
{
  "argv": [
    "/usr/lib/git-core/git",
    "--exec-path"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/lib/git-core/git",
  "pid": 463573,
  "ppid": 463565,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 42

```json
{
  "argv": [
    "/usr/bin/uname",
    "-s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "uname",
  "event": "process_exec",
  "image": "/usr/bin/uname",
  "pid": 463655,
  "ppid": 463565,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 43

```json
{
  "argv": [
    "/usr/lib/git-core/git",
    "rev-parse",
    "--git-dir"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "git",
  "event": "process_exec",
  "image": "/usr/lib/git-core/git",
  "pid": 463657,
  "ppid": 463565,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out"
}
```

#### Record 44

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-E",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/10675898257093557552detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 463663,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 45

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/10675898257093557552detect_compiler_family.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 463664,
  "ppid": 463663,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 46

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "aarch64-linux-g",
  "pid": 463667,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 47

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 463666,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 48

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/common/dictionary.c",
    "-quiet",
    "-dumpbase",
    "dictionary.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 463669,
  "ppid": 463667,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 49

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
    "/tmp/ccjyOnbv.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 463750,
  "ppid": 463667,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 50

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
    "-c",
    "brotli/dec/bit_reader.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 463754,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 51

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/dec/bit_reader.c",
    "-quiet",
    "-dumpbase",
    "bit_reader.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 463756,
  "ppid": 463754,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 52

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
    "/tmp/cced3CE8.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 463819,
  "ppid": 463754,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 53

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
    "-c",
    "brotli/dec/decode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 463847,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 54

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/dec/decode.c",
    "-quiet",
    "-dumpbase",
    "decode.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 463856,
  "ppid": 463847,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 55

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
    "/tmp/ccK9Ux98.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 464220,
  "ppid": 463847,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 56

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
    "-c",
    "brotli/dec/huffman.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 464311,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 57

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "cc1",
  "pid": 464316,
  "ppid": 464311,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 58

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
    "/tmp/ccqAteEd.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 464344,
  "ppid": 464311,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 59

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
    "-c",
    "brotli/dec/state.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 464407,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 60

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/dec/state.c",
    "-quiet",
    "-dumpbase",
    "state.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 464410,
  "ppid": 464407,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 61

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
    "/tmp/ccYWBmAt.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 464477,
  "ppid": 464407,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 62

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
    "-c",
    "brotli/enc/backward_references.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 464496,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 63

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/backward_references.c",
    "-quiet",
    "-dumpbase",
    "backward_references.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 464500,
  "ppid": 464496,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 64

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
    "/tmp/ccLHb9nd.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 464973,
  "ppid": 464496,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 65

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "aarch64-linux-g",
  "pid": 465117,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 66

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/backward_references_hq.c",
    "-quiet",
    "-dumpbase",
    "backward_references_hq.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 465120,
  "ppid": 465117,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 67

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
    "/tmp/cc0J87zb.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 465230,
  "ppid": 465117,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 68

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
    "-c",
    "brotli/enc/bit_cost.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 465266,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 69

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/bit_cost.c",
    "-quiet",
    "-dumpbase",
    "bit_cost.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 465268,
  "ppid": 465266,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 70

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
    "/tmp/cc6GUPEq.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 465300,
  "ppid": 465266,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 71

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
    "-c",
    "brotli/enc/block_splitter.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 465305,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 72

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/block_splitter.c",
    "-quiet",
    "-dumpbase",
    "block_splitter.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 465306,
  "ppid": 465305,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 73

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
    "/tmp/ccbAYZQn.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 465337,
  "ppid": 465305,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 74

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-c",
    "brotli/enc/brotli_bit_stream.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 465348,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 75

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/brotli_bit_stream.c",
    "-quiet",
    "-dumpbase",
    "brotli_bit_stream.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 465349,
  "ppid": 465348,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 76

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/tmp/cccjBiJD.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 465511,
  "ppid": 465348,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 77

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
    "-c",
    "brotli/enc/cluster.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 465573,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 78

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/cluster.c",
    "-quiet",
    "-dumpbase",
    "cluster.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 465576,
  "ppid": 465573,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 79

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
    "/tmp/ccDMVWvF.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 465644,
  "ppid": 465573,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 80

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
    "-c",
    "brotli/enc/compress_fragment.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 465649,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 81

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/compress_fragment.c",
    "-quiet",
    "-dumpbase",
    "compress_fragment.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 465652,
  "ppid": 465649,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 82

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
    "/tmp/ccRUTsAn.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 465850,
  "ppid": 465649,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 83

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-c",
    "brotli/enc/compress_fragment_two_pass.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 465908,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 84

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/compress_fragment_two_pass.c",
    "-quiet",
    "-dumpbase",
    "compress_fragment_two_pass.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 465909,
  "ppid": 465908,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 85

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/tmp/ccqCAVEX.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 465994,
  "ppid": 465908,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 86

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "aarch64-linux-g",
  "pid": 466017,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 87

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/dictionary_hash.c",
    "-quiet",
    "-dumpbase",
    "dictionary_hash.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 466020,
  "ppid": 466017,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 88

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
    "/tmp/ccJlg9Ge.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 466038,
  "ppid": 466017,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 89

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
    "-c",
    "brotli/enc/encode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 466044,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 90

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/encode.c",
    "-quiet",
    "-dumpbase",
    "encode.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 466045,
  "ppid": 466044,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 91

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
    "/tmp/ccrY057e.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 466156,
  "ppid": 466044,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 92

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
    "-c",
    "brotli/enc/entropy_encode.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 466180,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 93

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/entropy_encode.c",
    "-quiet",
    "-dumpbase",
    "entropy_encode.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 466181,
  "ppid": 466180,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 94

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
    "/tmp/ccQKxcaz.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 466200,
  "ppid": 466180,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 95

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
    "-c",
    "brotli/enc/histogram.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 466209,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 96

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/histogram.c",
    "-quiet",
    "-dumpbase",
    "histogram.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 466212,
  "ppid": 466209,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 97

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
    "/tmp/ccwl32JJ.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 466232,
  "ppid": 466209,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 98

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-literal_cost.o",
    "-c",
    "brotli/enc/literal_cost.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 466248,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 99

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/literal_cost.c",
    "-quiet",
    "-dumpbase",
    "literal_cost.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-literal_cost.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 466256,
  "ppid": 466248,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 100

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-literal_cost.o",
    "/tmp/ccgYzTWI.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 466271,
  "ppid": 466248,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 101

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-memory.o",
    "-c",
    "brotli/enc/memory.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 466293,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 102

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/memory.c",
    "-quiet",
    "-dumpbase",
    "memory.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-memory.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 466298,
  "ppid": 466293,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 103

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-memory.o",
    "/tmp/ccpeCHy3.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 466326,
  "ppid": 466293,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 104

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-metablock.o",
    "-c",
    "brotli/enc/metablock.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 466330,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 105

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/metablock.c",
    "-quiet",
    "-dumpbase",
    "metablock.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-metablock.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 466332,
  "ppid": 466330,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 106

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-metablock.o",
    "/tmp/ccB9WWhU.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 466374,
  "ppid": 466330,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 107

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "cc1",
  "pid": 466396,
  "ppid": 466395,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 108

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-static_dict.o",
    "-c",
    "brotli/enc/static_dict.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 466395,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 109

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-static_dict.o",
    "/tmp/ccBZkBOL.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 466576,
  "ppid": 466395,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 110

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
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-utf8_util.o",
    "-c",
    "brotli/enc/utf8_util.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 466617,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 111

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/utf8_util.c",
    "-quiet",
    "-dumpbase",
    "utf8_util.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-utf8_util.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 466619,
  "ppid": 466617,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 112

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-I",
    "brotli/include",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-utf8_util.o",
    "/tmp/ccQZstPC.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 466634,
  "ppid": 466617,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 113

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/libbrotli.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 466636,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 114

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "sD",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/libbrotli.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463549,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 466684,
  "ppid": 463549,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 115

```json
{
  "crate": "brotli-sys",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "bsrun:3ae121e5967af9bc:6676e31a3a9dd614:1d04d589fda2fc13",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/build-script-build",
  "host": "x86_64-unknown-linux-gnu",
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "out_dir": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
  "success": true,
  "target": "aarch64-unknown-linux-gnu",
  "version": "0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  }
}
```

#### Record 116

```json
{
  "crate": "libc",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "bsrun:a733304fa0307800:4a171888d45fa12d:6ed0f36d8fdf2af7",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
  "success": true,
  "target": null,
  "version": "0.2.186",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  }
}
```

#### Record 117

```json
{
  "crate": "brotli-sys",
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "event_id": "bsrun:3ae121e5967af9bc:325298fb080efefc:70bcf1a2ee0afd48",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
  "success": true,
  "target": null,
  "version": "0.3.2",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  }
}
```

#### Record 118

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 462480,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 462483,
  "ppid": 462480,
  "root_cargo_pid": 462219,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 119

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/common/dictionary.c",
    "-quiet",
    "-dumpbase",
    "dictionary.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/common/dictionary.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 463669,
  "ppid": 463667,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 120

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/dec/bit_reader.c",
    "-quiet",
    "-dumpbase",
    "bit_reader.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/dec/bit_reader.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 463756,
  "ppid": 463754,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 121

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/dec/decode.c",
    "-quiet",
    "-dumpbase",
    "decode.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/dec/decode.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 463856,
  "ppid": 463847,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 122

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/dec/state.c",
    "-quiet",
    "-dumpbase",
    "state.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/dec/state.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 464410,
  "ppid": 464407,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 123

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/backward_references.c",
    "-quiet",
    "-dumpbase",
    "backward_references.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/backward_references.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 464500,
  "ppid": 464496,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 124

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/backward_references_hq.c",
    "-quiet",
    "-dumpbase",
    "backward_references_hq.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/backward_references_hq.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465120,
  "ppid": 465117,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 125

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/bit_cost.c",
    "-quiet",
    "-dumpbase",
    "bit_cost.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/bit_cost.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465268,
  "ppid": 465266,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 126

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/block_splitter.c",
    "-quiet",
    "-dumpbase",
    "block_splitter.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/block_splitter.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465306,
  "ppid": 465305,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 127

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/brotli_bit_stream.c",
    "-quiet",
    "-dumpbase",
    "brotli_bit_stream.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/brotli_bit_stream.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465349,
  "ppid": 465348,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 128

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/cluster.c",
    "-quiet",
    "-dumpbase",
    "cluster.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/cluster.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465576,
  "ppid": 465573,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 129

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/compress_fragment.c",
    "-quiet",
    "-dumpbase",
    "compress_fragment.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/compress_fragment.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465652,
  "ppid": 465649,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 130

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/compress_fragment_two_pass.c",
    "-quiet",
    "-dumpbase",
    "compress_fragment_two_pass.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/compress_fragment_two_pass.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 465909,
  "ppid": 465908,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 131

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/dictionary_hash.c",
    "-quiet",
    "-dumpbase",
    "dictionary_hash.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/dictionary_hash.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466020,
  "ppid": 466017,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 132

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/encode.c",
    "-quiet",
    "-dumpbase",
    "encode.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/encode.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466045,
  "ppid": 466044,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 133

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/entropy_encode.c",
    "-quiet",
    "-dumpbase",
    "entropy_encode.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/entropy_encode.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466181,
  "ppid": 466180,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 134

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/histogram.c",
    "-quiet",
    "-dumpbase",
    "histogram.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/histogram.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466212,
  "ppid": 466209,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 135

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/literal_cost.c",
    "-quiet",
    "-dumpbase",
    "literal_cost.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-literal_cost.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/literal_cost.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-literal_cost.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466256,
  "ppid": 466248,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 136

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/memory.c",
    "-quiet",
    "-dumpbase",
    "memory.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-memory.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/memory.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-memory.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466298,
  "ppid": 466293,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 137

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/metablock.c",
    "-quiet",
    "-dumpbase",
    "metablock.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-metablock.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/metablock.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-metablock.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466332,
  "ppid": 466330,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 138

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-quiet",
    "-I",
    "brotli/include",
    "-imultiarch",
    "aarch64-linux-gnu",
    "brotli/enc/utf8_util.c",
    "-quiet",
    "-dumpbase",
    "utf8_util.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-utf8_util.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "brotli/enc/utf8_util.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-utf8_util.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 466619,
  "ppid": 466617,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 139

```json
{
  "event": "compile",
  "tool": "/usr/bin/aarch64-linux-gnu-gcc",
  "real_tool": "/usr/bin/aarch64-linux-gnu-gcc",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
    "-c",
    "brotli/dec/huffman.c"
  ],
  "src": "brotli/dec/huffman.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "pid": 464311,
  "ppid": 463549,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 140

```json
{
  "event": "compile",
  "tool": "/usr/bin/aarch64-linux-gnu-gcc",
  "real_tool": "/usr/bin/aarch64-linux-gnu-gcc",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-I",
    "brotli/include",
    "-w",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-static_dict.o",
    "-c",
    "brotli/enc/static_dict.c"
  ],
  "src": "brotli/enc/static_dict.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-static_dict.o",
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "pid": 466395,
  "ppid": 463549,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 141

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/libbrotli.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
    "..."
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/libbrotli.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
    "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": true,
  "pid": 466636,
  "ppid": 463549,
  "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "root_cargo_pid": 462219,
  "build_script_root_pid": 463549,
  "build_script_related": true,
  "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
  "_owner": {
    "crate": "brotli-sys",
    "version": "0.3.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
    "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
  "_build_script_out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:02:28.446452+00:00",
  "crate": "brotli-sys",
  "version": "0.3.2",
  "architecture": "aarch64",
  "duration_seconds": 34.96394311496988,
  "trace_record_count": 117,
  "trace_owner_summary": {
    "owner_package_count": 5,
    "owner_packages": [
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "2.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml"
      },
      {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "manifest_path": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/Cargo.toml"
      }
    ],
    "attributed_event_count": 35,
    "unattributed_event_count": 82,
    "owners": [
      {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "event_count": 24,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 2,
          "used_input": 14,
          "link": 1,
          "exec_context": 2,
          "resolved_link": 1,
          "acquisition": 1,
          "build_script_run": 2
        }
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "event_count": 11,
        "kind_counts": {
          "exec": 1,
          "used_input": 6,
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
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "workspace_root": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
          "name": "brotli-sys",
          "version": "0.3.2",
          "manifest_path": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
          "name": "cc",
          "version": "1.2.67",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
          "name": "find-msvc-tools",
          "version": "0.1.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
        }
      ],
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "kind": "exec",
      "pid": 462442,
      "ppid": 462247,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:b4fed19ec505f12e:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
      "pid": 462442,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:c5eb16742d92300e:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
      "pid": 462442,
      "sha256": "750e5b687b769ef8e1f6a9de3b3b4cc39d771526f669d42b53a924666b856dae",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:135ba558c9da774d:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
      "pid": 462442,
      "sha256": "53140dc43536033138eb06a34e55a6a0ff33641d1e3937f2ad7a716aa3ee683a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:2a8f9787c6af6fe7:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
      "pid": 462442,
      "sha256": "d07a13370e4d6a6a6abdcfd76827ef7c0991362bd0043ae1f902898148c0a6fb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:e37cae5c272f2a12:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
      "pid": 462442,
      "sha256": "c1d04af73990d492aeddeae1678948453dcb03afe9564782fafda521716fd66f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:759cfb97b73257cf:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
      "pid": 462442,
      "sha256": "8ef6a5d57a020f215781ab0bc6a156213342dbd5f757c677fe270d0bad9c7795",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
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
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "context_path": "/tmp/native-trace-460526-1783994514766/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-460526-1783994514766/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 462442,
      "ppid": 462247,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11",
        "/target/debug/build/libc-8a22300c8f78b6db",
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
          "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcx0yG11/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-462442-1783994521136353534.map",
      "pid": 462442,
      "ppid": 462247,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-462442-1783994521136353534.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 463431,
      "ppid": 463347,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:f9598343693f9dc2:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
      "pid": 463431,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:fe69b3de69a443d0:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "066906ba68ec21b810aaa3c0517c0308a534e30fca9c3622c3d0950704428a71",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:674e5c441859ff5b:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "06f17cd715816b7411d31a79b8580c86dfcb3e9057e3a3222403e197094eb5d7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:c5f8ad7a7509399b:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "07dcc9020fb6262a403e53b1805048b8971d6a80204fc6c16b690fdb746d3469",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:b08d43b4fc18ac68:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "9d6f6f42a20e945b7350fcd9fe5e73d466e4844c7001683c097f7d872ea63a19",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:9c70f17e65921a88:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "eb4737e86588cd368203f578ae6862356cf3d741b2aa882c5e2005f583e3a12e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:f2ad538339242aae:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "454f319e4b32ffdef131dea8c5f675f0161e9a9720142b3af9a7ec932a7075bb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:8a7c13e4f82cdb1a:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "118b1d3cca9156d424875c26b30b1728b308cc10139f734231792604fe721e45",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:0aa834dfd777b434:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "ca1854b8cacbb691d5f22f581deada73bf400d9c3e5add751eb0734016dbaff1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:f0e425713f9f67a7:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "7c405faedd91a8c11780a97ff4ebd6acafbea1912796b04df58005993766446f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:0569919e222832b5:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "d5161492432dd4dd3191a599276f42a0c5a1e9f2dc0c0c687421a6d505c69c50",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:e6e0023477a70c32:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "1dad8e6f0bf8913023efe3a29f9a80671391170ca0fb57b9d712435586fb8fbf",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:b41c97349864bf0f:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "a4ede0d9fd60a4a3a93c21ea33624039eb713acb0ee4de1eeea7c08ef4ddc843",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "used:cc:f233c38d147b3728:327ce420b9f9e7cb:5484f17373dac776",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
      "pid": 463431,
      "sha256": "beef5da5a6c1990c62ffa6870030b80fca74e235a45ee672440764f3d7b85ad9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
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
      "output": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "context_path": "/tmp/native-trace-460526-1783994514766/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-460526-1783994514766/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 463431,
      "ppid": 463347,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus",
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
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
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/rustcMDoQus/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.0n7qjats2kg6cx322byqyz5lj.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2fwxha7ofxl4umlsl93oxhvmz.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.2prt6v6439a4ak1a669yvanuf.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.38kci45acko4otg8oe7z0u0ir.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.39tdgugmq4o7g3xlea26tv36n.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.59to0jztayjciompzme8csnix.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.5fcouaruei4ivy6daaxwx8v06.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.61vv5in54hnlxt3mu8s9zs6cj.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.7de8xiwtjfokt9z3oyn8ki4he.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.9qn3env0nfno4dzhpr9dtcn3p.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.d9o2g4hdqlxt42ofw0adgp3rp.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.ev3eqlx75d5kv139p1w07baz7.1vmdcc2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/brotli-sys-b6f66f13a6f3816f",
          "kind": "object",
          "path": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build_script_build-b6f66f13a6f3816f.cdc92z7dbay7d31wo38mgo3pe.1vmdcc2.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-463431-1783994523506733384.map",
      "pid": 463431,
      "ppid": 463347,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-463431-1783994523506733384.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "git",
        "submodule",
        "update",
        "--init"
      ],
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "exit_code": 128,
      "kind": "exec",
      "pid": 463550,
      "ppid": 463549,
      "success": false,
      "tool": "git",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "acquisition_kind": "git_submodule",
      "argv": [
        "git",
        "submodule",
        "update",
        "--init"
      ],
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "checkout_root": null,
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "acq-ext:git:f233c38d147b3728:e3b0c44298fc1c14",
      "exit_code": 128,
      "kind": "acquisition",
      "output": null,
      "pid": 463550,
      "success": false,
      "tool": "git",
      "url": null,
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "git",
        "submodule",
        "update",
        "--init"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "cargo_pkg_name": "brotli-sys",
      "cargo_pkg_version": "0.3.2",
      "context_path": "/tmp/native-trace-460526-1783994514766/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "exit_code": 128,
      "host": "x86_64-unknown-linux-gnu",
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-460526-1783994514766/events/00000000-cargo-metadata.json",
      "num_jobs": "16",
      "opt_level": "0",
      "out_dir": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out",
      "pid": 463550,
      "ppid": 463549,
      "profile": "debug",
      "real_tool": "/usr/bin/git",
      "root_cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "success": false,
      "target": "aarch64-unknown-linux-gnu",
      "tool": "git",
      "workspace_root": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
      "parse_error_count": 2,
      "parsed_event_count": 1556,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1558,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "tc            468006 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.760  rustc            468007 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.772  rustc            468010 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.772  rustc            468011 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.786  execsnoop        468018 468002   0 /usr/local/bin/execsnoop -t\n16.786  python3          468018 468002   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.787  execsnoop        468021 468003   0 /usr/local/bin/execsnoop -t\n16.787  python3          468021 468003   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.281  runc             468024 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2801572281 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n17.287  exe              468031 468024   0 /proc/self/exe init\n17.304  curl             468034 468024   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n17.538  sh               468040 2147557   0 /bin/sh -c which ps\n17.539  which            468040 2147557   0 /usr/bin/which ps\n17.541  sh               468041 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.543  ps               468041 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.569  sh               468042 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.571  cpuUsage.sh      468042 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.572  sed              468043 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.574  cat              468044 468042   0 /usr/bin/cat /proc/2240539/stat\n17.576  cat              468045 468042   0 /usr/bin/cat /proc/4193716/stat\n17.577  sleep            468046 468042   0 /usr/bin/sleep 1\n18.579  sed              468047 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.581  cat              468048 468042   0 /usr/bin/cat /proc/2240539/stat\n18.583  cat              468050 468042   0 /usr/bin/cat /proc/4193716/stat\n18.651  cargo            468052 468002   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n18.664  rustc            468053 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.683  rustc            468059 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n18.726  cc               468079 468059   0 /tmp/native-trace-468002-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.727  cc               468080 468079   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.730  collect2         468081 468080   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.731  ld.lld           468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n18.733  rust-lld         468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.769  build-script-bu  468100 468052   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n18.774  rustc            468102 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=01dbfa75f86e934e ...\n18.922  cargo            468109 468003   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.935  rustc            468110 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.954  rustc            468116 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n18.976  runc             468120 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup kill --all c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 9\n18.994  runc             468143 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup delete c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n18.996  cc               468142 468116   0 /tmp/native-trace-468003-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.997  cc               468149 468142   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n19.000  collect2         468150 468149   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.001  ld.lld           468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n19.003  rust-lld         468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.047  build-script-bu  468169 468109   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n19.053  rustc            468171 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=eb508d71aca425cd ...\n19.189  containerd-shim  468178 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d delete\n19.191  runc             468184 468178   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b7 --log-format json delete --force c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n19.252  systemd-sysctl   468190 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth26ae1bd --prefix=/net/ipv4/neigh/veth26ae1bd --prefix=/net/ipv6/conf/veth26ae1bd --prefix=/net/ipv6/neigh/veth26ae1bd\n19.263  runc             468191 461041   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb --log-format json --systemd-cgroup kill --all 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468 9\n19.280  runc             468197 461041   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb --log-format json --systemd-cgroup delete 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468\n19.485  containerd-shim  468203 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb delete\n19.487  runc             468209 468203   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed46 --log-format json delete --force 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468\n19.527  sh               468217 467838   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth83795da\n19.528  ethtool          468218 468217   0 /usr/sbin/ethtool -i veth83795da\n19.529  sed              468219 468217   0 /usr/bin/sed -n s/^driver: //p\n19.534  systemd-sysctl   468222 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth83795da --prefix=/net/ipv4/neigh/veth83795da --prefix=/net/ipv6/conf/veth83795da --prefix=/net/ipv6/neigh/veth83795da\n19.681  runc             468224 461102   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c --log-format json --systemd-cgroup kill --all aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358 9\n19.699  runc             468230 461102   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c --log-format json --systemd-cgroup delete aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358\n19.779  runc             468236 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process812323305 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n19.784  exe              468243 468236   0 /proc/self/exe init\n19.793  curl             468245 468236   0 /usr/bin/curl -f http://localhost:9091/healthz\n19.875  containerd-shim  468252 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c delete\n19.877  runc             468259 468252   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a35 --log-format json delete --force aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358\n19.921  systemd-sysctl   468264 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth61a52e7 --prefix=/net/ipv4/neigh/veth61a52e7 --prefix=/net/ipv6/conf/veth61a52e7 --prefix=/net/ipv6/neigh/veth61a52e7\n20.626  runc             468266 461203   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3 --log-format json --systemd-cgroup kill --all 1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3a8219 9\n20.643  runc             468272 461203   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3 --log-format json --systemd-cgroup delete 1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3a8219\n20.834  containerd-shim  468279 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3a8219 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3 delete\n20.837  runc             468285 468279   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3a821 --log-format json delete --force 1f45d624c90e47fdfdfdc14eb9681771e074bb9337eaf1d704db913fca3a8219\n20.879  systemd-sysctl   468291 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethac32133 --prefix=/net/ipv4/neigh/vethac32133 --prefix=/net/ipv6/conf/vethac32133 --prefix=/net/ipv6/neigh/vethac32133\n21.031  runc             468292 430091   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e80230344 --log-format json --systemd-cgroup kill --all 99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e8023034471195 9\n21.048  runc             468298 430091   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e80230344 --log-format json --systemd-cgroup delete 99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e8023034471195\n21.213  containerd-shim  468304 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e8023034471195 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e80230344 delete\n21.216  runc             468311 468304   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e802303447119 --log-format json delete --force 99adb35cdbbd47e38b922df165c4e6f11a04bb3382cc7095c5e8023034471195\n21.249  systemd-sysctl   468316 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha43ea2d --prefix=/net/ipv4/neigh/vetha43ea2d --prefix=/net/ipv6/conf/vetha43ea2d --prefix=/net/ipv6/neigh/vetha43ea2d\n22.537  sh               468319 2147557   0 /bin/sh -c which ps\n22.538  which            468319 2147557   0 \n22.540  sh               468320 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.541  ps               468320 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.542  git              468318 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n22.563  sh               468321 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n22.565  cpuUsage.sh      468321 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n22.566  sed              468322 468321   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n22.568  cat              468323 468321   0 /usr/bin/cat /proc/2240539/stat\n22.569  cat              468324 468321   0 /usr/bin/cat /proc/4193716/stat\n22.570  sleep            468325 468321   0 /usr/bin/sleep 1\n23.005  cross            468326 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n23.006  rustc            468328 468326   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.013  rustc            468328 468326   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.028  rustc            468341 468326   0 /home/xmoe/.cargo/bin/rustc -vV\n23.034  rustc            468341 468326   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.045  cargo            468351 468326   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n23.052  cargo            468351 468326   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n23.066  rustc            468360 468351   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.078  rustc            468362 468351   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.091  rustc            468366 468351   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n23.095  cross            468367 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n23.096  rustc            468370 468367   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.102  rustc            468370 468367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.113  rustc            468385 468367   0 /home/xmoe/.cargo/bin/rustc -vV\n23.118  rustc            468385 468367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.128  cargo            468396 468367   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n23.133  cargo            468396 468367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n23.142  rustc            468405 468396   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.151  rustc            468407 468396   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.163  rustc            468411 468396   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n23.543  cross            468415 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n23.544  rustc            468418 468415   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.550  rustc            468418 468415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.564  rustc            468431 468415   0 /home/xmoe/.cargo/bin/rustc -vV\n23.571  rustc            468431 468415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.572  sed              468440 468321   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n23.574  cat              468441 468321   0 /usr/bin/cat /proc/2240539/stat\n23.576  cat              468443 468321   0 /usr/bin/cat /proc/4193716/stat\n23.583  cargo            468446 468415   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n23.590  cargo            468446 468415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n23.603  rustc            468455 468446   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.616  rustc            468458 468446   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.631  rustc            468462 468446   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n23.643  cross            468466 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n23.644  rustc            468469 468466   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.651  rustc            468469 468466   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.665  rustc            468481 468466   0 /home/xmoe/.cargo/bin/rustc -vV\n23.671  rustc            468481 468466   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.682  cargo            468491 468466   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n23.689  cargo            468491 468466   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n23.702  rustc            468500 468491   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.714  rustc            468502 468491   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.728  rustc            468506 468491   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n23.732  cross            468507 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n23.733  rustc            468510 468507   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.738  rustc            468510 468507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.750  rustc            468525 468507   0 /home/xmoe/.cargo/bin/rustc -vV\n23.756  rustc            468525 468507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.765  cargo            468535 468507   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n23.769  cargo            468535 468507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n23.779  rustc            468544 468535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n23.789  rustc            468546 468535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n23.801  rustc            468550 468535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n24.268  runc             468554 460030   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6 --log-format json --systemd-cgroup kill --all bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6b44bb 9\n24.287  runc             468560 460030   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6 --log-format json --systemd-cgroup delete bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6b44bb\n24.444  containerd-shim  468567 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6b44bb -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6 delete\n24.447  runc             468574 468567   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6b44b --log-format json delete --force bcfda1702fc236d08f91616885ef98fb53b4c01a086fa8e328cb554d4f6b44bb\n24.492  sh               468582 468579   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth64e3490\n24.493  ethtool          468583 468582   0 /usr/sbin/ethtool -i veth64e3490\n24.493  sed              468584 468582   0 /usr/bin/sed -n s/^driver: //p\n24.500  systemd-sysctl   468587 468579   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth64e3490 --prefix=/net/ipv4/neigh/veth64e3490 --prefix=/net/ipv6/conf/veth64e3490 --prefix=/net/ipv6/neigh/veth64e3490\n24.529  rustup           468589 459404   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n25.362  runc             468599 427640   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883dda --log-format json --systemd-cgroup kill --all 68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883ddaafa5c 9\n25.378  runc             468605 427640   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883dda --log-format json --systemd-cgroup delete 68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883ddaafa5c\n25.576  containerd-shim  468611 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883ddaafa5c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883dda delete\n25.578  runc             468618 468611   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883ddaafa5 --log-format json delete --force 68f958ad0354d7d1811606ef327b3f99cae9e71eb69b4f7c530b7883ddaafa5c\n25.614  systemd-sysctl   468623 468579   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth46be2bd --prefix=/net/ipv4/neigh/veth46be2bd --prefix=/net/ipv6/conf/veth46be2bd --prefix=/net/ipv6/neigh/veth46be2bd\n26.542  rustc            468626 468351   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n26.656  rustc            468628 468446   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n26.768  rustc            468630 468491   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.029  rustc            468632 468367   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n27.034  rustc            468632 468367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n27.046  docker           468644 468367   0 /usr/bin/docker --help\n27.049  rustc            468650 468326   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n27.051  rustc            468651 468507   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n27.054  rustc            468650 468326   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n27.056  rustc            468651 468507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n27.061  docker           468673 468367   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n27.066  docker           468685 468326   0 /usr/bin/docker --help\n27.067  docker           468686 468507   0 /usr/bin/docker --help\n27.073  runc             468705 1599     0 /usr/bin/runc --version\n27.076  docker-init      468716 1599     0 /usr/bin/docker-init --version\n27.078  docker           468721 468367   0 /usr/bin/docker info -f {{.SecurityOptions}}\n27.079  docker           468722 468326   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n27.080  docker           468723 468507   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n27.089  runc             468752 1599     0 /usr/bin/runc --version\n27.090  runc             468753 1599     0 /usr/bin/runc --version\n27.091  runc             468756 1599     0 /usr/bin/runc --version\n27.093  docker-init      468770 1599     0 /usr/bin/docker-init --version\n27.093  docker-init      468771 1599     0 /usr/bin/docker-init --version\n27.094  docker-init      468772 1599     0 /usr/bin/docker-init --version\n27.095  docker           468773 468326   0 /usr/bin/docker info -f {{.SecurityOptions}}\n27.096  rustc            468774 468415   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n27.097  docker           468779 468507   0 /usr/bin/docker info -f {{.SecurityOptions}}\n27.101  rustc            468774 468415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n27.108  runc             468803 1599     0 /usr/bin/runc --version\n27.109  runc             468804 1599     0 /usr/bin/runc --version\n27.111  docker-init      468818 1599     0 /usr/bin/docker-init --version\n27.112  docker-init      468819 1599     0 /usr/bin/docker-init --version\n27.115  docker           468820 468415   0 /usr/bin/docker --help\n27.117  rustup           468826 468367   0 /home/xmoe/.cargo/bin/rustup toolchain list\n27.123  rustup           468835 468367   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n27.126  rustc            468843 468466   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n27.129  docker           468849 468415   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n27.132  rustc            468843 468466   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n27.135  rustup           468863 468326   0 /home/xmoe/.cargo/bin/rustup toolchain list\n27.136  rustup           468864 468507   0 /home/xmoe/.cargo/bin/rustup toolchain list\n27.141  rustup           468887 468326   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n27.141  rustup           468888 468507   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n27.142  runc             468889 1599     0 /usr/bin/runc --version\n27.145  docker           468911 468466   0 /usr/bin/docker --help\n27.145  docker-init      468912 1599     0 /usr/bin/docker-init --version\n27.146  docker           468913 468415   0 /usr/bin/docker info -f {{.SecurityOptions}}\n27.154  rustup           468929 468367   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n27.157  docker           468945 468466   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n27.160  runc             468951 1599     0 /usr/bin/runc --version\n27.163  docker-init      468957 1599     0 /usr/bin/docker-init --version\n27.169  rustup           468963 468507   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n27.169  rustup           468964 468326   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n27.171  runc             468965 1599     0 /usr/bin/runc --version\n27.174  docker-init      468987 1599     0 /usr/bin/docker-init --version\n27.175  docker           468988 468466   0 /usr/bin/docker info -f {{.SecurityOptions}}\n27.183  uname            468994 468367   0 /usr/bin/uname -r\n27.188  runc             469000 1599     0 /usr/bin/runc --version\n27.189  rustup           469001 468415   0 /home/xmoe/.cargo/bin/rustup toolchain list\n27.192  docker-init      469007 1599     0 /usr/bin/docker-init --version\n27.196  rustup           469016 468415   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n27.197  uname            469017 468326   0 /usr/bin/uname -r\n27.198  uname            469018 468507   0 /usr/bin/uname -r\n27.204  docker           469027 468367   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n27.214  rustup           469036 468466   0 /home/xmoe/.cargo/bin/rustup toolchain list\n27.215  docker           469037 468507   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n27.218  docker           469051 468326   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n27.221  rustup           469061 468466   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n27.222  rustup           469062 468415   0 \n27.246  uname            469090 468415   0 /usr/bin/uname -r\n27.247  rustup           469091 468466   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n27.249  systemd-sysctl   469092 468624   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth426010c --prefix=/net/ipv4/neigh/veth426010c --prefix=/net/ipv6/conf/veth426010c --prefix=/net/ipv6/neigh/veth426010c\n27.249  systemd-sysctl   469093 468579   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth678d0c0 --prefix=/net/ipv4/neigh/veth678d0c0 --prefix=/net/ipv6/conf/veth678d0c0 --prefix=/net/ipv6/neigh/veth678d0c0\n27.266  docker           469129 468415   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n27.272  systemd-sysctl   469140 469139   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth944d10a --prefix=/net/ipv4/neigh/veth944d10a --prefix=/net/ipv6/conf/veth944d10a --prefix=/net/ipv6/neigh/veth944d10a\n27.273  containerd-shim  469141 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a9c1e2 start\n27.277  containerd-shim  469150 469141   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a9c1e2 -address /var/run/docker/containerd/containerd.sock\n27.279  systemd-sysctl   469156 469124   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth79b31cf --prefix=/net/ipv4/neigh/veth79b31cf --prefix=/net/ipv6/conf/veth79b31cf --prefix=/net/ipv6/neigh/veth79b31cf\n27.279  uname            469157 468466   0 /usr/bin/uname -r\n27.283  runc             469162 469150   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a 6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a9c1e2\n27.289  exe              469170 469162   0 /proc/self/exe init\n27.299  docker           469172 468466   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n27.319  exe              469194 469162   0 /proc/1599/exe -exec-root=/var/run/docker 6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a9c1e2 d7da31e8f8e1\n27.321  systemd-sysctl   469195 469130   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth669b94c --prefix=/net/ipv4/neigh/veth669b94c --prefix=/net/ipv6/conf/veth669b94c --prefix=/net/ipv6/neigh/veth669b94c\n27.322  systemd-sysctl   469201 469115   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethbf12c7b --prefix=/net/ipv4/neigh/vethbf12c7b --prefix=/net/ipv6/conf/vethbf12c7b --prefix=/net/ipv6/neigh/vethbf12c7b\n27.327  systemd-sysctl   469202 469131   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth55737ad --prefix=/net/ipv4/neigh/veth55737ad --prefix=/net/ipv6/conf/veth55737ad --prefix=/net/ipv6/neigh/veth55737ad\n27.329  systemd-sysctl   469204 469102   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3a82b94 --prefix=/net/ipv4/neigh/veth3a82b94 --prefix=/net/ipv6/conf/veth3a82b94 --prefix=/net/ipv6/neigh/veth3a82b94\n27.335  containerd-shim  469206 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba26ba4 start\n27.342  containerd-shim  469213 469206   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba26ba4 -address /var/run/docker/containerd/containerd.sock\n27.346  runc             469224 469213   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba26ba4\n27.351  exe              469232 469224   0 /proc/self/exe init\n27.352  exe              469234 1599     0 /proc/self/exe /var/run/docker/netns/3c1d4ba953c1 all false\n27.383  exe              469256 469224   0 /proc/1599/exe -exec-root=/var/run/docker e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba26ba4 d7da31e8f8e1\n27.392  systemd-sysctl   469265 469115   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth60773cd --prefix=/net/ipv4/neigh/veth60773cd --prefix=/net/ipv6/conf/veth60773cd --prefix=/net/ipv6/neigh/veth60773cd\n27.394  systemd-sysctl   469266 469130   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2475756 --prefix=/net/ipv4/neigh/veth2475756 --prefix=/net/ipv6/conf/veth2475756 --prefix=/net/ipv6/neigh/veth2475756\n27.396  runc             469268 469150   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a --log-format json --systemd-cgroup start 6ea296954db83cfd368b0b5e82af02309ff49d2c5c0d495f3d0fba07a5a9c1e2\n27.402  sh               469179 469150   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n27.404  cargo            469275 469179   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n27.406  exe              469276 1599     0 /proc/self/exe /var/run/docker/netns/07892d955a62 all false\n27.416  cargo-native-tr  469275 469179   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n27.419  cargo            469290 469275   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n27.430  rustc            469296 469290   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.441  rustc            469298 469290   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n27.456  runc             469302 469213   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba --log-format json --systemd-cgroup start e3be263ce8d56be40be5e9e10fd87de2c6af4e795b53b47a2c6c10c06ba26ba4\n27.461  sh               469250 469213   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n27.463  cargo            469308 469250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n27.470  containerd-shim  469309 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e81c1e start\n27.473  containerd-shim  469316 469309   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e81c1e -address /var/run/docker/containerd/containerd.sock\n27.473  cargo-native-tr  469308 469250   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n27.476  runc             469326 469316   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e 57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e81c1e\n27.477  cargo            469325 469308   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n27.483  exe              469334 469326   0 /proc/self/exe init\n27.487  rustc            469336 469325   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.499  rustc            469338 469325   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n27.513  containerd-shim  469349 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb3844bf1 start\n27.514  exe              469350 469326   0 /proc/1599/exe -exec-root=/var/run/docker 57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e81c1e d7da31e8f8e1\n27.517  containerd-shim  469362 469349   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb3844bf1 -address /var/run/docker/containerd/containerd.sock\n27.520  runc             469371 469362   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb38 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb38 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb38 061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb3844bf1\n27.525  exe              469379 469371   0 /proc/self/exe init\n27.532  exe              469383 1599     0 /proc/self/exe /var/run/docker/netns/6cec44d0fe2b all false\n27.537  sh               469396 2147557   0 /bin/sh -c which ps\n27.538  which            469396 2147557   0 /usr/bin/which ps\n27.540  sh               469399 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n27.541  ps               469399 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n27.547  containerd-shim  469409 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef64750d8b start\n27.551  containerd-shim  469417 469409   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef64750d8b -address /var/run/docker/containerd/containerd.sock\n27.552  exe              469422 469371   0 /proc/1599/exe -exec-root=/var/run/docker 061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb3844bf1 d7da31e8f8e1\n27.554  runc             469433 469417   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef647 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef647 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef647 6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef64750d8b\n27.559  exe              469441 469433   0 /proc/self/exe init\n27.567  sh               469443 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n27.568  cpuUsage.sh      469443 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n27.569  sed              469445 469443   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n27.571  exe              469448 1599     0 /proc/self/exe /var/run/docker/netns/ba96595b5719 all false\n27.571  cat              469447 469443   0 /usr/bin/cat /proc/2240539/stat\n27.572  runc             469449 469316   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e --log-format json --systemd-cgroup start 57746c172349689102f822e7ecbf34146c0ebd77d8bc68cb9ac4349cc7e81c1e\n27.573  cat              469450 469443   0 /usr/bin/cat /proc/4193716/stat\n27.574  sleep            469459 469443   0 /usr/bin/sleep 1\n27.578  sh               469340 469316   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n27.579  cargo            469469 469340   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n27.589  cargo-native-tr  469469 469340   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n27.592  exe              469483 469433   0 /proc/1599/exe -exec-root=/var/run/docker 6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef64750d8b d7da31e8f8e1\n27.593  cargo            469482 469469   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n27.605  rustc            469491 469482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.612  exe              469493 1599     0 /proc/self/exe /var/run/docker/netns/1bf4b29d05d5 all false\n27.612  execsnoop        469494 469275   0 /usr/local/bin/execsnoop -t\n27.613  python3          469494 469275   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n27.617  runc             469505 469362   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb38 --log-format json --systemd-cgroup start 061bae7b2164a391cefb535dd6489c55e530ebda497e8a8647e9d48fb3844bf1\n27.617  rustc            469504 469482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n27.623  sh               469390 469362   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n27.624  cargo            469516 469390   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n27.626  execsnoop        469517 469308   0 /usr/local/bin/execsnoop -t\n27.627  python3          469517 469308   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n27.636  cargo-native-tr  469516 469390   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n27.639  cargo            469528 469516   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n27.650  rustc            469529 469528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.661  rustc            469531 469528   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n27.664  runc             469532 469417   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef647 --log-format json --systemd-cgroup start 6e18dce2795ad4ce3ebc44b5aa59918289212d342a9f150b819998ef64750d8b\n27.669  sh               469457 469417   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n27.670  cargo            469541 469457   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n27.680  cargo-native-tr  469541 469457   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n27.683  cargo            469542 469541   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n27.695  rustc            469543 469542   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n27.706  rustc            469545 469542   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 462480,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
      "pid": 462480,
      "ppid": 462219,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 462480,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 462483,
      "ppid": 462480,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
      "pid": 463549,
      "ppid": 462219,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/tmp/native-trace-460526-1783994514766/shims/git",
        "submodule",
        "update",
        "--init"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/tmp/native-trace-460526-1783994514766/shims/git",
      "pid": 463550,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/git",
        "submodule",
        "update",
        "--init"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/usr/bin/git",
      "pid": 463564,
      "ppid": 463550,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/git-core/git-submodule",
        "update",
        "--init"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git-submodule",
      "event": "process_exec",
      "image": "/usr/lib/git-core/git-submodule",
      "pid": 463565,
      "ppid": 463564,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/git-core/git",
        "--exec-path"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/usr/lib/git-core/git",
      "pid": 463573,
      "ppid": 463565,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/uname",
        "-s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "uname",
      "event": "process_exec",
      "image": "/usr/bin/uname",
      "pid": 463655,
      "ppid": 463565,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/git-core/git",
        "rev-parse",
        "--git-dir"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "git",
      "event": "process_exec",
      "image": "/usr/lib/git-core/git",
      "pid": 463657,
      "ppid": 463565,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-E",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/10675898257093557552detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 463663,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/10675898257093557552detect_compiler_family.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 463664,
      "ppid": 463663,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "aarch64-linux-g",
      "pid": 463667,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 463666,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/common/dictionary.c",
        "-quiet",
        "-dumpbase",
        "dictionary.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 463669,
      "ppid": 463667,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
        "/tmp/ccjyOnbv.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 463750,
      "ppid": 463667,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
        "-c",
        "brotli/dec/bit_reader.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 463754,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/dec/bit_reader.c",
        "-quiet",
        "-dumpbase",
        "bit_reader.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 463756,
      "ppid": 463754,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
        "/tmp/cced3CE8.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 463819,
      "ppid": 463754,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
        "-c",
        "brotli/dec/decode.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 463847,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/dec/decode.c",
        "-quiet",
        "-dumpbase",
        "decode.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 463856,
      "ppid": 463847,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
        "/tmp/ccK9Ux98.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 464220,
      "ppid": 463847,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
        "-c",
        "brotli/dec/huffman.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 464311,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "cc1",
      "pid": 464316,
      "ppid": 464311,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
        "/tmp/ccqAteEd.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 464344,
      "ppid": 464311,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
        "-c",
        "brotli/dec/state.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 464407,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/dec/state.c",
        "-quiet",
        "-dumpbase",
        "state.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 464410,
      "ppid": 464407,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
        "/tmp/ccYWBmAt.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 464477,
      "ppid": 464407,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
        "-c",
        "brotli/enc/backward_references.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 464496,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/backward_references.c",
        "-quiet",
        "-dumpbase",
        "backward_references.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 464500,
      "ppid": 464496,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
        "/tmp/ccLHb9nd.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 464973,
      "ppid": 464496,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "aarch64-linux-g",
      "pid": 465117,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/backward_references_hq.c",
        "-quiet",
        "-dumpbase",
        "backward_references_hq.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 465120,
      "ppid": 465117,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
        "/tmp/cc0J87zb.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 465230,
      "ppid": 465117,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
        "-c",
        "brotli/enc/bit_cost.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 465266,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/bit_cost.c",
        "-quiet",
        "-dumpbase",
        "bit_cost.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 465268,
      "ppid": 465266,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
        "/tmp/cc6GUPEq.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 465300,
      "ppid": 465266,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
        "-c",
        "brotli/enc/block_splitter.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 465305,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/block_splitter.c",
        "-quiet",
        "-dumpbase",
        "block_splitter.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 465306,
      "ppid": 465305,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
        "/tmp/ccbAYZQn.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 465337,
      "ppid": 465305,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
        "-c",
        "brotli/enc/brotli_bit_stream.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 465348,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/brotli_bit_stream.c",
        "-quiet",
        "-dumpbase",
        "brotli_bit_stream.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 465349,
      "ppid": 465348,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
        "/tmp/cccjBiJD.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 465511,
      "ppid": 465348,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
        "-c",
        "brotli/enc/cluster.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 465573,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/cluster.c",
        "-quiet",
        "-dumpbase",
        "cluster.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 465576,
      "ppid": 465573,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
        "/tmp/ccDMVWvF.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 465644,
      "ppid": 465573,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
        "-c",
        "brotli/enc/compress_fragment.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 465649,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/compress_fragment.c",
        "-quiet",
        "-dumpbase",
        "compress_fragment.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 465652,
      "ppid": 465649,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
        "/tmp/ccRUTsAn.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 465850,
      "ppid": 465649,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "-c",
        "brotli/enc/compress_fragment_two_pass.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 465908,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/compress_fragment_two_pass.c",
        "-quiet",
        "-dumpbase",
        "compress_fragment_two_pass.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 465909,
      "ppid": 465908,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "/tmp/ccqCAVEX.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 465994,
      "ppid": 465908,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "aarch64-linux-g",
      "pid": 466017,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/dictionary_hash.c",
        "-quiet",
        "-dumpbase",
        "dictionary_hash.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 466020,
      "ppid": 466017,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
        "/tmp/ccJlg9Ge.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 466038,
      "ppid": 466017,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
        "-c",
        "brotli/enc/encode.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 466044,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/encode.c",
        "-quiet",
        "-dumpbase",
        "encode.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 466045,
      "ppid": 466044,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
        "/tmp/ccrY057e.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 466156,
      "ppid": 466044,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
        "-c",
        "brotli/enc/entropy_encode.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 466180,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/entropy_encode.c",
        "-quiet",
        "-dumpbase",
        "entropy_encode.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 466181,
      "ppid": 466180,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
        "/tmp/ccQKxcaz.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 466200,
      "ppid": 466180,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
        "-c",
        "brotli/enc/histogram.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 466209,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/histogram.c",
        "-quiet",
        "-dumpbase",
        "histogram.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 466212,
      "ppid": 466209,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
        "/tmp/ccwl32JJ.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 466232,
      "ppid": 466209,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-literal_cost.o",
        "-c",
        "brotli/enc/literal_cost.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 466248,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/literal_cost.c",
        "-quiet",
        "-dumpbase",
        "literal_cost.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-literal_cost.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 466256,
      "ppid": 466248,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-literal_cost.o",
        "/tmp/ccgYzTWI.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 466271,
      "ppid": 466248,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-memory.o",
        "-c",
        "brotli/enc/memory.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 466293,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/memory.c",
        "-quiet",
        "-dumpbase",
        "memory.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-memory.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 466298,
      "ppid": 466293,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-memory.o",
        "/tmp/ccpeCHy3.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 466326,
      "ppid": 466293,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-metablock.o",
        "-c",
        "brotli/enc/metablock.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 466330,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/metablock.c",
        "-quiet",
        "-dumpbase",
        "metablock.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-metablock.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 466332,
      "ppid": 466330,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-metablock.o",
        "/tmp/ccB9WWhU.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 466374,
      "ppid": 466330,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "cc1",
      "pid": 466396,
      "ppid": 466395,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-static_dict.o",
        "-c",
        "brotli/enc/static_dict.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 466395,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-static_dict.o",
        "/tmp/ccBZkBOL.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 466576,
      "ppid": 466395,
      "root_cargo_pid": 462219,
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
        "-I",
        "brotli/include",
        "-w",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-utf8_util.o",
        "-c",
        "brotli/enc/utf8_util.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 466617,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-quiet",
        "-I",
        "brotli/include",
        "-imultiarch",
        "aarch64-linux-gnu",
        "brotli/enc/utf8_util.c",
        "-quiet",
        "-dumpbase",
        "utf8_util.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-utf8_util.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 466619,
      "ppid": 466617,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-I",
        "brotli/include",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-utf8_util.o",
        "/tmp/ccQZstPC.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 466634,
      "ppid": 466617,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "cqD",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/libbrotli.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/e198953d800c79d4-dictionary.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-bit_reader.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-decode.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-huffman.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/76d4580618152496-state.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-backward_references_hq.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-bit_cost.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-block_splitter.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-brotli_bit_stream.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-cluster.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-compress_fragment_two_pass.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-dictionary_hash.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-encode.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-entropy_encode.o",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/62394abbbe01bffa-histogram.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 466636,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "sD",
        "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out/libbrotli.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463549,
      "build_script_target_dir": "brotli-sys-b6f66f13a6f3816f",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 466684,
      "ppid": 463549,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "brotli-sys",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "bsrun:3ae121e5967af9bc:6676e31a3a9dd614:1d04d589fda2fc13",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/build-script-build",
      "host": "x86_64-unknown-linux-gnu",
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "out_dir": "/target/aarch64-unknown-linux-gnu/debug/build/brotli-sys-324ee26cab1a8731/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
      "success": true,
      "target": "aarch64-unknown-linux-gnu",
      "version": "0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "bsrun:a733304fa0307800:4a171888d45fa12d:6ed0f36d8fdf2af7",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "success": true,
      "target": null,
      "version": "0.2.186",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "brotli-sys",
      "cwd": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "event_id": "bsrun:3ae121e5967af9bc:325298fb080efefc:70bcf1a2ee0afd48",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
      "out_dir": "/target/debug/build/brotli-sys-b6f66f13a6f3816f/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
      "success": true,
      "target": null,
      "version": "0.3.2",
      "_owner": {
        "crate": "brotli-sys",
        "version": "0.3.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2#brotli-sys@0.3.2",
        "manifest_dir": "/tmp/crate-build-aarch64-rp055gtt/src/brotli-sys-0.3.2",
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
      "build_script_root_pid": 462480,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 462483,
      "ppid": 462480,
      "root_cargo_pid": 462219,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 1992,
    "crate": "brotli-sys",
    "version": "0.3.2",
    "crate_id": "4566",
    "version_id": "65780",
    "downloads": 7258982,
    "cumulative_downloads": 101677447474,
    "cumulative_share_of_global": 0.3801485032752649,
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
