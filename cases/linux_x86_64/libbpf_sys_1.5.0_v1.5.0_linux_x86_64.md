# `libbpf-sys` `1.5.0+v1.5.0`

Platform: Linux x86_64

## Build-level coding evidence

### pkg-config / pkgconf

Working directory: `/work/libbpf/src`

```text
pkg-config --cflags libelf zlib
```

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 2069767

Build-script executable: `/work/target/debug/build/libbpf-sys-fef3364d6dc1f4d1/build_script_build-fef3364d6dc1f4d1`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/libbpf-sys-e3f36c75b44831f5/out/obj/libbpf.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/libbpf/src`

### Source file examples

* `/work/libbpf/src/bpf.c`
* `/work/libbpf/src/bpf_prog_linfo.c`
* `/work/libbpf/src/btf.c`
* `/work/libbpf/src/btf_dump.c`
* `/work/libbpf/src/btf_iter.c`

### Compilation

```text
cc -I<include directory> -I<include directory> -I<include directory> -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -D_LARGEFILE64_SOURCE -D_FILE_OFFSET_BITS=64 -Wno-unknown-warning-option -Wno-format-overflow -c <source> -o <object>
```

### Static library construction

```text
ar rcs <static library> <object files>
```
