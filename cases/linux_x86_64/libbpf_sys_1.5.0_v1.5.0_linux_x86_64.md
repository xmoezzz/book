# `libbpf-sys` `1.5.0+v1.5.0`

Platform: Linux x86_64

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
