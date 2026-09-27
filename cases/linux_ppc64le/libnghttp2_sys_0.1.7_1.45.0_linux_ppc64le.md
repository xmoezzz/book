# `libnghttp2-sys` `0.1.7+1.45.0`

Platform: Linux ppc64le

## Submodule

Repository: `https://github.com/alexcrichton/nghttp2-rs`
Crate release commit: `02f226d5fcc211d22785ac0cc9bb84d3421decc4`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `nghttp2`

## `/target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/lib/libnghttp2.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0`

### Source directories

* `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib`

### Source file examples

* `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_buf.c`
* `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_callbacks.c`
* `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_debug.c`
* `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_frame.c`
* `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_hd.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch powerpc64le-linux-gnu -D NGHTTP2_STATICLIB -D HAVE_NETINET_IN -D HAVE_ARPA_INET_H <source> -msecure-plt -quiet -dumpbase <source> -m64 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
