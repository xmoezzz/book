# `rdkafka-sys` `4.7.0+2.3.0`

Platform: Linux ppc64le

## Build-level coding evidence

### Network / source acquisition activity

Working directory: `/tmp/crate-build-ppc64le-1sqyz6um/src/rdkafka-sys-4.7.0+2.3.0`

```text
internal_build_script_archive_output
```

Acquisition kind: `internal_build_script_archive_output`

Outcome: succeeded

Working directory: `/tmp/crate-build-ppc64le-1sqyz6um/src/rdkafka-sys-4.7.0+2.3.0`

```text
internal_build_script_archive_output
```

Acquisition kind: `internal_build_script_archive_output`

Outcome: succeeded

Working directory: `/tmp/crate-build-ppc64le-1sqyz6um/src/rdkafka-sys-4.7.0+2.3.0`

```text
internal_build_script_archive_output
```

Acquisition kind: `internal_build_script_archive_output`

Outcome: succeeded

Working directory: `/tmp/crate-build-ppc64le-1sqyz6um/src/rdkafka-sys-4.7.0+2.3.0`

```text
internal_build_script_archive_output
```

Acquisition kind: `internal_build_script_archive_output`

Outcome: succeeded

### pkg-config / pkgconf

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
pkg-config --version
```

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
pkg-config --short-errors --cflags zlib
```

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
pkg-config --short-errors --libs zlib
```

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 478185

Build-script executable: `/target/debug/build/rdkafka-sys-b317c81c2e6d43f1/build_script_build-b317c81c2e6d43f1`

Working directory: `/tmp/crate-build-ppc64le-1sqyz6um/src/rdkafka-sys-4.7.0+2.3.0`

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

#### Linker process 483194

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpnI1448.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIjN43R.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpnI1448.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccRIAAdS.o --trace -Map /tmp/native-trace-link-cc-483096-1783994580282408769.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 483096

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpnI1448.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -Wall -Werror _mkltmpnI1448.c -o _mkltmpnI1448.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -fPIC
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483392

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpAf83cg.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCfd9K0.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o _mkltmpAf83cg.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccjAPzQX.o -soname mkltest.0 --trace -Map /tmp/native-trace-link-cc-483357-1783994580813070788.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 483357

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpAf83cg.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Werror _mkltmpAf83cg.c -o _mkltmpAf83cg.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -shared -Wl,-soname,mkltest.0
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483513

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmp4OW6u2.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cckzs1XQ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o _mkltmp4OW6u2.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccVS237O.o --version-script=_mkltmpO7mc3z --trace -Map /tmp/native-trace-link-cc-483492-1783994581034130393.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 483492

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmp4OW6u2.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Werror _mkltmp4OW6u2.c -o _mkltmp4OW6u2.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -shared -Wl,--version-script=_mkltmpO7mc3z
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483585

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpF92FXC.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqcwmJv.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpF92FXC.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccgPmg3t.o --trace -Map /tmp/native-trace-link-cc-483556-1783994581200335527.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 483556

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpF92FXC.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Werror _mkltmpF92FXC.c -o _mkltmpF92FXC.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483699

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpOZEnWJ.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRQAqwu.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpOZEnWJ.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccZteQqw.o --trace -Map /tmp/native-trace-link-cc-483675-1783994581387090150.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 483675

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpOZEnWJ.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Werror _mkltmpOZEnWJ.c -o _mkltmpOZEnWJ.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483781

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpRMI1q1.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7B45JI.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpRMI1q1.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccPj2CwI.o --trace -Map /tmp/native-trace-link-cc-483743-1783994581529032790.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 483743

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpRMI1q1.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpRMI1q1.c -o _mkltmpRMI1q1.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib/x86_64-linux-gnu/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483882

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpvChEjH.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4s7Y8a.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpvChEjH.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccJR5DOc.o -lrt --trace -Map /tmp/native-trace-link-cc-483850-1783994581734558406.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 483850

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpvChEjH.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpvChEjH.c -o _mkltmpvChEjH.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lrt
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

#### Linker process 483972

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpjKJgBX.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccE6N6N.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpjKJgBX.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccZvvU7N.o -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483957-1783994581956816139.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 483957

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpjKJgBX.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpjKJgBX.c -o _mkltmpjKJgBX.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lpthread -lrt
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

#### Linker process 484051

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpEWh5YZ.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5D4ICC.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpEWh5YZ.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccLMYMsC.o -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484020-1783994582101784485.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 484020

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpEWh5YZ.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpEWh5YZ.c -o _mkltmpEWh5YZ.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lpthread -lrt -lpthread -lrt
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

#### Linker process 484157

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpmycX8G.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cceTnQbE.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpmycX8G.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccQD1C4A.o -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484126-1783994582290645269.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 484126

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpmycX8G.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpmycX8G.c -o _mkltmpmycX8G.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 484317

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmp3xP6Uo.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch4bW6p.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmp3xP6Uo.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccZ43ZLp.o -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484255-1783994582560012084.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 484255

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmp3xP6Uo.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmp3xP6Uo.c -o _mkltmp3xP6Uo.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 484511

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpgYZMsW.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBZiLWF.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpgYZMsW.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccURI27D.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484429-1783994582820994671.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 484429

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpgYZMsW.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpgYZMsW.c -o _mkltmpgYZMsW.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 484646

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpn9187E.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbBhYCL.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpn9187E.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccNj470L.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484576-1783994583084410793.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 484576

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpn9187E.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpn9187E.c -o _mkltmpn9187E.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 484893

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpmNYWEa.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqdseMi.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpmNYWEa.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccQXzxXf.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484862-1783994583360665449.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 484862

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpmNYWEa.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpmNYWEa.c -o _mkltmpmNYWEa.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 484948

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpZ381k5.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqxAsQw.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpZ381k5.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/cc5alp8t.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484918-1783994583495974364.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 484918

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpZ381k5.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpZ381k5.c -o _mkltmpZ381k5.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 485019

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpxRFh9S.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsiAEDh.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpxRFh9S.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccvQ7vbf.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484981-1783994583641149098.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 484981

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpxRFh9S.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpxRFh9S.c -o _mkltmpxRFh9S.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 485149

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpHxiUXK.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclvHFLV.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpHxiUXK.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccW97JZX.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-485096-1783994583925860948.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 485096

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpHxiUXK.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpHxiUXK.c -o _mkltmpHxiUXK.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 485314

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmp7TKgnH.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5sovPU.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmp7TKgnH.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/cccoEWtR.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-485266-1783994584235656594.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 485266

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmp7TKgnH.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmp7TKgnH.c -o _mkltmp7TKgnH.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 485358

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpJIkK48.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccGWbaR.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpJIkK48.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/cc987soR.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-485346-1783994584461694117.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 485346

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpJIkK48.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpJIkK48.c -o _mkltmpJIkK48.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 485402

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpO1pHJk.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccCkq0cf.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpO1pHJk.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccVyvqRa.o -lpthread -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-485375-1783994584585266537.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 485375

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpO1pHJk.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpO1pHJk.c -o _mkltmpO1pHJk.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -D_GNU_SOURCE -lpthread -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 485480

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpDHPDLj.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccF3aA9y.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpDHPDLj.c.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. /tmp/ccQ7Nw5A.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-485448-1783994584775003765.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 485448

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/_mkltmpDHPDLj.c.o`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

