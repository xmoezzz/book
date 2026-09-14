# `sqlite3-parser` `0.12.0`

Platform: Linux aarch64

## Build-level coding evidence

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 881956

Build-script executable: `/target/debug/build/sqlite3-parser-061781c3cbb7eda7/build_script_build-061781c3cbb7eda7`

Working directory: `/tmp/crate-build-aarch64-52fp3t2d/src/sqlite3-parser-0.12.0`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libutil.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

### Other root-owned linker native-library inputs

#### Linker process 881983

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/sqlite3-parser-6425b28518a4a125/out/rlemon`

Working directory: `/tmp/crate-build-aarch64-52fp3t2d/src/sqlite3-parser-0.12.0`

```text
/tmp/native-trace-881547-1783997672877/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccOWXzk.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/aarch64-unknown-linux-gnu/debug/build/sqlite3-parser-6425b28518a4a125/out/rlemon /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccizIGBh.o --trace -Map /tmp/native-trace-link-cc-881978-1783997675532800640.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(exit@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 881978

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/sqlite3-parser-6425b28518a4a125/out/rlemon`

Working directory: `/tmp/crate-build-aarch64-52fp3t2d/src/sqlite3-parser-0.12.0`

```text
cc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/sqlite3-parser-6425b28518a4a125/out/rlemon third_party/lemon/lemon.c
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)
