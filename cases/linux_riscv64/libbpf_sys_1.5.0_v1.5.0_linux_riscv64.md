# `libbpf-sys` `1.5.0+v1.5.0`

Platform: Linux riscv64

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
