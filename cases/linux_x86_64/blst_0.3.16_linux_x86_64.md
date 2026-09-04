# `blst` `0.3.16`

Platform: Linux x86_64

## `/work/target/debug/build/blst-1a71e90ce1f068b5/out/libblst.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/blst/build`
* `/work/blst/src`

### Source file examples

* `/work/blst/build/assembly.S`
* `/work/blst/src/server.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -D__ADX__ -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
