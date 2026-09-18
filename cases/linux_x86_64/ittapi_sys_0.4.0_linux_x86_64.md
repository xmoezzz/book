# `ittapi-sys` `0.4.0`

Platform: Linux x86_64

## `/work/target/debug/build/ittapi-sys-f438b9b74b041e0a/out/libittnotify.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/c-library/src/ittnotify`

### Source file examples

* `/work/c-library/src/ittnotify/ittnotify_static.c`
* `/work/c-library/src/ittnotify/jitprofiling.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
