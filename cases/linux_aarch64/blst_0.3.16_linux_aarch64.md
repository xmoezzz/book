# `blst` `0.3.16`

Platform: Linux aarch64

## `/target/aarch64-unknown-linux-gnu/debug/build/blst-013c6a04e2a717d2/out/libblst.a`

### Source origin

* under crate source directory `/tmp/crate-build-aarch64-23zjpn7l/src/blst-0.3.16`

### Source directories

* `/tmp/crate-build-aarch64-23zjpn7l/src/blst-0.3.16/blst/build`
* `/tmp/crate-build-aarch64-23zjpn7l/src/blst-0.3.16/blst/src`

### Source file examples

* `/tmp/crate-build-aarch64-23zjpn7l/src/blst-0.3.16/blst/build/assembly.S`
* `/tmp/crate-build-aarch64-23zjpn7l/src/blst-0.3.16/blst/src/server.c`

### Source preparation

Working directory: `/tmp/crate-build-aarch64-23zjpn7l/src/blst-0.3.16`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -fno-builtin -Wno-unused-function -Wno-unused-command-line-argument -o /target/aarch64-unknown-linux-gnu/debug/build/blst-013c6a04e2a717d2/out/3ce72ea41a6346fd-server.o -c /tmp/crate-build-aarch64-23zjpn7l/src/blst-0.3.16/blst/src/server.c
```

Working directory: `/tmp/crate-build-aarch64-23zjpn7l/src/blst-0.3.16`

```text
/usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -fno-builtin -Wno-unused-function -Wno-unused-command-line-argument -o /target/aarch64-unknown-linux-gnu/debug/build/blst-013c6a04e2a717d2/out/f6e817b043e0335b-assembly.o -c /tmp/crate-build-aarch64-23zjpn7l/src/blst-0.3.16/blst/build/assembly.S
```

### Compilation

```text
cc1 -quiet -imultiarch aarch64-linux-gnu <source> -quiet -dumpbase <source> -mlittle-endian -mabi=lp64 -auxbase-strip <object> -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-function -Wno-unused-command-line-argument -ffunction-sections -fdata-sections ...
```

```text
cc1 -E -lang-asm -quiet -imultiarch aarch64-linux-gnu <source> -mlittle-endian -mabi=lp64 -Wall -Wextra -Wno-unused-function -Wno-unused-command-line-argument -ffunction-sections -fdata-sections -fPIC -fno-omit-frame-pointer -fno-builtin -gdwarf-4 -fworking-directory ...
```

### Static library construction

```text
ar cq <static library> <object files>
```
