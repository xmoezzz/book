# `libz-ng-sys` `1.1.22`

Platform: Linux x86_64

## `/work/target/debug/build/libz-ng-sys-541195f19191bc21/out/build/libz-ng.a`

### Source origin

* under crate source directory `/work`
* under build output directory `/work/target/debug/build/libz-ng-sys-541195f19191bc21/out`

### Source directories

* `/work/src/zlib-ng`
* `/work/src/zlib-ng/arch/generic`
* `/work/src/zlib-ng/arch/x86`
* `/work/target/debug/build/libz-ng-sys-541195f19191bc21/out/build`

### Source file examples

* `/work/src/zlib-ng/adler32.c`
* `/work/src/zlib-ng/arch/generic/adler32_c.c`
* `/work/src/zlib-ng/arch/generic/adler32_fold_c.c`
* `/work/src/zlib-ng/arch/generic/chunkset_c.c`
* `/work/src/zlib-ng/arch/generic/compare256_c.c`

### Compilation

```text
cc -DHAVE_ALIGNED_ALLOC -DHAVE_ATTRIBUTE_ALIGNED -DHAVE_BUILTIN_ASSUME_ALIGNED -DHAVE_BUILTIN_CTZ -DHAVE_BUILTIN_CTZLL -DHAVE_LINUX_AUXVEC_H -DHAVE_POSIX_MEMALIGN -DHAVE_SYS_AUXV_H -DHAVE_VISIBILITY_HIDDEN -DHAVE_VISIBILITY_INTERNAL -DWITH_GZFILEOP -DX86_AVX2 -DX86_AVX512 -DX86_AVX512VNNI -DX86_FEATURES -DX86_HAVE_XSAVE_INTRIN -DX86_PCLMULQDQ_CRC -DX86_SSE2 -DX86_SSE42 -DX86_SSSE3 -DX86_VPCLMULQDQ_CRC -DZLIBNG_NATIVE_API -D_LARGEFILE64_SOURCE=1 -D__USE_LARGEFILE64 -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -g -Wall -DZLIB_DEBUG -std=c11 -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

```text
cc -DHAVE_ALIGNED_ALLOC -DHAVE_ATTRIBUTE_ALIGNED -DHAVE_BUILTIN_ASSUME_ALIGNED -DHAVE_BUILTIN_CTZ -DHAVE_BUILTIN_CTZLL -DHAVE_LINUX_AUXVEC_H -DHAVE_POSIX_MEMALIGN -DHAVE_SYS_AUXV_H -DHAVE_VISIBILITY_HIDDEN -DHAVE_VISIBILITY_INTERNAL -DWITH_GZFILEOP -DX86_AVX2 -DX86_AVX512 -DX86_AVX512VNNI -DX86_FEATURES -DX86_HAVE_XSAVE_INTRIN -DX86_PCLMULQDQ_CRC -DX86_SSE2 -DX86_SSE42 -DX86_SSSE3 -DX86_VPCLMULQDQ_CRC -DZLIBNG_NATIVE_API -D_LARGEFILE64_SOURCE=1 -D__USE_LARGEFILE64 -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -g -Wall -DZLIB_DEBUG -std=c11 -mavx2 -mbmi2 -fno-lto -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

```text
cc -DHAVE_ALIGNED_ALLOC -DHAVE_ATTRIBUTE_ALIGNED -DHAVE_BUILTIN_ASSUME_ALIGNED -DHAVE_BUILTIN_CTZ -DHAVE_BUILTIN_CTZLL -DHAVE_LINUX_AUXVEC_H -DHAVE_POSIX_MEMALIGN -DHAVE_SYS_AUXV_H -DHAVE_VISIBILITY_HIDDEN -DHAVE_VISIBILITY_INTERNAL -DWITH_GZFILEOP -DX86_AVX2 -DX86_AVX512 -DX86_AVX512VNNI -DX86_FEATURES -DX86_HAVE_XSAVE_INTRIN -DX86_PCLMULQDQ_CRC -DX86_SSE2 -DX86_SSE42 -DX86_SSSE3 -DX86_VPCLMULQDQ_CRC -DZLIBNG_NATIVE_API -D_LARGEFILE64_SOURCE=1 -D__USE_LARGEFILE64 -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -g -Wall -DZLIB_DEBUG -std=c11 -mssse3 -fno-lto -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

```text
cc -DHAVE_ALIGNED_ALLOC -DHAVE_ATTRIBUTE_ALIGNED -DHAVE_BUILTIN_ASSUME_ALIGNED -DHAVE_BUILTIN_CTZ -DHAVE_BUILTIN_CTZLL -DHAVE_LINUX_AUXVEC_H -DHAVE_POSIX_MEMALIGN -DHAVE_SYS_AUXV_H -DHAVE_VISIBILITY_HIDDEN -DHAVE_VISIBILITY_INTERNAL -DWITH_GZFILEOP -DX86_AVX2 -DX86_AVX512 -DX86_AVX512VNNI -DX86_FEATURES -DX86_HAVE_XSAVE_INTRIN -DX86_PCLMULQDQ_CRC -DX86_SSE2 -DX86_SSE42 -DX86_SSSE3 -DX86_VPCLMULQDQ_CRC -DZLIBNG_NATIVE_API -D_LARGEFILE64_SOURCE=1 -D__USE_LARGEFILE64 -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -g -Wall -DZLIB_DEBUG -std=c11 -mpclmul -mvpclmulqdq -mavx512f -mavx512f -mavx512dq -mavx512bw -mavx512vl -mbmi2 -mtune=cascadelake -fno-lto -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

```text
cc -DHAVE_ALIGNED_ALLOC -DHAVE_ATTRIBUTE_ALIGNED -DHAVE_BUILTIN_ASSUME_ALIGNED -DHAVE_BUILTIN_CTZ -DHAVE_BUILTIN_CTZLL -DHAVE_LINUX_AUXVEC_H -DHAVE_POSIX_MEMALIGN -DHAVE_SYS_AUXV_H -DHAVE_VISIBILITY_HIDDEN -DHAVE_VISIBILITY_INTERNAL -DWITH_GZFILEOP -DX86_AVX2 -DX86_AVX512 -DX86_AVX512VNNI -DX86_FEATURES -DX86_HAVE_XSAVE_INTRIN -DX86_PCLMULQDQ_CRC -DX86_SSE2 -DX86_SSE42 -DX86_SSSE3 -DX86_VPCLMULQDQ_CRC -DZLIBNG_NATIVE_API -D_LARGEFILE64_SOURCE=1 -D__USE_LARGEFILE64 -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -g -Wall -DZLIB_DEBUG -std=c11 -mavx512f -mavx512dq -mavx512bw -mavx512vl -mbmi2 -mtune=cascadelake -fno-lto -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

### Static library construction

```text
ar qc <static library> <object files>
```
