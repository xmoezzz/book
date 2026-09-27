# `brotli-sys` `0.3.2`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/alexcrichton/brotli2-rs`
Crate release commit: `44509bd6ea07bd91ab4f1ea5e106c53be23e1b7b`
Commit evidence: release tag `0.3.2` with matching package name/version
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `brotli-sys/brotli`

## Build-level coding evidence

### Source acquisition

Working directory: `/work`

```text
git submodule update --init
```

Working directory: `/work`

```text
/usr/bin/git submodule update --init
```

## `/work/target/debug/build/brotli-sys-54a7dfacae66a30e/out/libbrotli.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/brotli/common`
* `/work/brotli/dec`
* `/work/brotli/enc`

### Source file examples

* `/work/brotli/common/dictionary.c`
* `/work/brotli/dec/bit_reader.c`
* `/work/brotli/dec/decode.c`
* `/work/brotli/dec/huffman.c`
* `/work/brotli/dec/state.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -w -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
