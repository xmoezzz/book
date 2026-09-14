# `tree-sitter-python` `0.23.6`

Platform: Linux ppc64le

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 902002

Build-script executable: `/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311`

Working directory: `/tmp/crate-build-ppc64le-td_mnp7p/src/tree-sitter-python-0.23.6`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-python-8658ffea3e282e28/out/libtree-sitter-python.a`

### Source origin

* under crate source directory `/tmp/crate-build-ppc64le-td_mnp7p/src/tree-sitter-python-0.23.6`

### Source directories

* `/tmp/crate-build-ppc64le-td_mnp7p/src/tree-sitter-python-0.23.6/src`

### Source file examples

* `/tmp/crate-build-ppc64le-td_mnp7p/src/tree-sitter-python-0.23.6/src/parser.c`
* `/tmp/crate-build-ppc64le-td_mnp7p/src/tree-sitter-python-0.23.6/src/scanner.c`

### Source preparation

Working directory: `/tmp/crate-build-ppc64le-td_mnp7p/src/tree-sitter-python-0.23.6`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-python-8658ffea3e282e28/out/ea708c7824d36062-parser.o -c src/parser.c
```

Working directory: `/tmp/crate-build-ppc64le-td_mnp7p/src/tree-sitter-python-0.23.6`

```text
/usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-python-8658ffea3e282e28/out/ea708c7824d36062-scanner.o -c src/scanner.c
```

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch powerpc64le-linux-gnu <source> -msecure-plt -quiet -dumpbase <source> -m64 -mcpu=power8 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -Wextra ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
