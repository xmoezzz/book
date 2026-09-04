# `rdkafka-sys` `4.7.0+2.3.0`

Platform: Linux riscv64

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
