# `liblzma-sys` `0.4.4`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/portable-network-archive/liblzma-rs`
Crate release commit: `357d78880433dc634878777e645e026145d56197`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `liblzma-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `liblzma-sys/xz`

## `/work/target/debug/build/liblzma-sys-989e8346251acdd2/out/liblzma.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/xz/src`

### Source file examples

* `/work/xz/src/common/tuklib_cpucores.c`
* `/work/xz/src/common/tuklib_physmem.c`
* `/work/xz/src/liblzma/check/check.c`
* `/work/xz/src/liblzma/check/crc32_fast.c`
* `/work/xz/src/liblzma/check/crc64_fast.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -Wall -Wextra -std=c99 -DHAVE_CONFIG_H=1 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
