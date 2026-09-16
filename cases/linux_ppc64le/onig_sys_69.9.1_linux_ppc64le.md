# `onig_sys` `69.9.1`

Platform: Linux ppc64le

## `/target/powerpc64le-unknown-linux-gnu/debug/build/onig_sys-420b899eb2b0f695/out/libonig.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1`

### Source directories

* `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1/oniguruma/src`

### Source file examples

* `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1/oniguruma/src/ascii.c`
* `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1/oniguruma/src/onig_init.c`
* `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1/oniguruma/src/regcomp.c`
* `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1/oniguruma/src/regenc.c`
* `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1/oniguruma/src/regerror.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/onig_sys-420b899eb2b0f695/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/powerpc64le-unknown-linux-gnu/debug/build/onig_sys-420b899eb2b0f695/out/a445302c6d3dcb51-regerror.o -c oniguruma/src/regerror.c
```

Working directory: `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/onig_sys-420b899eb2b0f695/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/powerpc64le-unknown-linux-gnu/debug/build/onig_sys-420b899eb2b0f695/out/a445302c6d3dcb51-regparse.o -c oniguruma/src/regparse.c
```

Working directory: `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1`

```text
/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/onig_sys-420b899eb2b0f695/out -I oniguruma/src -imultiarch powerpc64le-linux-gnu -D HAVE_UNISTD_H=1 -D HAVE_SYS_TYPES_H=1 -D HAVE_SYS_TIME_H=1 oniguruma/src/regext.c -msecure-plt -quiet -dumpbase regext.c -m64 ...
```

Working directory: `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/onig_sys-420b899eb2b0f695/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/powerpc64le-unknown-linux-gnu/debug/build/onig_sys-420b899eb2b0f695/out/a445302c6d3dcb51-regcomp.o -c oniguruma/src/regcomp.c
```

Working directory: `/tmp/crate-build-ppc64le-2633tc0r/src/onig_sys-69.9.1`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /target/powerpc64le-unknown-linux-gnu/debug/build/onig_sys-420b899eb2b0f695/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /target/powerpc64le-unknown-linux-gnu/debug/build/onig_sys-420b899eb2b0f695/out/a445302c6d3dcb51-reggnu.o -c oniguruma/src/reggnu.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch powerpc64le-linux-gnu -D HAVE_UNISTD_H=1 -D HAVE_SYS_TYPES_H=1 -D HAVE_SYS_TIME_H=1 <source> -msecure-plt -quiet -dumpbase <source> -m64 ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
