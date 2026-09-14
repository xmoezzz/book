# `libudev-sys` `0.1.4`

Platform: Linux x86_64

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

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 1867287

Build-script executable: `/work/target/debug/build/libudev-sys-543ec4092d1cb386/build_script_build-543ec4092d1cb386`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

### Other root-owned linker native-library inputs

#### Linker process 1867343

Link output: `/work/target/debug/build/libudev-sys-b431cd0168440ed2/out/check_udev_hwdb_new`

Working directory: `/work`

```text
cc -m64 /work/target/debug/build/libudev-sys-b431cd0168440ed2/out/rustcZOsH7h/symbols.o /work/target/debug/build/libudev-sys-b431cd0168440ed2/out/check_udev_hwdb_new.check_udev_hwdb_new.2e522517000b5984-cgu.0.rcgu.o /work/target/debug/build/libudev-sys-b431cd0168440ed2/out/check_udev_hwdb_new.535yzp58ev3il9175twv9yz20.rcgu.o -Wl,--as-needed -Wl,-Bdynamic -ludev -Wl,-Bstatic /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-46d936097e8c5b85.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-e462f106b2b26a06.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-926daa94a00ee327.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-48d5b0db80402653.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-3367f26bd486b29d.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-7aeefe72516b1ebd.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-a5addfdc94c3bad3.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-789fb9c0cb1c7158.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-b16e5cb5eba3e0fd.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-70305b2ec0766fa6.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-76b5fe9328c1063f.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-2b6a8d2f6e1dc71b.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-39ffdbc27c978ccc.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-353b2c7de9775880.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-6036bb7ab2db827f.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-43aaa5c9542afd99.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-c99e676976f4dcce.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-e60dd2ab51fbc7de.rlib /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-58c8d4715a55733a.rlib -Wl,-Bdynamic -lgcc_s -lutil -lrt -lpthread -lm -ldl -lc -L /work/target/debug/build/libudev-sys-b431cd0168440ed2/out/rustcZOsH7h/raw-dylibs -B/usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld -fuse-ld=lld -Wl,--eh-frame-hdr -Wl,-z,noexecstack -L /usr/local/rustup/toolchains/1.94.1-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib -o /work/target/debug/build/libudev-sys-b431cd0168440ed2/out/check_udev_hwdb_new -Wl,--gc-sections -pie -Wl,-z,relro,-z,now -nodefaultlibs
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libudev.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)
