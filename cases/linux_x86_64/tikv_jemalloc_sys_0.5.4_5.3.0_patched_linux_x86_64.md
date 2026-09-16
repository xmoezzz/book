# `tikv-jemalloc-sys` `0.5.4+5.3.0-patched`

Platform: Linux x86_64

## `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/lib/libjemalloc.a`

### Source origin

* under build output directory `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out`

### Source directories

* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src`

### Source file examples

* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src/arena.c`
* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src/background_thread.c`
* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src/base.c`
* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src/bin.c`
* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src/bin_info.c`

### Compilation

```text
cc -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -c -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -I<include directory> -I<include directory> -o <object> <source>
```

### Static library construction

```text
ar crus <static library> <object files>
```

## `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/lib/libjemalloc_pic.a`

### Source origin

* under build output directory `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out`

### Source directories

* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src`

### Source file examples

* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src/arena.c`
* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src/background_thread.c`
* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src/base.c`
* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src/bin.c`
* `/work/target/debug/build/tikv-jemalloc-sys-1d2e3cb703355b36/out/build/src/bin_info.c`

### Compilation

```text
cc -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -fPIC -DPIC -c -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -I<include directory> -I<include directory> -o <object> <source>
```

### Static library construction

```text
ar crus <static library> <object files>
```
