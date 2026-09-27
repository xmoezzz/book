# `hidapi` `2.6.3`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/ruabmbua/hidapi-rs`
Crate release commit: `ef8ee38edf81d8e48267e6c4f79cda57d8ca225a`
Commit evidence: published crate `.cargo_vcs_info.json`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `etc/hidapi`

## Build-level coding evidence

### pkg-config / pkgconf

Working directory: `/work`

```text
pkg-config --libs --cflags libudev
```

Working directory: `/work`

```text
pkg-config --modversion libudev
```

## `/work/target/debug/build/hidapi-804845236c584c2b/out/libhidapi.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/etc/hidapi/linux`

### Source file examples

* `/work/etc/hidapi/linux/hid.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -Wextra -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
