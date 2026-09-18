# `libwebp-sys` `0.9.6`

Platform: Linux x86_64

## `/work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/libsharpyuv.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/vendor/sharpyuv`

### Source file examples

* `/work/vendor/sharpyuv/sharpyuv.c`
* `/work/vendor/sharpyuv/sharpyuv_cpu.c`
* `/work/vendor/sharpyuv/sharpyuv_csp.c`
* `/work/vendor/sharpyuv/sharpyuv_dsp.c`
* `/work/vendor/sharpyuv/sharpyuv_gamma.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_SSE2=1 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```

## `/work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/libwebpsys.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/vendor/src/dec`
* `/work/vendor/src/demux`
* `/work/vendor/src/dsp`
* `/work/vendor/src/enc`
* `/work/vendor/src/mux`

### Source file examples

* `/work/vendor/src/dec/alpha_dec.c`
* `/work/vendor/src/dec/buffer_dec.c`
* `/work/vendor/src/dec/frame_dec.c`
* `/work/vendor/src/dec/idec_dec.c`
* `/work/vendor/src/dec/io_dec.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_SSE2=1 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
