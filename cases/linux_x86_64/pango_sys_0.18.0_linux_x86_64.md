# `pango-sys` `0.18.0`

Platform: Linux x86_64

## Build-level coding evidence

### pkg-config / pkgconf

Working directory: `/work`

```text
pkg-config --libs --cflags pango "pango >= 1.40"
```

Working directory: `/work`

```text
pkg-config --modversion pango "pango >= 1.40"
```

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1912007

Build-script executable: `/work/target/debug/build/pango-sys-e87da1ab65491156/build_script_build-e87da1ab65491156`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)