```text
cc -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpDHPDLj.c -o _mkltmpDHPDLj.c.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 492955

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/librdkafka.so.1`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRxhufQ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o librdkafka.so.1 /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. -soname librdkafka.so.1 --version-script=librdkafka.lds rdkafka.o rdkafka_broker.o rdkafka_msg.o rdkafka_topic.o rdkafka_conf.o rdkafka_timer.o rdkafka_offset.o rdkafka_transport.o rdkafka_buf.o rdkafka_queue.o rdkafka_op.o rdkafka_request.o rdkafka_cgrp.o rdkafka_pattern.o rdkafka_partition.o rdkafka_subscription.o rdkafka_assignment.o rdkafka_assignor.o rdkafka_range_assignor.o rdkafka_roundrobin_assignor.o rdkafka_sticky_assignor.o rdkafka_feature.o rdcrc32.o crc32c.o rdmurmur2.o rdfnv1a.o cJSON.o rdaddr.o rdrand.o rdlist.o tinycthread.o tinycthread_extra.o rdlog.o rdstring.o rdkafka_event.o rdkafka_metadata.o rdregex.o rdports.o rdkafka_metadata_cache.o rdavl.o rdkafka_sasl.o rdkafka_sasl_plain.o rdkafka_interceptor.o rdkafka_msgset_writer.o rdkafka_msgset_reader.o rdkafka_header.o rdkafka_admin.o rdkafka_aux.o rdkafka_background.o rdkafka_idempotence.o rdkafka_cert.o rdkafka_txnmgr.o rdkafka_coord.o rdbase64.o rdvarint.o rdbuf.o rdmap.o rdunittest.o rdkafka_mock.o rdkafka_mock_handlers.o rdkafka_mock_cgrp.o rdkafka_error.o rdkafka_fetcher.o snappy.o rdgz.o rdhdrhistogram.o rdkafka_lz4.o rdxxhash.o lz4.o lz4frame.o lz4hc.o rddl.o rdkafka_plugin.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-492949-1783994616272409687.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
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

#### Linker process 492949

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/librdkafka.so.1`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src`

