# `libnghttp2-sys` `0.1.7+1.45.0`

Platform: Linux riscv64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 563462

Build-script executable: `/target/debug/build/libnghttp2-sys-722df0cdf52d382a/build_script_build-722df0cdf52d382a`

Working directory: `/tmp/crate-build-riscv64-au80jzj9/src/libnghttp2-sys-0.1.7+1.45.0`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/libnghttp2-sys-6214cd0c0a1bd802/out/i/lib/libnghttp2.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-au80jzj9/src/libnghttp2-sys-0.1.7+1.45.0`

### Source directories

* `/tmp/crate-build-riscv64-au80jzj9/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib`

### Source file examples

* `/tmp/crate-build-riscv64-au80jzj9/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_buf.c`
* `/tmp/crate-build-riscv64-au80jzj9/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_callbacks.c`
* `/tmp/crate-build-riscv64-au80jzj9/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_debug.c`
* `/tmp/crate-build-riscv64-au80jzj9/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_frame.c`
* `/tmp/crate-build-riscv64-au80jzj9/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_hd.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D NGHTTP2_STATICLIB -D HAVE_NETINET_IN -D HAVE_ARPA_INET_H <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/libnghttp2-sys-6214cd0c0a1bd802/out/i/lib/nghttp2/lib/ ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
