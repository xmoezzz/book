# `c-kzg` `1.0.3`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/ethereum/c-kzg-4844`
Crate release commit: `75d569b16cb2e17a33484af0f03ec633cba3b582`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `blst`

## `/work/target/debug/build/c-kzg-f4992513e4ea16ac/out/libckzg.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/c_kzg_4844.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -w -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
