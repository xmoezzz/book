# `c-kzg` `1.0.3`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 2087739

Build-script executable: `/work/target/debug/build/c-kzg-e956adc71f1a2ade/build_script_build-e956adc71f1a2ade`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/c-kzg-f4992513e4ea16ac/out/libckzg.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/src`

### Source file examples

* `/work/src/c_kzg_4844.c`

### Source preparation

Working directory: `/work`

```text
/usr/bin/cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I /work/blst/bindings -w -o /work/target/debug/build/c-kzg-f4992513e4ea16ac/out/98490c8781b409d2-c_kzg_4844.o -c /work/src/c_kzg_4844.c
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1 -quiet -I /work/blst/bindings -imultiarch x86_64-linux-gnu /work/src/c_kzg_4844.c -quiet -dumpdir /work/target/debug/build/c-kzg-f4992513e4ea16ac/out/ -dumpbase 98490c8781b409d2-c_kzg_4844.c -dumpbase-ext .c -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 -O0 ...
```

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -w -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
