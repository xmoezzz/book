# `libmimalloc-sys` `0.1.44`

Platform: Linux ppc64le

## Submodule

Repository: `https://github.com/purpleprotocol/mimalloc_rust`
Crate release commit: `a5a76fd2c5a3a7c7b24d4765d53c71e41b32df74`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `libmimalloc-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `libmimalloc-sys/c_src/mimalloc/v2`
- `libmimalloc-sys/c_src/mimalloc/v3`

## `/target/powerpc64le-unknown-linux-gnu/debug/build/libmimalloc-sys-8ca74cb6f5a037b9/out/libmimalloc.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-_qjqxzyy/src/libmimalloc-sys-0.1.44`

### Source directories

* `/tmp/crate-build-ppc64le-_qjqxzyy/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src`

### Source file examples

* `/tmp/crate-build-ppc64le-_qjqxzyy/src/libmimalloc-sys-0.1.44/c_src/mimalloc/v2/src/static.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch powerpc64le-linux-gnu -D MI_DEBUG=0 <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -gdwarf-4 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
