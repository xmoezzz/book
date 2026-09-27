# `snmalloc-sys` `0.3.5`

Platform: Windows x86_64

## Submodule

Repository: `https://github.com/SchrodingerZhu/snmalloc-rs`
Crate release commit: `609bcb01f9ec592a11aa3010bea4fcf1ce815dd7`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `snmalloc-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `snmalloc-sys/snmalloc`

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-6mcqfb22/src/snmalloc-sys-0.3.5/target/debug/build/snmalloc-sys-53837b178283d37d/out/build/snmallocshim-rust.lib`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-6mcqfb22/src/snmalloc-sys-0.3.5`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-6mcqfb22/src/snmalloc-sys-0.3.5/snmalloc/src/snmalloc/override`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-6mcqfb22/src/snmalloc-sys-0.3.5/snmalloc/src/snmalloc/override/rust.cc`

### Compilation

```text
cl /TP -DMALLOC_USABLE_SIZE_QUALIFIER=const -DSNMALLOC_CHECK_LOADS=false -DSNMALLOC_NO_REALLOCARR -DSNMALLOC_NO_REALLOCARRAY -DSNMALLOC_PAGEID=false -DSNMALLOC_USE_CXX11_DESTRUCTORS -D_HAS_EXCEPTIONS=0 -I<include directory> -nologo -MD -Brepro -W0 /O2 /Ob2 /DNDEBUG /EHsc -std:c++20 /Zi /W4 /WX /wd4127 /wd4324 /wd4201 /showIncludes /Fo<object> /Fd<auxiliary file> /FS -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
