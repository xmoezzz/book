# `tiny-xlib` `0.2.4`

Platform: Linux x86_64

## Build-level coding evidence

### pkg-config / pkgconf

Working directory: `/work`

```text
pkg-config --libs --cflags x11
```

Working directory: `/work`

```text
pkg-config --modversion x11
```

Working directory: `/work`

```text
pkg-config --libs --cflags x11-xcb
```

Working directory: `/work`

```text
pkg-config --modversion x11-xcb
```

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 2131137

Build-script executable: `/work/target/debug/build/tiny-xlib-268ab96de0d15394/build_script_build-268ab96de0d15394`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)
