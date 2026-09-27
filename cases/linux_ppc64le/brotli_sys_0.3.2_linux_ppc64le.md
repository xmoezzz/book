# `brotli-sys` `0.3.2`

Platform: Linux ppc64le

## Submodule

Repository: `https://github.com/alexcrichton/brotli2-rs`
Crate release commit: `44509bd6ea07bd91ab4f1ea5e106c53be23e1b7b`
Commit evidence: release tag `0.3.2` with matching package name/version
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `brotli-sys/brotli`

## Build-level coding evidence

### Source acquisition

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
git submodule update --init
```

Working directory: `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

```text
/usr/bin/git submodule update --init
```

## `/target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2`

### Source directories

* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/common`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/enc`

### Source file examples

* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/common/dictionary.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/bit_reader.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/decode.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/huffman.c`
* `/tmp/crate-build-ppc64le-ey9cdojy/src/brotli-sys-0.3.2/brotli/dec/state.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -w -ffunction-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
