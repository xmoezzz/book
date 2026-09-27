# `libwebp-sys` `0.9.6`

Platform: Linux riscv64

## Submodule

Repository: `https://github.com/NoXF/libwebp-sys`
Crate release commit: `4007a323c1dcc4ad11d70ddadffc51ecfa1dbb5e`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `vendor`

## `/target/riscv64gc-unknown-linux-gnu/debug/build/libwebp-sys-4d0268ff836c5918/out/libsharpyuv.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6`

### Source directories

* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/sharpyuv`

### Source file examples

* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv.c`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_csp.c`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_dsp.c`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_gamma.c`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_neon.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/libwebp-sys-4d0268ff836c5918/out/ -dumpbase <source> -dumpbase-ext .c ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```

## `/target/riscv64gc-unknown-linux-gnu/debug/build/libwebp-sys-4d0268ff836c5918/out/libwebpsys.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6`

### Source directories

* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/src/dec`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/src/demux`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/src/dsp`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/src/enc`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/src/utils`

### Source file examples

* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/src/dec/alpha_dec.c`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/src/dec/buffer_dec.c`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/src/dec/frame_dec.c`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/src/dec/idec_dec.c`
* `/tmp/crate-build-riscv64-t6qavx3e/src/libwebp-sys-0.9.6/vendor/src/dec/io_dec.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/libwebp-sys-4d0268ff836c5918/out/ -dumpbase <source> -dumpbase-ext .c ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
