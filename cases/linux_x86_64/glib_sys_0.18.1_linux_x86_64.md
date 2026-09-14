# `glib-sys` `0.18.1`

Platform: Linux x86_64

## Build-level coding evidence

### pkg-config / pkgconf

Working directory: `/work`

```text
pkg-config --libs --cflags glib-2.0 "glib-2.0 >= 2.56"
```

Working directory: `/work`

```text
pkg-config --modversion glib-2.0 "glib-2.0 >= 2.56"
```

Working directory: `/work`

```text
pkg-config --libs --cflags gobject-2.0 "gobject-2.0 >= 2.56"
```

Working directory: `/work`

```text
pkg-config --modversion gobject-2.0 "gobject-2.0 >= 2.56"
```

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1903183

Build-script executable: `/work/target/debug/build/glib-sys-ed1d4068725fe518/build_script_build-ed1d4068725fe518`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)
