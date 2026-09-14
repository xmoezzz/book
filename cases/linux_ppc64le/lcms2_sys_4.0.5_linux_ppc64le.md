# `lcms2-sys` `4.0.5`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 995501

Build-script executable: `/target/debug/build/lcms2-sys-e678190117c9ae61/build_script_build-e678190117c9ae61`

Working directory: `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/lcms2-sys-5fede971eb0990c2/out/liblcms2.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5`

### Source directories

* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src`

### Source file examples

* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src/cmsalpha.c`
* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src/cmscam02.c`
* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src/cmscgats.c`
* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src/cmscnvrt.c`
* `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5/vendor/src/cmserr.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I vendor/include -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/lcms2-sys-5fede971eb0990c2/out/49c72391db7e6a2b-cmsalpha.o -c vendor/src/cmsalpha.c
```

Working directory: `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I vendor/include -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/lcms2-sys-5fede971eb0990c2/out/49c72391db7e6a2b-cmscam02.o -c vendor/src/cmscam02.c
```

Working directory: `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I vendor/include -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/lcms2-sys-5fede971eb0990c2/out/49c72391db7e6a2b-cmscgats.o -c vendor/src/cmscgats.c
```

Working directory: `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I vendor/include -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/lcms2-sys-5fede971eb0990c2/out/49c72391db7e6a2b-cmscnvrt.o -c vendor/src/cmscnvrt.c
```

Working directory: `/tmp/crate-build-ppc64le-bs80rzv_/src/lcms2-sys-4.0.5`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I vendor/include -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/lcms2-sys-5fede971eb0990c2/out/49c72391db7e6a2b-cmserr.o -c vendor/src/cmserr.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
