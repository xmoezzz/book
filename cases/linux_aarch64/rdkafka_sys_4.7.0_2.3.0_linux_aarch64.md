# `rdkafka-sys` `4.7.0+2.3.0`

Platform: Linux aarch64

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
