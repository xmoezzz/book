# `libwebp-sys` `0.9.6`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 1003315

Build-script executable: `/target/debug/build/libwebp-sys-d20e776345980990/build_script_build-d20e776345980990`

Working directory: `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/powerpc64le-unknown-linux-gnu/debug/build/libwebp-sys-352f3e5efd9f8302/out/libsharpyuv.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6`

### Source directories

* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/sharpyuv`

### Source file examples

* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv.c`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_cpu.c`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_csp.c`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_dsp.c`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/sharpyuv/sharpyuv_gamma.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```

## `/target/powerpc64le-unknown-linux-gnu/debug/build/libwebp-sys-352f3e5efd9f8302/out/libwebpsys.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6`

### Source directories

* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/src/dec`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/src/demux`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/src/dsp`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/src/enc`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/src/utils`

### Source file examples

* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/src/dec/alpha_dec.c`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/src/dec/buffer_dec.c`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/src/dec/frame_dec.c`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/src/dec/idec_dec.c`
* `/tmp/crate-build-ppc64le-mdilb4hc/src/libwebp-sys-0.9.6/vendor/src/dec/io_dec.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu -D NDEBUG=1 -D _THREAD_SAFE=1 <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
