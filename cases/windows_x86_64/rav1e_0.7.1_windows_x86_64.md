# `rav1e` `0.7.1`

Platform: Windows x86_64

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-77s3v_7g/src/rav1e-0.7.1/target/debug/build/rav1e-961331760573a12d/out/librav1easm.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-77s3v_7g/src/rav1e-0.7.1`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-77s3v_7g/src/rav1e-0.7.1/src/x86`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-77s3v_7g/src/rav1e-0.7.1/src/x86/cdef16_avx2.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-77s3v_7g/src/rav1e-0.7.1/src/x86/cdef16_avx512.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-77s3v_7g/src/rav1e-0.7.1/src/x86/cdef16_sse.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-77s3v_7g/src/rav1e-0.7.1/src/x86/cdef_avx2.asm`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-77s3v_7g/src/rav1e-0.7.1/src/x86/cdef_avx512.asm`

### Compilation

```text
nasm -fwin64 -g -I<include directory> -I<include directory> <source> -o <object>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
