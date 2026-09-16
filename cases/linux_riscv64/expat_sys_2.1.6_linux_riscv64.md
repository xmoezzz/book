# `expat-sys` `2.1.6`

Platform: Linux riscv64

## `libexpat.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6`

### Source directories

* `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib`

### Source file examples

* `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib/xmlparse.c`
* `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib/xmlrole.c`
* `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib/xmltok.c`
* `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib/xmltok_impl.c`
* `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib/xmltok_ns.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6`

```text
/usr/bin/riscv64-linux-gnu-gcc -DHAVE_EXPAT_CONFIG_H -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-90b0f67bddaf0ac4/out/build -I/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib -ffunction-sections -fdata-sections -fPIC -march=rv64gc -mabi=lp64d -w -g -MD -MT CMakeFiles/expat.dir/lib/xmlrole.c.o -MF CMakeFiles/expat.dir/lib/xmlrole.c.o.d -o CMakeFiles/expat.dir/lib/xmlrole.c.o -c /tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib/xmlrole.c ...
```

Working directory: `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6`

```text
/usr/bin/riscv64-linux-gnu-gcc -DHAVE_EXPAT_CONFIG_H -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-90b0f67bddaf0ac4/out/build -I/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib -ffunction-sections -fdata-sections -fPIC -march=rv64gc -mabi=lp64d -w -g -MD -MT CMakeFiles/expat.dir/lib/xmltok_impl.c.o -MF CMakeFiles/expat.dir/lib/xmltok_impl.c.o.d -o CMakeFiles/expat.dir/lib/xmltok_impl.c.o -c /tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib/xmltok_impl.c ...
```

Working directory: `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6`

```text
/usr/bin/riscv64-linux-gnu-gcc -DHAVE_EXPAT_CONFIG_H -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-90b0f67bddaf0ac4/out/build -I/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib -ffunction-sections -fdata-sections -fPIC -march=rv64gc -mabi=lp64d -w -g -MD -MT CMakeFiles/expat.dir/lib/xmltok.c.o -MF CMakeFiles/expat.dir/lib/xmltok.c.o.d -o CMakeFiles/expat.dir/lib/xmltok.c.o -c /tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib/xmltok.c ...
```

Working directory: `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6`

```text
/usr/bin/riscv64-linux-gnu-gcc -DHAVE_EXPAT_CONFIG_H -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-90b0f67bddaf0ac4/out/build -I/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib -ffunction-sections -fdata-sections -fPIC -march=rv64gc -mabi=lp64d -w -g -MD -MT CMakeFiles/expat.dir/lib/xmlparse.c.o -MF CMakeFiles/expat.dir/lib/xmlparse.c.o.d -o CMakeFiles/expat.dir/lib/xmlparse.c.o -c /tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib/xmlparse.c ...
```

Working directory: `/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6`

```text
/usr/bin/riscv64-linux-gnu-gcc -DHAVE_EXPAT_CONFIG_H -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-90b0f67bddaf0ac4/out/build -I/tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib -ffunction-sections -fdata-sections -fPIC -march=rv64gc -mabi=lp64d -w -g -MD -MT CMakeFiles/expat.dir/lib/xmltok_ns.c.o -MF CMakeFiles/expat.dir/lib/xmltok_ns.c.o.d -o CMakeFiles/expat.dir/lib/xmltok_ns.c.o -c /tmp/crate-build-riscv64-ekf9k5gw/src/expat-sys-2.1.6/expat/lib/xmltok_ns.c ...
```

### Compilation

```text
cc1 -quiet -I <include directory> -I <include directory> -imultilib . -imultiarch riscv64-linux-gnu -MD <dependency file> -MF <dependency file> -MT <dependency target> -D HAVE_EXPAT_CONFIG_H <source> -quiet ...
```

### Static library construction

```text
ar qc <static library> <object files>
```
