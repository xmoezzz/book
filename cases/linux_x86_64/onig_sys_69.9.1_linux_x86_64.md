# `onig_sys` `69.9.1`

Platform: Linux x86_64

## `/work/target/debug/build/onig_sys-f19d2ec133539df1/out/libonig.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/oniguruma/src`

### Source file examples

* `/work/oniguruma/src/ascii.c`
* `/work/oniguruma/src/big5.c`
* `/work/oniguruma/src/cp1251.c`
* `/work/oniguruma/src/euc_jp.c`
* `/work/oniguruma/src/euc_jp_prop.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /work/target/debug/build/onig_sys-f19d2ec133539df1/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /work/target/debug/build/onig_sys-f19d2ec133539df1/out/a445302c6d3dcb51-regexec.o -c oniguruma/src/regexec.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/target/debug/build/onig_sys-f19d2ec133539df1/out -I oniguruma/src -imultiarch x86_64-linux-gnu -D HAVE_UNISTD_H=1 -D HAVE_SYS_TYPES_H=1 -D HAVE_SYS_TIME_H=1 oniguruma/src/regexec.c -quiet -dumpdir /work/target/debug/build/onig_sys-f19d2ec133539df1/out/ -dumpbase a445302c6d3dcb51-regexec.c ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /work/target/debug/build/onig_sys-f19d2ec133539df1/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /work/target/debug/build/onig_sys-f19d2ec133539df1/out/a445302c6d3dcb51-regerror.o -c oniguruma/src/regerror.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/target/debug/build/onig_sys-f19d2ec133539df1/out -I oniguruma/src -imultiarch x86_64-linux-gnu -D HAVE_UNISTD_H=1 -D HAVE_SYS_TYPES_H=1 -D HAVE_SYS_TIME_H=1 oniguruma/src/regerror.c -quiet -dumpdir /work/target/debug/build/onig_sys-f19d2ec133539df1/out/ -dumpbase a445302c6d3dcb51-regerror.c ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /work/target/debug/build/onig_sys-f19d2ec133539df1/out -I oniguruma/src -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o /work/target/debug/build/onig_sys-f19d2ec133539df1/out/a445302c6d3dcb51-regparse.o -c oniguruma/src/regparse.c
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
