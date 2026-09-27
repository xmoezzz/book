# `apriltag-sys` `0.3.0`

Platform: Linux aarch64

## Submodule

Repository: `https://github.com/jerry73204/apriltag-rust.git`
Crate release commit: `70d84e3237362e6140f5a13485a565411f9cec4a`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `apriltag-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `apriltag-sys/apriltag-src`

## `/target/aarch64-unknown-linux-gnu/debug/build/apriltag-sys-b0d9b762630146c2/out/libapriltags.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0`

### Source directories

* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src`
* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/common`

### Source file examples

* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/apriltag.c`
* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/apriltag_pose.c`
* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/apriltag_quad_thresh.c`
* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/common/unionfind.c`
* `/tmp/crate-build-aarch64-5ifarqng/src/apriltag-sys-0.3.0/apriltag-src/common/workerpool.c`

### Compilation

```text
cc1 -quiet -I <include directory> -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O0 -Wall -ffunction-sections -fdata-sections ...
```

```text
gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I <include directory> -Wall -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
