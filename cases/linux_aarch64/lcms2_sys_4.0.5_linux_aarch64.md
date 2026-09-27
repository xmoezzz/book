# `lcms2-sys` `4.0.5`

Platform: Linux aarch64

## Submodule

Repository: `https://github.com/kornelski/rust-lcms2-sys.git`
Crate release commit: `b8e9c3efcf266b88600318fb519c073b9ebb61b7`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `vendor`

## `/target/aarch64-unknown-linux-gnu/debug/build/lcms2-sys-291f8ed5f45995e7/out/liblcms2.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5`

### Source directories

* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src`

### Source file examples

* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src/cmsalpha.c`
* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src/cmscam02.c`
* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src/cmscgats.c`
* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src/cmscnvrt.c`
* `/tmp/crate-build-aarch64-6azo69h2/src/lcms2-sys-4.0.5/vendor/src/cmserr.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
