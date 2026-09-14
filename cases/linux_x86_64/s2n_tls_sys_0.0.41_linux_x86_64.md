# `s2n-tls-sys` `0.0.41`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1986203

Build-script executable: `/work/target/debug/build/s2n-tls-sys-83a7f9a6cf5b3121/build_script_build-83a7f9a6cf5b3121`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/s2n-tls-sys-08b02e6450b7ea17/out/libs2n-tls.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/lib`

### Source file examples

* `/work/lib/crypto/s2n_aead_cipher_aes_gcm.c`
* `/work/lib/crypto/s2n_aead_cipher_chacha20_poly1305.c`
* `/work/lib/crypto/s2n_cbc_cipher_3des.c`
* `/work/lib/crypto/s2n_cbc_cipher_aes.c`
* `/work/lib/crypto/s2n_certificate.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -I <include directory> -std=c11 -fgnu89-inline -D_POSIX_C_SOURCE=200112L -DS2N_NO_PQ=1 -DS2N_ATOMIC_SUPPORTED=1 -DS2N_CLOEXEC_XOPEN_SUPPORTED=1 -DS2N_CLONE_SUPPORTED=1 -DS2N_CPUID_AVAILABLE=1 -DS2N_DIAGNOSTICS_POP_SUPPORTED=1 -DS2N_DIAGNOSTICS_PUSH_SUPPORTED=1 -DS2N_EXECINFO_AVAILABLE=1 -DS2N_FALL_THROUGH_SUPPORTED=1 -DS2N_FEATURES_AVAILABLE=1 -DS2N_KTLS_SUPPORTED=1 -DS2N_KYBER512R3_AVX2_BMI2_SUPPORTED=1 -DS2N_KYBER512R3_M256_INTRINSICS_SUPPORTED=1 -DS2N_LIBCRYPTO_SUPPORTS_EVP_MD5_SHA1_HASH=1 -DS2N_LIBCRYPTO_SUPPORTS_EVP_MD_CTX_SET_PKEY_CTX=1 -DS2N_LIBCRYPTO_SUPPORTS_EVP_RC4=1 -DS2N_LIBCRYPTO_SUPPORTS_FLAG_NO_CHECK_TIME=1 -DS2N_LINUX_SENDFILE=1 -DS2N_MADVISE_SUPPORTED=1 -DS2N___RESTRICT__SUPPORTED=1 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
