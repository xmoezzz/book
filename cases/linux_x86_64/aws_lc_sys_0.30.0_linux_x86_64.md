# `aws-lc-sys` `0.30.0`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/aws/aws-lc-rs`
Crate release commit: `e2e9e8222a68e3512eec6ffc1b332f45d0b151f6`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `aws-lc-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `aws-lc-fips-sys/aws-lc`
- `aws-lc-sys/aws-lc`

## `/work/target/debug/build/aws-lc-sys-53d8903074a0b2d2/out/libaws_lc_0_30_0_crypto.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work`

### Source file examples

* `/work/aws-lc/crypto/asn1/a_bitstr.c`
* `/work/aws-lc/crypto/asn1/a_bool.c`
* `/work/aws-lc/crypto/asn1/a_d2i_fp.c`
* `/work/aws-lc/crypto/asn1/a_dup.c`
* `/work/aws-lc/crypto/asn1/a_gentm.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -Wall -Wextra -Wno-unused-parameter -pthread -D_XOPEN_SOURCE=700 -DBORINGSSL_IMPLEMENTATION=1 -DBORINGSSL_PREFIX=aws_lc_0_30_0 -DAWS_LC_STDALIGN_AVAILABLE=1 -DAWS_LC_BUILTIN_SWAP_SUPPORTED=1 -o <object> -c <source>
```

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -Wall -Wextra -Wno-unused-parameter -pthread --include=/work/generated-include/openssl/boringssl_prefix_symbols_asm.h -D_XOPEN_SOURCE=700 -DBORINGSSL_IMPLEMENTATION=1 -DBORINGSSL_PREFIX=aws_lc_0_30_0 -DAWS_LC_STDALIGN_AVAILABLE=1 -DAWS_LC_BUILTIN_SWAP_SUPPORTED=1 -DS2N_BN_HIDE_SYMBOLS=1 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
