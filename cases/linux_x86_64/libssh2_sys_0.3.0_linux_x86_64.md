# `libssh2-sys` `0.3.0`

Platform: Linux x86_64

## Build-level coding evidence

### Network / source acquisition activity

Working directory: `/work`

```text
git submodule update --init
```

Acquisition kind: `git_submodule`

Outcome: failed (exit code 128)

Working directory: `/work`

```text
/usr/bin/git submodule update --init
```

Outcome: outcome unavailable in trace

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1887730

Build-script executable: `/work/target/debug/build/libssh2-sys-f50cf38e5cb89728/build_script_build-f50cf38e5cb89728`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/libssh2-sys-bc9cae7ae982df81/out/build/libssh2.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/libssh2/src`

### Source file examples

* `/work/libssh2/src/agent.c`
* `/work/libssh2/src/bcrypt_pbkdf.c`
* `/work/libssh2/src/blowfish.c`
* `/work/libssh2/src/channel.c`
* `/work/libssh2/src/comp.c`

### Compilation

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -w -fvisibility=hidden -DHAVE_LONGLONG -DHAVE_SNPRINTF -DHAVE_UNISTD_H -DHAVE_INTTYPES_H -DHAVE_STDLIB_H -DHAVE_SYS_SELECT_H -DHAVE_SYS_SOCKET_H -DHAVE_SYS_IOCTL_H -DHAVE_SYS_TIME_H -DHAVE_SYS_UN_H -DHAVE_O_NONBLOCK -DLIBSSH2_OPENSSL -DHAVE_LIBCRYPT32 -DHAVE_EVP_AES_128_CTR -DHAVE_POLL -DHAVE_GETTIMEOFDAY -DLIBSSH2_DH_GEX_NEW -DLIBSSH2_HAVE_ZLIB -DLIBSSH2DEBUG -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
