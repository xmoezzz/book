# `rdkafka-sys` `4.7.0+2.3.0`

Platform: Linux riscv64

## Build-level coding evidence

### Source acquisition

Working directory: `/tmp/crate-build-riscv64-vbhlv5j2/src/rdkafka-sys-4.7.0+2.3.0`

```text
internal_build_script_archive_output
```

Working directory: `/tmp/crate-build-riscv64-vbhlv5j2/src/rdkafka-sys-4.7.0+2.3.0`

```text
internal_build_script_archive_output
```

Working directory: `/tmp/crate-build-riscv64-vbhlv5j2/src/rdkafka-sys-4.7.0+2.3.0`

```text
internal_build_script_archive_output
```

Working directory: `/tmp/crate-build-riscv64-vbhlv5j2/src/rdkafka-sys-4.7.0+2.3.0`

```text
internal_build_script_archive_output
```

### pkg-config / pkgconf

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
pkg-config --version
```

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
pkg-config --short-errors --cflags zlib
```

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
pkg-config --short-errors --libs zlib
```

### Build-script executable native dependencies

#### Linker process 478100

Build-script executable: `/target/debug/build/rdkafka-sys-b317c81c2e6d43f1/build_script_build-b317c81c2e6d43f1`

Working directory: `/tmp/crate-build-riscv64-vbhlv5j2/src/rdkafka-sys-4.7.0+2.3.0`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

### Other root-owned linker native-library inputs

#### Linker process 482813

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmp7xE4WH.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3Da1WE.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmp7xE4WH.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccWHudBE.o --trace -Map /tmp/native-trace-link-cc-482747-1783994579731020010.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482747

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmp7xE4WH.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -Wall -Werror _mkltmp7xE4WH.c -o _mkltmp7xE4WH.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -fPIC
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482881

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpsnCden.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctKgu5y.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o _mkltmpsnCden.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccyLofoH.o -soname mkltest.0 --trace -Map /tmp/native-trace-link-cc-482847-1783994579938957409.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482847

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpsnCden.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Werror _mkltmpsnCden.c -o _mkltmpsnCden.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -shared -Wl,-soname,mkltest.0
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482964

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpnPfrZf.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMdTzFL.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o _mkltmpnPfrZf.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccQvSc0K.o --version-script=_mkltmpmdS5vV --trace -Map /tmp/native-trace-link-cc-482936-1783994580085266330.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 482936

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpnPfrZf.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Werror _mkltmpnPfrZf.c -o _mkltmpnPfrZf.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -shared -Wl,--version-script=_mkltmpmdS5vV
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483078

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpq0eqRv.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccw6rOo5.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpq0eqRv.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/cc5zW6XJ.o --trace -Map /tmp/native-trace-link-cc-483022-1783994580208744963.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483022

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpq0eqRv.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Werror _mkltmpq0eqRv.c -o _mkltmpq0eqRv.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483229

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpGJMExg.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJnHNqO.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpGJMExg.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccokIhbQ.o --trace -Map /tmp/native-trace-link-cc-483160-1783994580386539919.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483160

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpGJMExg.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Werror _mkltmpGJMExg.c -o _mkltmpGJMExg.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483349

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpCptmLt.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu91Y6t.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpCptmLt.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccDtEHA2.o --trace -Map /tmp/native-trace-link-cc-483302-1783994580694389764.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483302

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpCptmLt.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpCptmLt.c -o _mkltmpCptmLt.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483472

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpxaChlc.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTJaU2H.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpxaChlc.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccdZLgly.o -lrt --trace -Map /tmp/native-trace-link-cc-483433-1783994580929010880.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483433

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpxaChlc.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpxaChlc.c -o _mkltmpxaChlc.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483577

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpI2mDO4.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSyf3yV.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpI2mDO4.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccydXtxX.o -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483536-1783994581154911667.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483536

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpI2mDO4.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpI2mDO4.c -o _mkltmpI2mDO4.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483703

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmphpGIPm.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuHvU1E.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmphpGIPm.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccl1lzJ0.o -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483638-1783994581373254987.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(thrd_create@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483638

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmphpGIPm.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmphpGIPm.c -o _mkltmphpGIPm.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483793

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpEt1tFi.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2pFlaz.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpEt1tFi.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/cckU9MNB.o -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483768-1783994581575591860.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483768

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpEt1tFi.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpEt1tFi.c -o _mkltmpEt1tFi.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483877

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpKgDs8c.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPqM11M.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpKgDs8c.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccGQykMH.o -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483867-1783994581752917596.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(inflate` (dynamic_library)
* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483867

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpKgDs8c.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpKgDs8c.c -o _mkltmpKgDs8c.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483960

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpB46hcQ.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc8FC05H.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpB46hcQ.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/cc28FLRL.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-483922-1783994581898797261.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 483922

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpB46hcQ.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpB46hcQ.c -o _mkltmpB46hcQ.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484043

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpNlxZWn.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cczOtQ2x.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpNlxZWn.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccSv4Wls.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484003-1783994582074264410.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484003

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpNlxZWn.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpNlxZWn.c -o _mkltmpNlxZWn.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484160

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpmeTzjS.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMYtkzl.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpmeTzjS.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccLApdZB.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484147-1783994582331062798.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__printf_chk@@GLIBC_2.3.4` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484147

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpmeTzjS.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpmeTzjS.c -o _mkltmpmeTzjS.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484234

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpAdSseT.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccIhnAs.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpAdSseT.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/cc43sQXM.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484217-1783994582482089308.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(regcomp@@GLIBC_2.2.5` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484217

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpAdSseT.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpAdSseT.c -o _mkltmpAdSseT.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484355

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpFbWCc7.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccPdihOI.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpFbWCc7.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccLwg5C9.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484281-1783994582605872183.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484281

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpFbWCc7.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpFbWCc7.c -o _mkltmpFbWCc7.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484539

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpCG49ON.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc8RoE17.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpCG49ON.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccz37OqN.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484460-1783994582881880416.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484460

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpCG49ON.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpCG49ON.c -o _mkltmpCG49ON.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484763

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpBrbQl6.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cci0OVxP.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpBrbQl6.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccpDCtkV.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484666-1783994583194710313.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484666

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpBrbQl6.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpBrbQl6.c -o _mkltmpBrbQl6.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484899

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmp8XvoDf.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWRjjz5.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmp8XvoDf.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccuICb7v.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484829-1783994583330716447.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__libc_start_main@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484829

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmp8XvoDf.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmp8XvoDf.c -o _mkltmp8XvoDf.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484961

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpaqoeT1.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdYFFDm.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpaqoeT1.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/ccuFwEuD.o -lpthread -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-484942-1783994583533091132.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(pthread_setname_np@@GLIBC_2.34` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 484942

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpaqoeT1.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpaqoeT1.c -o _mkltmpaqoeT1.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -D_GNU_SOURCE -lpthread -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 485046

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpaAGHJw.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccidyugc.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o _mkltmpaAGHJw.c.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. /tmp/cctCyaUb.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-485010-1783994583728102193.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `(__printf_chk@@GLIBC_2.3.4` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 485010

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/_mkltmpaAGHJw.c.o`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

```text
cc -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wall -Werror _mkltmpaAGHJw.c -o _mkltmpaAGHJw.c.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 492740

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/librdkafka.so.1`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9CkFqF.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o librdkafka.so.1 /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. -soname librdkafka.so.1 --version-script=librdkafka.lds rdkafka.o rdkafka_broker.o rdkafka_msg.o rdkafka_topic.o rdkafka_conf.o rdkafka_timer.o rdkafka_offset.o rdkafka_transport.o rdkafka_buf.o rdkafka_queue.o rdkafka_op.o rdkafka_request.o rdkafka_cgrp.o rdkafka_pattern.o rdkafka_partition.o rdkafka_subscription.o rdkafka_assignment.o rdkafka_assignor.o rdkafka_range_assignor.o rdkafka_roundrobin_assignor.o rdkafka_sticky_assignor.o rdkafka_feature.o rdcrc32.o crc32c.o rdmurmur2.o rdfnv1a.o cJSON.o rdaddr.o rdrand.o rdlist.o tinycthread.o tinycthread_extra.o rdlog.o rdstring.o rdkafka_event.o rdkafka_metadata.o rdregex.o rdports.o rdkafka_metadata_cache.o rdavl.o rdkafka_sasl.o rdkafka_sasl_plain.o rdkafka_interceptor.o rdkafka_msgset_writer.o rdkafka_msgset_reader.o rdkafka_header.o rdkafka_admin.o rdkafka_aux.o rdkafka_background.o rdkafka_idempotence.o rdkafka_cert.o rdkafka_txnmgr.o rdkafka_coord.o rdbase64.o rdvarint.o rdbuf.o rdmap.o rdunittest.o rdkafka_mock.o rdkafka_mock_handlers.o rdkafka_mock_cgrp.o rdkafka_error.o rdkafka_fetcher.o snappy.o rdgz.o rdhdrhistogram.o rdkafka_lz4.o rdxxhash.o lz4.o lz4frame.o lz4hc.o rddl.o rdkafka_plugin.o -lm -lz -ldl -lpthread -lrt -lpthread -lrt --trace -Map /tmp/native-trace-link-cc-492735-1783994614783536820.map -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 492735

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/librdkafka.so.1`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src`

```text
cc -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -shared -Wl,-soname,librdkafka.so.1 -Wl,--version-script=librdkafka.lds rdkafka.o rdkafka_broker.o rdkafka_msg.o rdkafka_topic.o rdkafka_conf.o rdkafka_timer.o rdkafka_offset.o rdkafka_transport.o rdkafka_buf.o rdkafka_queue.o rdkafka_op.o rdkafka_request.o rdkafka_cgrp.o rdkafka_pattern.o rdkafka_partition.o rdkafka_subscription.o rdkafka_assignment.o rdkafka_assignor.o rdkafka_range_assignor.o rdkafka_roundrobin_assignor.o rdkafka_sticky_assignor.o rdkafka_feature.o rdcrc32.o crc32c.o rdmurmur2.o rdfnv1a.o cJSON.o rdaddr.o rdrand.o rdlist.o tinycthread.o tinycthread_extra.o rdlog.o rdstring.o rdkafka_event.o rdkafka_metadata.o rdregex.o rdports.o rdkafka_metadata_cache.o rdavl.o rdkafka_sasl.o rdkafka_sasl_plain.o rdkafka_interceptor.o rdkafka_msgset_writer.o rdkafka_msgset_reader.o rdkafka_header.o rdkafka_admin.o rdkafka_aux.o rdkafka_background.o rdkafka_idempotence.o rdkafka_cert.o rdkafka_txnmgr.o rdkafka_coord.o rdbase64.o rdvarint.o rdbuf.o rdmap.o rdunittest.o rdkafka_mock.o rdkafka_mock_handlers.o rdkafka_mock_cgrp.o rdkafka_error.o rdkafka_fetcher.o snappy.o rdgz.o rdhdrhistogram.o rdkafka_lz4.o rdxxhash.o lz4.o lz4frame.o lz4hc.o rddl.o rdkafka_plugin.o -o librdkafka.so.1 -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 492910

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/librdkafka++.so.1`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp`

```text
/tmp/native-trace-473425-1783994555071/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccag0y9j.res -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o librdkafka++.so.1 /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L../src -L/usr/lib/gcc/x86_64-linux-gnu/11 -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/11/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/11/../../.. -soname librdkafka++.so.1 RdKafka.o ConfImpl.o HandleImpl.o ConsumerImpl.o ProducerImpl.o KafkaConsumerImpl.o TopicImpl.o TopicPartitionImpl.o MessageImpl.o HeadersImpl.o QueueImpl.o MetadataImpl.o -lrdkafka --trace -Map /tmp/native-trace-link-c++-492899-1783994616243423147.map -lstdc++ -lm -lgcc_s -lc -lgcc_s /usr/lib/gcc/x86_64-linux-gnu/11/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crtn.o
```

**Linker library inputs**

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/../src/librdkafka.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libstdc++.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

**Resolved dynamic-library entries**

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/../src/librdkafka.so` (dynamic_library)
* `../src/librdkafka.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libstdc++.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

#### Linker process 492899

Link output: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/librdkafka++.so.1`

Working directory: `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp`

```text
c++ -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -shared -Wl,-soname,librdkafka++.so.1 RdKafka.o ConfImpl.o HandleImpl.o ConsumerImpl.o ProducerImpl.o KafkaConsumerImpl.o TopicImpl.o TopicPartitionImpl.o MessageImpl.o HeadersImpl.o QueueImpl.o MetadataImpl.o -o librdkafka++.so.1 -L../src -lrdkafka
```

**Linker library inputs**

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/../src/librdkafka.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libstdc++.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a` (static_library)
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libc.so` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/usr/lib/x86_64-linux-gnu/libc_nonshared.a` (static_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/librdkafka++.a`

### Source origin

* under build output directory `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

### Source directories

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp`

### Source file examples

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/ConfImpl.cpp`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/ConsumerImpl.cpp`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/HandleImpl.cpp`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/HeadersImpl.cpp`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/KafkaConsumerImpl.cpp`

### Compilation

```text
c++ -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wno-non-virtual-dtor -c <source> -o <object>
```

### Static library construction

```text
ar rcs <static library> <object files>
```

## `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/librdkafka++.so.1`

### Source origin

* under build output directory `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

### Source directories

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp`

### Source file examples

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/ConfImpl.cpp`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/ConsumerImpl.cpp`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/HandleImpl.cpp`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/HeadersImpl.cpp`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/KafkaConsumerImpl.cpp`

### Compilation

```text
c++ -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -Wno-non-virtual-dtor -c <source> -o <object>
```

### Native linking

```text
c++ -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -shared <native inputs> -o <native artifact> -L../src -lrdkafka
```

### Linked native libraries

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o (object)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o (object)`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src-cpp/../src/librdkafka.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/libstdc++.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so (dynamic_library)`
* `/lib/x86_64-linux-gnu/libm.so.6 (dynamic_library)`
* `/lib/x86_64-linux-gnu/libmvec.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc_s.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libgcc_s.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a (static_library)`

## `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/librdkafka.a`

### Source origin

* under build output directory `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

### Source directories

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src`

### Source file examples

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/cJSON.c`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/crc32c.c`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/lz4.c`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/lz4frame.c`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/lz4hc.c`

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

## `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/librdkafka.so.1`

### Source origin

* under build output directory `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out`

### Source directories

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src`

### Source file examples

* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/cJSON.c`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/crc32c.c`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/lz4.c`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/lz4frame.c`
* `/target/riscv64gc-unknown-linux-gnu/debug/build/rdkafka-sys-6787da11a21e3edd/out/src/lz4hc.c`

### Compilation

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I<include directory> -I<include directory> -I<include directory> -c <source> -o <object>
```

```text
cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I<include directory> -I<include directory> -I<include directory> -O3 -c <source> -o <object>
```

### Native linking

```text
cc -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -L/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/build -shared <native inputs> -Wl,--version-script=librdkafka.lds -o <native artifact> -lm -lz -ldl -lpthread -lrt -lpthread -lrt
```

### Linked native libraries

* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o (object)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o (object)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libm.so (dynamic_library)`
* `/lib/x86_64-linux-gnu/libm.so.6 (dynamic_library)`
* `/lib/x86_64-linux-gnu/libmvec.so.1 (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libz.so (dynamic_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libdl.a (static_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/libpthread.a (static_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/librt.a (static_library)`
* `/usr/lib/gcc/x86_64-linux-gnu/11/libgcc.a (static_library)`
