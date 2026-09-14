# `libbpf-sys` `1.5.0+v1.5.0`

Platform: Linux riscv64

## Build-level coding evidence

### pkg-config / pkgconf

Working directory: `/tmp/crate-build-riscv64-utk15keu/src/libbpf-sys-1.5.0+v1.5.0/libbpf/src`

```text
pkg-config --cflags libelf zlib
```

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 832596

Build-script executable: `/target/debug/build/libbpf-sys-7bc730b0c3eff001/build_script_build-7bc730b0c3eff001`

Working directory: `/tmp/crate-build-riscv64-utk15keu/src/libbpf-sys-1.5.0+v1.5.0`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/libbpf-sys-012b9e38ffe91251/out/obj/libbpf.a`

### Source origin

* matches Linux x86_64 source path `/work/libbpf/src/bpf_prog_linfo.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/btf.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/btf_iter.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/elf.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/gen_loader.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/libbpf.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/libbpf_probes.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/linker.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/netlink.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/strset.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/usdt.c`, under crate source directory `/work`
* matches Linux x86_64 source path `/work/libbpf/src/zip.c`, under crate source directory `/work`

### Source file examples

* `bpf_prog_linfo.c`
* `btf.c`
* `btf_iter.c`
* `elf.c`
* `gen_loader.c`

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -D _LARGEFILE64_SOURCE -D _FILE_OFFSET_BITS=64 <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/libbpf-sys-012b9e38ffe91251/out/obj/staticobjs/ ...
```

### Static library construction

```text
ar rcs <static library> <object files>
```
