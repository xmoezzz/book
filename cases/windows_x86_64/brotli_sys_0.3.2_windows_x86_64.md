# `brotli-sys` `0.3.2`

Platform: Windows x86_64

## Submodule

Repository: `https://github.com/alexcrichton/brotli2-rs`
Crate release commit: `44509bd6ea07bd91ab4f1ea5e106c53be23e1b7b`
Commit evidence: release tag `0.3.2` with matching package name/version
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `brotli-sys/brotli`

## Build-level coding evidence

### Source acquisition

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2`

```text
git submodule update --init
```

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/target/debug/build/brotli-sys-2611b5847f11cbf2/out/libbrotli.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/common`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/dec`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/enc`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/common/dictionary.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/dec/bit_reader.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/dec/decode.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/dec/huffman.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-udgj5k51/src/brotli-sys-0.3.2/brotli/dec/state.c`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -W0 <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
