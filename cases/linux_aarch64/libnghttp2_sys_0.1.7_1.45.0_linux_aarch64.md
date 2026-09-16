# `libnghttp2-sys` `0.1.7+1.45.0`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/lib/libnghttp2.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0`

### Source directories

* `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib`

### Source file examples

* `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_buf.c`
* `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_callbacks.c`
* `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_debug.c`
* `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_frame.c`
* `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0/nghttp2/lib/nghttp2_hd.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I nghttp2/lib/includes -I /target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/lib/nghttp2/lib/nghttp2_buf.o -c nghttp2/lib/nghttp2_buf.c
```

Working directory: `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I nghttp2/lib/includes -I /target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/lib/nghttp2/lib/nghttp2_callbacks.o -c nghttp2/lib/nghttp2_callbacks.c
```

Working directory: `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I nghttp2/lib/includes -I /target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/lib/nghttp2/lib/nghttp2_debug.o -c nghttp2/lib/nghttp2_debug.c
```

Working directory: `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I nghttp2/lib/includes -I /target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/lib/nghttp2/lib/nghttp2_frame.o -c nghttp2/lib/nghttp2_frame.c
```

Working directory: `/tmp/crate-build-aarch64-j60ftest/src/libnghttp2-sys-0.1.7+1.45.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -I nghttp2/lib/includes -I /target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /target/aarch64-unknown-linux-gnu/debug/build/libnghttp2-sys-f3a403acb65c6e94/out/i/lib/nghttp2/lib/nghttp2_hd.o -c nghttp2/lib/nghttp2_hd.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultiarch aarch64-linux-gnu -D NGHTTP2_STATICLIB -D HAVE_NETINET_IN -D HAVE_ARPA_INET_H <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
