# `onig_sys` `69.9.1`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out/libonig.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1`

### Source directories

* `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1/oniguruma/src`

### Source file examples

* `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1/oniguruma/src/ascii.c`
* `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1/oniguruma/src/onig_init.c`
* `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1/oniguruma/src/regcomp.c`
* `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1/oniguruma/src/regenc.c`
* `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1/oniguruma/src/regerror.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out/a445302c6d3dcb51-regexec.o -c oniguruma/src/regexec.c
```

Working directory: `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out/a445302c6d3dcb51-regerror.o -c oniguruma/src/regerror.c
```

Working directory: `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out/a445302c6d3dcb51-regparse.o -c oniguruma/src/regparse.c
```

Working directory: `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out/a445302c6d3dcb51-regext.o -c oniguruma/src/regext.c
```

Working directory: `/tmp/crate-build-aarch64-wmynz6m0/src/onig_sys-69.9.1`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/aarch64-unknown-linux-gnu/debug/build/onig_sys-b9649950dc8f1c3f/out/a445302c6d3dcb51-reggnu.o -c oniguruma/src/reggnu.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu -D HAVE_UNISTD_H=1 -D HAVE_SYS_TYPES_H=1 -D HAVE_SYS_TIME_H=1 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I <include directory> -I <include directory> -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
