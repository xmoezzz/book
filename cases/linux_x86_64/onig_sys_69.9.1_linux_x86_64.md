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

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -DHAVE_UNISTD_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_TIME_H=1 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
