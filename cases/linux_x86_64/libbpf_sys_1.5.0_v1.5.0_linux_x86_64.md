# `libbpf-sys` `1.5.0+v1.5.0`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/libbpf/libbpf-sys`
Crate release commit: `d18238fba300dd16ee4d302387abf1b500ad982f`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `elfutils`
- `libbpf`
- `zlib`

## Build-level coding evidence

### pkg-config / pkgconf

Working directory: `/work/libbpf/src`

```text
pkg-config --cflags libelf zlib
```

## `/work/target/debug/build/libbpf-sys-e3f36c75b44831f5/out/obj/libbpf.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/libbpf/src`

### Source file examples

* `/work/libbpf/src/bpf.c`
* `/work/libbpf/src/bpf_prog_linfo.c`
* `/work/libbpf/src/btf.c`
* `/work/libbpf/src/btf_dump.c`
* `/work/libbpf/src/btf_iter.c`

### Compilation

```text
cc -I<include directory> -I<include directory> -I<include directory> -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -D_LARGEFILE64_SOURCE -D_FILE_OFFSET_BITS=64 -Wno-unknown-warning-option -Wno-format-overflow -c <source> -o <object>
```

### Static library construction

```text
ar rcs <static library> <object files>
```
