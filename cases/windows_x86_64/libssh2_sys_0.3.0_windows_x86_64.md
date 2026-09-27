# `libssh2-sys` `0.3.0`

Platform: Windows x86_64

## Submodule

Repository: `https://github.com/alexcrichton/ssh2-rs`
Crate release commit: `346c27a25890e54aca0eb9fcbf9113cbd4692bab`
Commit evidence: published crate `.cargo_vcs_info.json`
Crate source directory in repository: `libssh2-sys`
Repository-level submodule paths (relative to the repository root):
A listed path is a Git submodule link at this commit; this alone does not show whether the published crate or study build fetched or used it.

- `libssh2-sys/libssh2`

## Build-level coding evidence

### Source acquisition

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0`

```text
git submodule update --init
```

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/target/debug/build/libssh2-sys-f82558fc55df8c19/out/build/libssh2.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src/agent.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src/agent_win.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src/bcrypt_pbkdf.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src/blowfish.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-9lb_p4lz/src/libssh2-sys-0.3.0/libssh2/src/channel.c`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -I <include directory> -I <include directory> -I <include directory> -W0 -DHAVE_LONGLONG -DLIBSSH2_WIN32 -DLIBSSH2_WINCNG -DLIBSSH2_DH_GEX_NEW -DLIBSSH2_HAVE_ZLIB -DLIBSSH2DEBUG <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
