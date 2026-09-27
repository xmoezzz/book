# `apriltag-sys` `0.3.0`

Platform: Linux x86_64

## Submodule

Repository: `https://github.com/jerry73204/apriltag-rust.git`
Crate release commit: `70d84e3237362e6140f5a13485a565411f9cec4a`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `apriltag-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `apriltag-sys/apriltag-src`

## `/work/target/debug/build/apriltag-sys-994878befa074a2f/out/libapriltags.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/apriltag-src`
* `/work/apriltag-src/common`

### Source file examples

* `/work/apriltag-src/apriltag.c`
* `/work/apriltag-src/apriltag_pose.c`
* `/work/apriltag-src/apriltag_quad_thresh.c`
* `/work/apriltag-src/common/g2d.c`
* `/work/apriltag-src/common/getopt.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -Wall -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
