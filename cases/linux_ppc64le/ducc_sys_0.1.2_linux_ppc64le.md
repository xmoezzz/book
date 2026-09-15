# `ducc-sys` `0.1.2`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 907958

Build-script executable: `/target/debug/build/ducc-sys-cc5bc5d8537a5ab0/build_script_build-cc5bc5d8537a5ab0`

Working directory: `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/libduktape.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2`

### Source directories

* `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/duktape`

### Source file examples

* `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/duktape/duktape.c`
* `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2/duktape/wrapper.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I duktape -Wall -Wextra -std=c99 -o /target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/duktape.o -c duktape/duktape.c
```

Working directory: `/tmp/crate-build-ppc64le-bvllp_0w/src/ducc-sys-0.1.2`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -I duktape -Wall -Wextra -std=c99 -o /target/powerpc64le-unknown-linux-gnu/debug/build/ducc-sys-f0f41adf3b4047ae/out/duktape/wrapper.o -c duktape/wrapper.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -O0 -Wall -Wextra -std=c99 ...
```

### Static library construction

```text
ar crs <static library> <object files>
```
