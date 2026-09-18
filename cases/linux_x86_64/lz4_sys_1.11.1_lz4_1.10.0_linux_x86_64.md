# `lz4-sys` `1.11.1+lz4-1.10.0`

Platform: Linux x86_64

## `/work/target/debug/build/lz4-sys-544d4bf21ea43c0f/out/liblz4.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/liblz4/lib`

### Source file examples

* `/work/liblz4/lib/lz4.c`
* `/work/liblz4/lib/lz4frame.c`
* `/work/liblz4/lib/lz4hc.c`
* `/work/liblz4/lib/xxhash.c`

### Compilation

```text
cc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
