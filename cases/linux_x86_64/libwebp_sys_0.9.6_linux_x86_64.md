# `libwebp-sys` `0.9.6`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 2137536

Build-script executable: `/work/target/debug/build/libwebp-sys-9c31aff17d4c5b03/build_script_build-9c31aff17d4c5b03`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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

### Source preparation

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/vendor -imultiarch x86_64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_SSE2=1 /work/vendor/sharpyuv/sharpyuv.c -quiet -dumpdir /work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/ -dumpbase ba9ae331e1c03d63-sharpyuv.c -dumpbase-ext .c ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/vendor -imultiarch x86_64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_SSE2=1 /work/vendor/sharpyuv/sharpyuv_cpu.c -quiet -dumpdir /work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/ -dumpbase ba9ae331e1c03d63-sharpyuv_cpu.c -dumpbase-ext .c ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/vendor -imultiarch x86_64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_SSE2=1 /work/vendor/sharpyuv/sharpyuv_csp.c -quiet -dumpdir /work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/ -dumpbase ba9ae331e1c03d63-sharpyuv_csp.c -dumpbase-ext .c ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/vendor -imultiarch x86_64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_SSE2=1 /work/vendor/sharpyuv/sharpyuv_dsp.c -quiet -dumpdir /work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/ -dumpbase ba9ae331e1c03d63-sharpyuv_dsp.c -dumpbase-ext .c ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/vendor -imultiarch x86_64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_SSE2=1 /work/vendor/sharpyuv/sharpyuv_neon.c -quiet -dumpdir /work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/ -dumpbase ba9ae331e1c03d63-sharpyuv_neon.c -dumpbase-ext .c ...
```

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

### Source preparation

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/vendor -imultiarch x86_64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_SSE2=1 /work/vendor/src/dec/alpha_dec.c -quiet -dumpdir /work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/ -dumpbase 89142eb2371e4544-alpha_dec.c -dumpbase-ext .c ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/vendor -imultiarch x86_64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_SSE2=1 /work/vendor/src/dec/frame_dec.c -quiet -dumpdir /work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/ -dumpbase 89142eb2371e4544-frame_dec.c -dumpbase-ext .c ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/vendor -imultiarch x86_64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_SSE2=1 /work/vendor/src/dec/buffer_dec.c -quiet -dumpdir /work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/ -dumpbase 89142eb2371e4544-buffer_dec.c -dumpbase-ext .c ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/vendor -imultiarch x86_64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_SSE2=1 /work/vendor/src/dec/idec_dec.c -quiet -dumpdir /work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/ -dumpbase 89142eb2371e4544-idec_dec.c -dumpbase-ext .c ...
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/vendor -imultiarch x86_64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_SSE2=1 /work/vendor/src/dec/io_dec.c -quiet -dumpdir /work/target/debug/build/libwebp-sys-2cfcc612998dcbaf/out/ -dumpbase 89142eb2371e4544-io_dec.c -dumpbase-ext .c ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_SSE2=1 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
