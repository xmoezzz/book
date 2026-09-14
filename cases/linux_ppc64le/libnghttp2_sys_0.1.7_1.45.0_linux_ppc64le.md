# `libnghttp2-sys` `0.1.7+1.45.0`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 563350

Build-script executable: `/target/debug/build/libnghttp2-sys-722df0cdf52d382a/build_script_build-722df0cdf52d382a`

Working directory: `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0`

Full linker command: retained in the raw case.

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

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I nghttp2/lib/includes -I /target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/lib/nghttp2/lib/nghttp2_buf.o -c nghttp2/lib/nghttp2_buf.c
```

Working directory: `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I nghttp2/lib/includes -I /target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/lib/nghttp2/lib/nghttp2_callbacks.o -c nghttp2/lib/nghttp2_callbacks.c
```

Working directory: `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I nghttp2/lib/includes -I /target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/lib/nghttp2/lib/nghttp2_debug.o -c nghttp2/lib/nghttp2_debug.c
```

Working directory: `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I nghttp2/lib/includes -I /target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/lib/nghttp2/lib/nghttp2_frame.o -c nghttp2/lib/nghttp2_frame.c
```

Working directory: `/tmp/crate-build-ppc64le-9l_qb8kr/src/libnghttp2-sys-0.1.7+1.45.0`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I nghttp2/lib/includes -I /target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /target/powerpc64le-unknown-linux-gnu/debug/build/libnghttp2-sys-c89c130c219e0edc/out/i/lib/nghttp2/lib/nghttp2_hd.o -c nghttp2/lib/nghttp2_hd.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch powerpc64le-linux-gnu -D NGHTTP2_STATICLIB -D HAVE_NETINET_IN -D HAVE_ARPA_INET_H <source> -msecure-plt -quiet -dumpbase <source> -m64 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