```text
cc -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -shared -Wl,-soname,librdkafka.so.1 -Wl,--version-script=librdkafka.lds rdkafka.o rdkafka_broker.o rdkafka_msg.o rdkafka_topic.o rdkafka_conf.o rdkafka_timer.o rdkafka_offset.o rdkafka_transport.o rdkafka_buf.o rdkafka_queue.o rdkafka_op.o rdkafka_request.o rdkafka_cgrp.o rdkafka_pattern.o rdkafka_partition.o rdkafka_subscription.o rdkafka_assignment.o rdkafka_assignor.o rdkafka_range_assignor.o rdkafka_roundrobin_assignor.o rdkafka_sticky_assignor.o rdkafka_feature.o rdcrc32.o crc32c.o rdmurmur2.o rdfnv1a.o cJSON.o rdaddr.o rdrand.o rdlist.o tinycthread.o tinycthread_extra.o rdlog.o rdstring.o rdkafka_event.o rdkafka_metadata.o rdregex.o rdports.o rdkafka_metadata_cache.o rdavl.o rdkafka_sasl.o rdkafka_sasl_plain.o rdkafka_interceptor.o rdkafka_msgset_writer.o rdkafka_msgset_reader.o rdkafka_header.o rdkafka_admin.o rdkafka_aux.o rdkafka_background.o rdkafka_idempotence.o rdkafka_cert.o rdkafka_txnmgr.o rdkafka_coord.o rdbase64.o rdvarint.o rdbuf.o rdmap.o rdunittest.o rdkafka_mock.o rdkafka_mock_handlers.o rdkafka_mock_cgrp.o rdkafka_error.o rdkafka_fetcher.o snappy.o rdgz.o rdhdrhistogram.o rdkafka_lz4.o rdxxhash.o lz4.o lz4frame.o lz4hc.o rddl.o rdkafka_plugin.o -o librdkafka.so.1 -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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

#### Linker process 493537

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/librdkafka++.so.1`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp`

```text
/tmp/native-trace-473283-1783994554865/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuC5LZT.res -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o librdkafka++.so.1 /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L../src -L/usr/lib/gcc/x86_64-linux-gnu/9 -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/9/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/9/../../.. -soname librdkafka++.so.1 RdKafka.o ConfImpl.o HandleImpl.o ConsumerImpl.o ProducerImpl.o KafkaConsumerImpl.o TopicImpl.o TopicPartitionImpl.o MessageImpl.o HeadersImpl.o QueueImpl.o MetadataImpl.o -lrdkafka --trace -Map /tmp/native-trace-link-c++-493532-1783994618497901497.map -lstdc++ -lm -lgcc_s -lc -lgcc_s /usr/lib/gcc/x86_64-linux-gnu/9/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/../src/librdkafka.so` (dynamic_library)
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

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/../src/librdkafka.so` (dynamic_library)
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

#### Linker process 493532

Link output: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/librdkafka++.so.1`

Working directory: `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp`

```text
c++ -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -shared -Wl,-soname,librdkafka++.so.1 RdKafka.o ConfImpl.o HandleImpl.o ConsumerImpl.o ProducerImpl.o KafkaConsumerImpl.o TopicImpl.o TopicPartitionImpl.o MessageImpl.o HeadersImpl.o QueueImpl.o MetadataImpl.o -o librdkafka++.so.1 -L../src -lrdkafka
```

**Linker library inputs**

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/../src/librdkafka.so` (dynamic_library)
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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/librdkafka++.a`

### Source origin

* under build output directory `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

### Source directories

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp`

### Source file examples

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/ConfImpl.cpp`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/ConsumerImpl.cpp`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/HandleImpl.cpp`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/HeadersImpl.cpp`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/KafkaConsumerImpl.cpp`

### Compilation

```text
c++ -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wno-non-virtual-dtor -c <source> -o <object>
```

### Static library construction

```text
ar rcs <static library> <object files>
```

## `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/librdkafka++.so.1`

### Source origin

* under build output directory `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

### Source directories

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp`

### Source file examples

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/ConfImpl.cpp`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/ConsumerImpl.cpp`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/HandleImpl.cpp`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/HeadersImpl.cpp`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/KafkaConsumerImpl.cpp`

### Compilation

```text
c++ -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wno-non-virtual-dtor -c <source> -o <object>
```

### Native linking

```text
c++ -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -shared <native inputs> -o <native artifact> -L../src -lrdkafka
```

### Linked native libraries

* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o (object)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o (object)`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src-cpp/../src/librdkafka.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/libstdc++.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libm.so (dynamic_library)`
* `/lib/x86_64-linux-gnu/libm.so.6 (dynamic_library)`
* `/lib/x86_64-linux-gnu/libmvec.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc_s.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/libgcc_s.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/9/libgcc.a (static_library)`

## `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/librdkafka.a`

### Source origin

* under build output directory `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

### Source directories

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src`

### Source file examples

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/cJSON.c`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/crc32c.c`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/lz4.c`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/lz4frame.c`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/lz4hc.c`

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

## `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/librdkafka.so.1`

### Source origin

* under build output directory `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out`

### Source directories

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src`

### Source file examples

* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/cJSON.c`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/crc32c.c`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/lz4.c`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/lz4frame.c`
* `/target/powerpc64le-unknown-linux-gnu/debug/build/rdkafka-sys-e02825183b382499/out/src/lz4hc.c`

### Compilation

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I<include directory> -I<include directory> -I<include directory> -c <source> -o <object>
```

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I<include directory> -I<include directory> -I<include directory> -O3 -c <source> -o <object>
```

### Native linking

```text
cc -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -L/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/build -shared <native inputs> -Wl,--version-script=librdkafka.lds -o <native artifact> -lm -lz -ldl -lpthread -lrt -lpthread -lrt
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
