# `lz4-sys` `1.11.1+lz4-1.10.0`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/liblz4.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0`

### Source directories

* `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib`

### Source file examples

* `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4.c`
* `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4frame.c`
* `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4hc.c`
* `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/xxhash.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/efce31824dbf3730-lz4.o -c liblz4/lib/lz4.c
```

Working directory: `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/efce31824dbf3730-lz4frame.o -c liblz4/lib/lz4frame.c
```

Working directory: `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/efce31824dbf3730-lz4hc.o -c liblz4/lib/lz4hc.c
```

Working directory: `/tmp/crate-build-aarch64-1dlmgz0l/src/lz4-sys-1.11.1+lz4-1.10.0`

```text
/usr/bin/aarch64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/efce31824dbf3730-xxhash.o -c liblz4/lib/xxhash.c
```

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -g -gdwarf-4 -O3 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...
```

### Static library construction

```text
ar cqD <static library> <object files>
```
