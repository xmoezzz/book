# `aws-lc-sys` `0.30.0`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1915292

Build-script executable: `/work/target/debug/build/aws-lc-sys-2ddc6a4fc231e76f/build_script_main-2ddc6a4fc231e76f`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

### Other root-owned linker native-library inputs

#### Linker process 1915674

Link output: `/work/target/debug/build/aws-lc-sys-53d8903074a0b2d2/out/memcmp_invalid_stripped_check`

Working directory: `/work`

```text
/work/.tmp/native-trace-1912198-1784021571460/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/12/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/12/lto-wrapper -plugin-opt=-fresolution=/work/.tmp/ccfbCEEw.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -o /work/target/debug/build/aws-lc-sys-53d8903074a0b2d2/out/memcmp_invalid_stripped_check /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/12/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/12 -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/12/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/12/../../.. /work/.tmp/ccvZTCUy.o --trace -Map /work/.tmp/native-trace-link-cc-1915639-1784021580735108173.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/12/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 1915639

Link output: `/work/target/debug/build/aws-lc-sys-53d8903074a0b2d2/out/memcmp_invalid_stripped_check`

Working directory: `/work`

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra /work/aws-lc/tests/compiler_features_tests/memcmp_invalid_stripped_check.c -Wno-unused-parameter -o /work/target/debug/build/aws-lc-sys-53d8903074a0b2d2/out/memcmp_invalid_stripped_check
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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
