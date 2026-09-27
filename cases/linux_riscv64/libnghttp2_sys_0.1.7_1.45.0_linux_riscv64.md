# `libnghttp2-sys` `0.1.7+1.45.0`

Platform: Linux riscv64

## Submodule

Repository: `https://github.com/alexcrichton/nghttp2-rs`
Crate release commit: `02f226d5fcc211d22785ac0cc9bb84d3421decc4`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `nghttp2`

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
