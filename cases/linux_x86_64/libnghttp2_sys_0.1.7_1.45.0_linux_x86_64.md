# `libnghttp2-sys` `0.1.7+1.45.0`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/alexcrichton/nghttp2-rs`
Crate release commit: `02f226d5fcc211d22785ac0cc9bb84d3421decc4`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `nghttp2`

## `/work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/lib/libnghttp2.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/nghttp2/lib`

### Source file examples

* `/work/nghttp2/lib/nghttp2_buf.c`
* `/work/nghttp2/lib/nghttp2_callbacks.c`
* `/work/nghttp2/lib/nghttp2_debug.c`
* `/work/nghttp2/lib/nghttp2_frame.c`
* `/work/nghttp2/lib/nghttp2_hd.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
