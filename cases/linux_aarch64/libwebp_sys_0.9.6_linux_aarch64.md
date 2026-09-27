# `libwebp-sys` `0.9.6`

Platform: Linux aarch64

## Submodule

Repository: `https://github.com/NoXF/libwebp-sys`
Crate release commit: `4007a323c1dcc4ad11d70ddadffc51ecfa1dbb5e`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `vendor`

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
