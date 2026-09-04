# `miniz-sys` `0.1.12`

Platform: Linux x86_64

## `/work/target/debug/build/miniz-sys-21d1cb3132dd7174/out/libminiz.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work`

### Source file examples

* `/work/miniz.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -fvisibility=hidden -DMINIZ_NO_STDIO -DMINIZ_NO_ARCHIVE_APIS -DMINIZ_NO_ARCHIVE_WRITING_APIS -DMINIZ_NO_TIME -DMINIZ_NO_ZLIB_COMPATIBLE_NAMES -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
