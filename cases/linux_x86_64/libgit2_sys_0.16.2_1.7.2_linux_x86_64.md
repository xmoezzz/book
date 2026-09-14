# `libgit2-sys` `0.16.2+1.7.2`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1879390

Build-script executable: `/work/target/debug/build/libgit2-sys-6afb27b01e737f8d/build_script_build-6afb27b01e737f8d`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/libgit2-sys-44ba7eb72a3e5d1b/out/build/libgit2.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/libgit2`

### Source file examples

* `/work/libgit2/deps/http-parser/http_parser.c`
* `/work/libgit2/deps/pcre/pcre_byte_order.c`
* `/work/libgit2/deps/pcre/pcre_chartables.c`
* `/work/libgit2/deps/pcre/pcre_compile.c`
* `/work/libgit2/deps/pcre/pcre_config.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -w -fvisibility=hidden -DGIT_REGEX_BUILTIN=1 -DHAVE_STDINT_H=1 -DHAVE_MEMMOVE=1 -DNO_RECURSE=1 -DNEWLINE=10 -DPOSIX_MALLOC_THRESHOLD=10 -DLINK_SIZE=2 -DPARENS_NEST_LIMIT=250 -DMATCH_LIMIT=10000000 -DMATCH_LIMIT_RECURSION=MATCH_LIMIT -DMAX_NAME_SIZE=32 -DMAX_NAME_COUNT=10000 -DSHA1DC_NO_STANDARD_INCLUDES=1 -DSHA1DC_CUSTOM_INCLUDE_SHA1_C="common.h" -DSHA1DC_CUSTOM_INCLUDE_UBC_CHECK_C="common.h" -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
