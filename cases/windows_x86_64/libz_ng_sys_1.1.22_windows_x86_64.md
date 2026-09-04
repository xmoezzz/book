# `libz-ng-sys` `1.1.22`

Platform: Windows x86_64

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/target/debug/build/libz-ng-sys-49b708f297538d88/out/build/zlibstatic-ngd.lib`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22`
* under build output directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/target/debug/build/libz-ng-sys-49b708f297538d88/out`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/src/zlib-ng`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/src/zlib-ng/arch/generic`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/src/zlib-ng/arch/x86`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/target/debug/build/libz-ng-sys-49b708f297538d88/out/build`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/src/zlib-ng/adler32.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/src/zlib-ng/arch/generic/adler32_c.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/src/zlib-ng/arch/generic/adler32_fold_c.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/src/zlib-ng/arch/generic/chunkset_c.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-w9f2kzpt/src/libz-ng-sys-1.1.22/src/zlib-ng/arch/generic/compare256_c.c`

### Compilation

```text
cl /nologo -DHAVE_BUILTIN_ASSUME_ALIGNED -DNO_FSEEKO -DWITH_GZFILEOP -DX86_AVX2 -DX86_AVX512 -DX86_AVX512VNNI -DX86_FEATURES -DX86_HAVE_XSAVE_INTRIN -DX86_PCLMULQDQ_CRC -DX86_SSE2 -DX86_SSE42 -DX86_SSSE3 -DX86_VPCLMULQDQ_CRC -DZLIBNG_NATIVE_API -D_CRT_NONSTDC_NO_DEPRECATE -D_CRT_SECURE_NO_DEPRECATE -I<include directory> -I<include directory> -nologo -MD -Brepro /utf-8 /Ob0 /Od /RTC1 -std:c11 -MDd -Zi /W3 /w34242 /WX /wd4206 /wd4054 /wd4324 -DZLIB_DEBUG /showIncludes /Fo<object> /Fd<auxiliary file> /FS -c <source>
```

```text
cl /nologo -DHAVE_BUILTIN_ASSUME_ALIGNED -DNO_FSEEKO -DWITH_GZFILEOP -DX86_AVX2 -DX86_AVX512 -DX86_AVX512VNNI -DX86_FEATURES -DX86_HAVE_XSAVE_INTRIN -DX86_PCLMULQDQ_CRC -DX86_SSE2 -DX86_SSE42 -DX86_SSSE3 -DX86_VPCLMULQDQ_CRC -DZLIBNG_NATIVE_API -D_CRT_NONSTDC_NO_DEPRECATE -D_CRT_SECURE_NO_DEPRECATE -I<include directory> -I<include directory> -nologo -MD -Brepro /utf-8 /Ob0 /Od /RTC1 -std:c11 -MDd -Zi /W3 /w34242 /WX /wd4206 /wd4054 /wd4324 -DZLIB_DEBUG /arch:AVX512 /showIncludes /Fo<object> /Fd<auxiliary file> /FS -c <source>
```

```text
cl /nologo -DHAVE_BUILTIN_ASSUME_ALIGNED -DNO_FSEEKO -DWITH_GZFILEOP -DX86_AVX2 -DX86_AVX512 -DX86_AVX512VNNI -DX86_FEATURES -DX86_HAVE_XSAVE_INTRIN -DX86_PCLMULQDQ_CRC -DX86_SSE2 -DX86_SSE42 -DX86_SSSE3 -DX86_VPCLMULQDQ_CRC -DZLIBNG_NATIVE_API -D_CRT_NONSTDC_NO_DEPRECATE -D_CRT_SECURE_NO_DEPRECATE -I<include directory> -I<include directory> -nologo -MD -Brepro /utf-8 /Ob0 /Od /RTC1 -std:c11 -MDd -Zi /W3 /w34242 /WX /wd4206 /wd4054 /wd4324 -DZLIB_DEBUG /arch:AVX2 /showIncludes /Fo<object> /Fd<auxiliary file> /FS -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
