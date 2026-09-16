# `libwebp-sys` `0.9.6`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/libsharpyuv.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

### Source directories

* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv`

### Source file examples

* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv.c`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_cpu.c`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_csp.c`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_dsp.c`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_neon.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -I /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_NEON=1 -o /target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/ba9ae331e1c03d63-sharpyuv_cpu.o -c /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_cpu.c
```

Working directory: `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -I /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_NEON=1 -o /target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/ba9ae331e1c03d63-sharpyuv_csp.o -c /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_csp.c
```

Working directory: `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -I /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_NEON=1 -o /target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/ba9ae331e1c03d63-sharpyuv_dsp.o -c /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_dsp.c
```

Working directory: `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -I /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_NEON=1 -o /target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/ba9ae331e1c03d63-sharpyuv_neon.o -c /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_neon.c
```

Working directory: `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

```text
/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor -imultiarch aarch64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_NEON=1 /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_sse2.c -quiet -dumpbase sharpyuv_sse2.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/ba9ae331e1c03d63-sharpyuv_sse2.o ...
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_NEON=1 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -I <include directory> -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_NEON=1 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```

## `/target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/libwebpsys.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

### Source directories

* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/demux`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dsp`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/enc`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/utils`

### Source file examples

* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec/alpha_dec.c`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec/buffer_dec.c`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec/frame_dec.c`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec/idec_dec.c`
* `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec/io_dec.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -I /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_NEON=1 -o /target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/89142eb2371e4544-alpha_dec.o -c /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec/alpha_dec.c
```

Working directory: `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

```text
/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor -imultiarch aarch64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_NEON=1 /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec/buffer_dec.c -quiet -dumpbase buffer_dec.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/89142eb2371e4544-buffer_dec.o ...
```

Working directory: `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -I /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_NEON=1 -o /target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/89142eb2371e4544-frame_dec.o -c /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec/frame_dec.c
```

Working directory: `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -I /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_NEON=1 -o /target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/89142eb2371e4544-idec_dec.o -c /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec/idec_dec.c
```

Working directory: `/tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -I /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_NEON=1 -o /target/aarch64-unknown-linux-gnu/debug/build/libwebp-sys-3212adcfa46bb5b0/out/89142eb2371e4544-io_dec.o -c /tmp/crate-build-aarch64-vqe8rpqm/src/libwebp-sys-0.9.6/vendor/src/dec/io_dec.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 -D WEBP_HAVE_NEON=1 <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -I <include directory> -Wall -Wextra -fvisibility=hidden -Wall -DNDEBUG=1 -D_THREAD_SAFE=1 -DWEBP_HAVE_NEON=1 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
