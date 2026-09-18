# `aws-lc-fips-sys` `0.13.6`

Platform: Linux x86_64

## `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/artifacts/libaws_lc_fips_0_13_6_rust_wrapper.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work`

### Source file examples

* `/work/rust_wrapper.c`

### Compilation

```text
cc -DBORINGSSL_PREFIX=aws_lc_fips_0_13_6 -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -g -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

### Static library construction

```text
ar qc <static library> <object files>
```

## `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/../../artifacts/libaws_lc_fips_0_13_6_crypto.a`

### Source origin

* under crate source directory `/work`
* under build output directory `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out`

### Source directories

* `/work`

### Source file examples

* `/work/aws-lc/crypto/asn1/a_bitstr.c`
* `/work/aws-lc/crypto/asn1/a_bool.c`
* `/work/aws-lc/crypto/asn1/a_d2i_fp.c`
* `/work/aws-lc/crypto/asn1/a_dup.c`
* `/work/aws-lc/crypto/asn1/a_gentm.c`

### Source preparation

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/perl /work/aws-lc/crypto/test/asm/trampoline-x86_64.pl elf test/trampoline-x86_64.S
```

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/perl /work/aws-lc/crypto/chacha/asm/chacha-x86_64.pl elf chacha/chacha-x86_64.S
```

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/perl /work/aws-lc/crypto/cipher_extra/asm/aesni-sha1-x86_64.pl elf cipher_extra/aesni-sha1-x86_64.S
```

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/perl /work/aws-lc/crypto/cipher_extra/asm/chacha20_poly1305_x86_64.pl elf cipher_extra/chacha20_poly1305_x86_64.S
```

Working directory: `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto`

```text
/work/.tmp/native-trace-1933546-1784021623052/shims/perl /work/aws-lc/crypto/cipher_extra/asm/aes128gcmsiv-x86_64.pl elf cipher_extra/aes128gcmsiv-x86_64.S
```

### Compilation

```text
cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -Wredundant-decls -Wextra -Wunused -Wcomment -Wchar-subscripts -Wuninitialized -Wshadow -Wwrite-strings -Wformat-security -Wunused-result -Wno-overlength-strings -Wno-cast-function-type -Wall -fvisibility=hidden -fno-common -Wno-c11-extensions -Wvla -Wtype-limits -Wno-unused-parameter -Werror -Wformat=2 -Wsign-compare -Wmissing-field-initializers -Wwrite-strings -ggdb -Wno-free-nonheap-object -Wmissing-braces -Wimplicit-fallthrough -Wmissing-prototypes -Wold-style-definition -Wstrict-prototypes -DAWS_LC_STDALIGN_AVAILABLE -DAWS_LC_BUILTIN_SWAP_SUPPORTED -DAWS_LC_URANDOM_U32 -Wshadow -D_XOPEN_SOURCE=700 -g -fPIC -std=gnu11 -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

```text
cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -Wno-newline-eof -Wa,--noexecstack -Wa,-g -g -fPIC -o <object> -c <source>
```

### Static library construction

```text
ar qc <static library> <object files>
```

## `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/fipsmodule/libbcm_c_generated_asm.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/aws-lc/crypto/fipsmodule`

### Source file examples

* `/work/aws-lc/crypto/fipsmodule/bcm.c`

### Compilation

```text
cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -Wredundant-decls -Wextra -Wunused -Wcomment -Wchar-subscripts -Wuninitialized -Wshadow -Wwrite-strings -Wformat-security -Wunused-result -Wno-overlength-strings -Wno-cast-function-type -Wall -fvisibility=hidden -fno-common -Wno-c11-extensions -Wvla -Wtype-limits -Wno-unused-parameter -Werror -Wformat=2 -Wsign-compare -Wmissing-field-initializers -Wwrite-strings -ggdb -Wno-free-nonheap-object -Wmissing-braces -Wimplicit-fallthrough -Wmissing-prototypes -Wold-style-definition -Wstrict-prototypes -DAWS_LC_STDALIGN_AVAILABLE -DAWS_LC_BUILTIN_SWAP_SUPPORTED -DAWS_LC_URANDOM_U32 -Wshadow -D_XOPEN_SOURCE=700 -g -fPIC -S -std=gnu11 -MD -MT <dependency target> -MF <dependency file> -o <object> -c <source>
```

### Static library construction

```text
ar qc <static library> <object files>
```

## `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/fipsmodule/libbcm_hashunset.a`

### Source origin

* under build output directory `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out`

### Source directories

* `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/fipsmodule`

### Source file examples

* `/work/target/debug/build/aws-lc-fips-sys-d8201ea4f3698768/out/build/aws-lc/crypto/fipsmodule/bcm-delocated.S`

### Compilation

```text
cc -DBORINGSSL_FIPS -DBORINGSSL_IMPLEMENTATION -DFIPS_ENTROPY_SOURCE_PASSIVE -I<include directory> -I<include directory> -ffunction-sections -fdata-sections -fPIC -m64 -Wno-newline-eof -Wa,--noexecstack -Wa,-g -g -fPIC -o <object> -c <source>
```

### Static library construction

```text
ar qc <static library> <object files>
```
