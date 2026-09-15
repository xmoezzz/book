# `libnghttp2-sys` `0.1.7+1.45.0`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 1984190

Build-script executable: `/work/target/debug/build/libnghttp2-sys-84d6cb9c40db4ed0/build_script_build-84d6cb9c40db4ed0`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

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

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I nghttp2/lib/includes -I /work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/lib/nghttp2/lib/nghttp2_buf.o -c nghttp2/lib/nghttp2_buf.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I nghttp2/lib/includes -I /work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/include -imultiarch x86_64-linux-gnu -D NGHTTP2_STATICLIB -D HAVE_NETINET_IN -D HAVE_ARPA_INET_H nghttp2/lib/nghttp2_buf.c -quiet -dumpdir /work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/lib/nghttp2/lib/ -dumpbase nghttp2_buf.c ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I nghttp2/lib/includes -I /work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/lib/nghttp2/lib/nghttp2_callbacks.o -c nghttp2/lib/nghttp2_callbacks.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I nghttp2/lib/includes -I /work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/include -imultiarch x86_64-linux-gnu -D NGHTTP2_STATICLIB -D HAVE_NETINET_IN -D HAVE_ARPA_INET_H nghttp2/lib/nghttp2_callbacks.c -quiet -dumpdir /work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/lib/nghttp2/lib/ -dumpbase nghttp2_callbacks.c ...
```

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I nghttp2/lib/includes -I /work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/include -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o /work/target/debug/build/libnghttp2-sys-0fce1d4a97aacfbc/out/i/lib/nghttp2/lib/nghttp2_debug.o -c nghttp2/lib/nghttp2_debug.c
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -DNGHTTP2_STATICLIB -DHAVE_NETINET_IN -DHAVE_ARPA_INET_H -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
