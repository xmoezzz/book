# `rdkafka-sys` `4.7.0+2.3.0`

Platform: Linux aarch64

## Build-level coding evidence

### pkg-config / pkgconf

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
pkg-config --version
```

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
pkg-config --short-errors --cflags zlib
```

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
pkg-config --short-errors --libs zlib
```

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 477397

Build-script executable: `/target/debug/build/rdkafka-sys-b317c81c2e6d43f1/build_script_build-b317c81c2e6d43f1`

Working directory: `/tmp/crate-build-aarch64-959zsodz/src/rdkafka-sys-4.7.0+2.3.0`

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

#### Linker process 482159

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpeIQWMM.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRGnLg3.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpeIQWMM.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccSQ9UC6.o --trace -Map /tmp/native-trace-link-cc-482053-1783994578664819164.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

* `(__libc_start_main@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482053

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpeIQWMM.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -Wall -Werror _mkltmpeIQWMM.c -o _mkltmpeIQWMM.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -fPIC
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482253

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmp2JWysS.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUUlJTA.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o _mkltmp2JWysS.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/cc3fnS3z.o -soname mkltest.0 --trace -Map /tmp/native-trace-link-cc-482208-1783994578923657990.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482208

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmp2JWysS.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Werror _mkltmp2JWysS.c -o _mkltmp2JWysS.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -shared -Wl,-soname,mkltest.0
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482382

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpxwSlaU.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccP2HZQA.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o _mkltmpxwSlaU.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccRzRCFz.o --version-script=_mkltmpEVUdSK --trace -Map /tmp/native-trace-link-cc-482313-1783994579054222035.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482313

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpxwSlaU.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Werror _mkltmpxwSlaU.c -o _mkltmpxwSlaU.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -shared -Wl,--version-script=_mkltmpEVUdSK
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482483

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpkfilSB.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWOsYLt.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpkfilSB.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccEzfuUs.o --trace -Map /tmp/native-trace-link-cc-482431-1783994579228760642.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

* `(__libc_start_main@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482431

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpkfilSB.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Werror _mkltmpkfilSB.c -o _mkltmpkfilSB.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482581

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpocWi1L.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOKcmTM.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpocWi1L.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccGfVYDL.o --trace -Map /tmp/native-trace-link-cc-482541-1783994579418221341.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

* `(__libc_start_main@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482541

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpocWi1L.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Werror _mkltmpocWi1L.c -o _mkltmpocWi1L.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482711

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpKDVvfR.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdRkY1I.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpKDVvfR.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccMgOawI.o --trace -Map /tmp/native-trace-link-cc-482620-1783994579555629445.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

* `(socket@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482620

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpKDVvfR.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpKDVvfR.c -o _mkltmpKDVvfR.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482816

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpvhHYO7.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccipMr8u.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpvhHYO7.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccDEyvPv.o -lrt --trace -Map /tmp/native-trace-link-cc-482789-1783994579815011118.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482789

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpvhHYO7.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpvhHYO7.c -o _mkltmpvhHYO7.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482913

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmp2KtNWX.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccZfBa2d.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmp2KtNWX.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/cc4wx9Ag.o -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-482877-1783994579975696949.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482877

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmp2KtNWX.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmp2KtNWX.c -o _mkltmp2KtNWX.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483004

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpQuYPfQ.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjTNhOb.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpQuYPfQ.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/cc5awQTa.o -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-482968-1783994580134105467.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(thrd_create@@GLIBC_2.28` (dynamic_library)
* `(__stack_chk_fail@@GLIBC_2.4` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482968

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpQuYPfQ.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpQuYPfQ.c -o _mkltmpQuYPfQ.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483197

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmptmJVWY.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMBPJkV.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmptmJVWY.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccvQ6TBW.o -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483121-1783994580369676054.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(dlclose@@GLIBC_2.2.5` (dynamic_library)
* `(__libc_start_main@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483121

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmptmJVWY.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmptmJVWY.c -o _mkltmptmJVWY.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483312

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmptoDZMj.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpJCGQq.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmptoDZMj.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccFo1r4n.o -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483279-1783994580671629809.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(inflate` (dynamic_library)
* `(write@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `(__libc_start_main@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483279

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmptoDZMj.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmptoDZMj.c -o _mkltmptoDZMj.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483431

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpPH90bZ.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccS4FDeP.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpPH90bZ.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccMxB2fN.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483387-1783994580850664159.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483387

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpPH90bZ.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpPH90bZ.c -o _mkltmpPH90bZ.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483526

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpXIP6Ei.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN9hDMI.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpXIP6Ei.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/cc74IXAI.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483505-1783994581081956480.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__syslog_chk@@GLIBC_2.4` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483505

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpXIP6Ei.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpXIP6Ei.c -o _mkltmpXIP6Ei.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483659

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpzcRqTt.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxU4WeI.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpzcRqTt.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccfSnsBE.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483597-1783994581304035248.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__printf_chk@@GLIBC_2.3.4` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483597

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpzcRqTt.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpzcRqTt.c -o _mkltmpzcRqTt.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483760

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpReRfSw.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoHTOuE.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpReRfSw.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccScfZkH.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483728-1783994581509074310.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(regexec@@GLIBC_2.3.4` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483728

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpReRfSw.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpReRfSw.c -o _mkltmpReRfSw.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483878

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmppBm6MG.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc61CUT7.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmppBm6MG.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/cc79wyL8.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483853-1783994581732949868.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__stack_chk_fail@@GLIBC_2.4` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483853

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmppBm6MG.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmppBm6MG.c -o _mkltmppBm6MG.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483966

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpvMyyMJ.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjaO64u.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpvMyyMJ.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccWdY9Qt.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483919-1783994581906821534.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(strndup@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483919

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpvMyyMJ.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpvMyyMJ.c -o _mkltmpvMyyMJ.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484056

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpezXJMR.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLUOo11.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpezXJMR.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/cc5cF9L2.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484039-1783994582133789623.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__xpg_strerror_r@@GLIBC_2.3.4` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484039

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpezXJMR.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpezXJMR.c -o _mkltmpezXJMR.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484139

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpFsjaw7.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccizyYal.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpFsjaw7.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccGL3ZYk.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484107-1783994582262952670.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(strcasestr@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484107

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpFsjaw7.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpFsjaw7.c -o _mkltmpFsjaw7.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484226

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmppVGNQg.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYFpuvl.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmppVGNQg.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccQ1GBNm.o -lpthread -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484188-1783994582452343588.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(pthread_setname_np@@GLIBC_2.12` (dynamic_library)
* `(pthread_self@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484188

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmppVGNQg.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmppVGNQg.c -o _mkltmppVGNQg.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -D_GNU_SOURCE -lpthread -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484488

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpWpy2bK.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYcSXwC.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpWpy2bK.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccGeDOAy.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484441-1783994582828645763.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__printf_chk@@GLIBC_2.3.4` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484441

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/_mkltmpWpy2bK.c.o`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

```text
cc -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpWpy2bK.c -o _mkltmpWpy2bK.c.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 493193

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/librdkafka.so.1`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJ4rFpe.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o librdkafka.so.1 /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. -soname librdkafka.so.1 --version-script=librdkafka.lds rdkafka.o rdkafka_broker.o rdkafka_msg.o rdkafka_topic.o rdkafka_conf.o rdkafka_timer.o rdkafka_offset.o rdkafka_transport.o rdkafka_buf.o rdkafka_queue.o rdkafka_op.o rdkafka_request.o rdkafka_cgrp.o rdkafka_pattern.o rdkafka_partition.o rdkafka_subscription.o rdkafka_assignment.o rdkafka_assignor.o rdkafka_range_assignor.o rdkafka_roundrobin_assignor.o rdkafka_sticky_assignor.o rdkafka_feature.o rdcrc32.o crc32c.o rdmurmur2.o rdfnv1a.o cJSON.o rdaddr.o rdrand.o rdlist.o tinycthread.o tinycthread_extra.o rdlog.o rdstring.o rdkafka_event.o rdkafka_metadata.o rdregex.o rdports.o rdkafka_metadata_cache.o rdavl.o rdkafka_sasl.o rdkafka_sasl_plain.o rdkafka_interceptor.o rdkafka_msgset_writer.o rdkafka_msgset_reader.o rdkafka_header.o rdkafka_admin.o rdkafka_aux.o rdkafka_background.o rdkafka_idempotence.o rdkafka_cert.o rdkafka_txnmgr.o rdkafka_coord.o rdbase64.o rdvarint.o rdbuf.o rdmap.o rdunittest.o rdkafka_mock.o rdkafka_mock_handlers.o rdkafka_mock_cgrp.o rdkafka_error.o rdkafka_fetcher.o snappy.o rdgz.o rdhdrhistogram.o rdkafka_lz4.o rdxxhash.o lz4.o lz4frame.o lz4hc.o rddl.o rdkafka_plugin.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-493164-1783994616532888693.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 493164

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/librdkafka.so.1`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src`

```text
cc -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -shared -Wl,-soname,librdkafka.so.1 -Wl,--version-script=librdkafka.lds rdkafka.o rdkafka_broker.o rdkafka_msg.o rdkafka_topic.o rdkafka_conf.o rdkafka_timer.o rdkafka_offset.o rdkafka_transport.o rdkafka_buf.o rdkafka_queue.o rdkafka_op.o rdkafka_request.o rdkafka_cgrp.o rdkafka_pattern.o rdkafka_partition.o rdkafka_subscription.o rdkafka_assignment.o rdkafka_assignor.o rdkafka_range_assignor.o rdkafka_roundrobin_assignor.o rdkafka_sticky_assignor.o rdkafka_feature.o rdcrc32.o crc32c.o rdmurmur2.o rdfnv1a.o cJSON.o rdaddr.o rdrand.o rdlist.o tinycthread.o tinycthread_extra.o rdlog.o rdstring.o rdkafka_event.o rdkafka_metadata.o rdregex.o rdports.o rdkafka_metadata_cache.o rdavl.o rdkafka_sasl.o rdkafka_sasl_plain.o rdkafka_interceptor.o rdkafka_msgset_writer.o rdkafka_msgset_reader.o rdkafka_header.o rdkafka_admin.o rdkafka_aux.o rdkafka_background.o rdkafka_idempotence.o rdkafka_cert.o rdkafka_txnmgr.o rdkafka_coord.o rdbase64.o rdvarint.o rdbuf.o rdmap.o rdunittest.o rdkafka_mock.o rdkafka_mock_handlers.o rdkafka_mock_cgrp.o rdkafka_error.o rdkafka_fetcher.o snappy.o rdgz.o rdhdrhistogram.o rdkafka_lz4.o rdxxhash.o lz4.o lz4frame.o lz4hc.o rddl.o rdkafka_plugin.o -o librdkafka.so.1 -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 493563

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/librdkafka++.so.1`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp`

```text
/tmp/native-trace-470765-1783994551746/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdOLViT.res -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o librdkafka++.so.1 /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L../src -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. -soname librdkafka++.so.1 RdKafka.o ConfImpl.o HandleImpl.o ConsumerImpl.o ProducerImpl.o KafkaConsumerImpl.o TopicImpl.o TopicPartitionImpl.o MessageImpl.o HeadersImpl.o QueueImpl.o MetadataImpl.o -lrdkafka --trace -Map /tmp/native-trace-link-c++-493558-1783994618788078663.map -lstdc++ -lm -lgcc_s -lc -lgcc_s /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/../src/librdkafka.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libstdc++.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/../src/librdkafka.so` (dynamic_library)
* `../src/librdkafka.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libstdc++.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 493558

Link output: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/librdkafka++.so.1`

Working directory: `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp`

```text
c++ -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -shared -Wl,-soname,librdkafka++.so.1 RdKafka.o ConfImpl.o HandleImpl.o ConsumerImpl.o ProducerImpl.o KafkaConsumerImpl.o TopicImpl.o TopicPartitionImpl.o MessageImpl.o HeadersImpl.o QueueImpl.o MetadataImpl.o -o librdkafka++.so.1 -L../src -lrdkafka
```

**Linker library inputs**

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/../src/librdkafka.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libstdc++.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/librdkafka++.a`

### Source origin

* under build output directory `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

### Source directories

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp`

### Source file examples

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/ConfImpl.cpp`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/ConsumerImpl.cpp`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/HandleImpl.cpp`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/HeadersImpl.cpp`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/KafkaConsumerImpl.cpp`

### Compilation

```text
c++ -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wno-non-virtual-dtor -c <source> -o <object>
```

### Static library construction

```text
ar rcs <static library> <object files>
```

## `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/librdkafka++.so.1`

### Source origin

* under build output directory `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

### Source directories

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp`

### Source file examples

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/ConfImpl.cpp`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/ConsumerImpl.cpp`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/HandleImpl.cpp`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/HeadersImpl.cpp`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/KafkaConsumerImpl.cpp`

### Compilation

```text
c++ -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wno-non-virtual-dtor -c <source> -o <object>
```

### Native linking

```text
c++ -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -shared <native inputs> -o <native artifact> -L../src -lrdkafka
```

### Linked native libraries

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o (object)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o (object)`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src-cpp/../src/librdkafka.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/libstdc++.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so (dynamic_library)`
* `/lib/x86_64-linux-gnu/libm.so.6 (dynamic_library)`
* `/lib/x86_64-linux-gnu/libmvec.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a (static_library)`

## `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/librdkafka.a`

### Source origin

* under build output directory `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

### Source directories

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src`

### Source file examples

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/cJSON.c`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/crc32c.c`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/lz4.c`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/lz4frame.c`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/lz4hc.c`

### Compilation

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I<include directory> -I<include directory> -I<include directory> -c <source> -o <object>
```

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I<include directory> -I<include directory> -I<include directory> -O3 -c <source> -o <object>
```

### Static library construction

```text
ar rcs <static library> <object files>
```

## `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/librdkafka.so.1`

### Source origin

* under build output directory `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out`

### Source directories

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src`

### Source file examples

* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/cJSON.c`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/crc32c.c`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/lz4.c`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/lz4frame.c`
* `/target/aarch64-unknown-linux-gnu/debug/build/rdkafka-sys-7133559545dcb492/out/src/lz4hc.c`

### Compilation

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I<include directory> -I<include directory> -I<include directory> -c <source> -o <object>
```

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I<include directory> -I<include directory> -I<include directory> -O3 -c <source> -o <object>
```

### Native linking

```text
cc -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -L/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/build -shared <native inputs> -Wl,--version-script=librdkafka.lds -o <native artifact> -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

### Linked native libraries

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o (object)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o (object)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so (dynamic_library)`
* `/lib/x86_64-linux-gnu/libm.so.6 (dynamic_library)`
* `/lib/x86_64-linux-gnu/libmvec.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libz.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libdl.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libpthread.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/librt.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a (static_library)`
