# `libmimalloc-sys` `0.1.44`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/purpleprotocol/mimalloc_rust`
Crate release commit: `a5a76fd2c5a3a7c7b24d4765d53c71e41b32df74`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `libmimalloc-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `libmimalloc-sys/c_src/mimalloc/v2`
- `libmimalloc-sys/c_src/mimalloc/v3`

## `/work/target/debug/build/libmimalloc-sys-7a37162def3796f8/out/libmimalloc.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/c_src/mimalloc/v2/src`

### Source file examples

* `/work/c_src/mimalloc/v2/src/static.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -Wall -Wextra -Wno-error=date-time -DMI_DEBUG=0 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
