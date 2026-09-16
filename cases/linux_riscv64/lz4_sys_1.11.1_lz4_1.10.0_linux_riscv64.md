# `lz4-sys` `1.11.1+lz4-1.10.0`

Platform: Linux riscv64

## `/target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/liblz4.a`

### Source origin

* under crate source directory `/tmp/crate-build-riscv64-gsw5w4ht/src/lz4-sys-1.11.1+lz4-1.10.0`

### Source directories

* `/tmp/crate-build-riscv64-gsw5w4ht/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib`

### Source file examples

* `/tmp/crate-build-riscv64-gsw5w4ht/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4.c`
* `/tmp/crate-build-riscv64-gsw5w4ht/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4frame.c`
* `/tmp/crate-build-riscv64-gsw5w4ht/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4hc.c`
* `/tmp/crate-build-riscv64-gsw5w4ht/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/xxhash.c`

### Source preparation

Working directory: `/tmp/crate-build-riscv64-gsw5w4ht/src/lz4-sys-1.11.1+lz4-1.10.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/efce31824dbf3730-lz4.o -c liblz4/lib/lz4.c
```

Working directory: `/tmp/crate-build-riscv64-gsw5w4ht/src/lz4-sys-1.11.1+lz4-1.10.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/efce31824dbf3730-lz4frame.o -c liblz4/lib/lz4frame.c
```

Working directory: `/tmp/crate-build-riscv64-gsw5w4ht/src/lz4-sys-1.11.1+lz4-1.10.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/efce31824dbf3730-lz4hc.o -c liblz4/lib/lz4hc.c
```

Working directory: `/tmp/crate-build-riscv64-gsw5w4ht/src/lz4-sys-1.11.1+lz4-1.10.0`

```text
/usr/bin/riscv64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/efce31824dbf3730-xxhash.o -c liblz4/lib/xxhash.c
```

### Compilation

```text
cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu <source> -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/ -dumpbase <source> -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
