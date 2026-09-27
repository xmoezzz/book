# `snmalloc-sys` `0.3.5`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/SchrodingerZhu/snmalloc-rs`
Crate release commit: `609bcb01f9ec592a11aa3010bea4fcf1ce815dd7`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `snmalloc-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `snmalloc-sys/snmalloc`

## `/work/target/debug/build/snmalloc-sys-48be0585e1d46fef/out/build/libsnmallocshim-rust.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/snmalloc/src/snmalloc/override`

### Source file examples

* `/work/snmalloc/src/snmalloc/override/rust.cc`

### Compilation

```text
c++ -DMALLOC_USABLE_SIZE_QUALIFIER=const -DSNMALLOC_CHECK_LOADS=false -DSNMALLOC_EXPORT=__attribute__((visibility("default"))) -DSNMALLOC_HAS_LINUX_RANDOM_H -DSNMALLOC_NO_REALLOCARR -DSNMALLOC_NO_REALLOCARRAY -DSNMALLOC_PAGEID=false -DSNMALLOC_PLATFORM_HAS_GETENTROPY -DSNMALLOC_USE_PTHREAD_DESTRUCTORS -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -w -O3 -DNDEBUG -fvisibility=hidden -fno-exceptions -fno-rtti -Wall -Wextra -Werror -Wundef -fomit-frame-pointer -ffunction-sections -mprfchw -ftls-model=initial-exec -mcx16 -std=gnu++20 -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

### Static library construction

```text
ar qc <static library> <object files>
```
