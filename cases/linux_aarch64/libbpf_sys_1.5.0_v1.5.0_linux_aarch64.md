# `libbpf-sys` `1.5.0+v1.5.0`

Platform: Linux aarch64

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

Working directory: `/tmp/crate-build-aarch64-lyw8ifcr/src/libbpf-sys-1.5.0+v1.5.0/libbpf/src`

```text
pkg-config --cflags libelf zlib
```

## `/target/aarch64-unknown-linux-gnu/debug/build/libbpf-sys-8f8a828db70a36aa/out/obj/libbpf.a`

### Source origin

* matches Linux x86_64 source path `/work/libbpf/src/bpf.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/btf.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/btf_iter.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/btf_relocate.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/elf.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/hashmap.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/libbpf_errno.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/libbpf_probes.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/linker.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/nlattr.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/relo_core.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/str_error.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/strset.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/usdt.c`, under crate source directory `/work`

### Source file examples

* `bpf.c`
* `btf.c`
* `btf_iter.c`
* `btf_relocate.c`
* `elf.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu -D _LARGEFILE64_SOURCE -D _FILE_OFFSET_BITS=64 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 ...
```

### Static library construction

```text
ar rcs <static library> <object files>
```
