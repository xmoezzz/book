# `zmq-sys` `0.12.0`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 2146904

Build-script executable: `/work/target/debug/build/zmq-sys-667939c149e68702/build_script_main-667939c149e68702`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/zmq-sys-f7c4c0bb5bd7ff4e/out/lib/libzmq.a`

### Source origin

* under crate source directory `/usr/local/cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4`

### Source directories

* `/usr/local/cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/external/sha1`
* `/usr/local/cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/src`

### Source file examples

* `/usr/local/cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/external/sha1/sha1.c`
* `/usr/local/cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/src/address.cpp`
* `/usr/local/cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/src/channel.cpp`
* `/usr/local/cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/src/client.cpp`
* `/usr/local/cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/src/clock.cpp`

### Compilation

```text
c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -Wall -Wextra -DZMQ_BUILD_TESTS=OFF -DZMQ_USE_CV_IMPL_STL11=1 -DZMQ_STATIC=1 -DZMQ_USE_BUILTIN_SHA1=1 -DZMQ_HAVE_WS=1 -DZMQ_IOTHREAD_POLLER_USE_EPOLL=1 -DZMQ_POLL_BASED_ON_POLL=1 -DZMQ_HAVE_IPC=1 -DHAVE_STRNLEN=1 -DZMQ_HAVE_UIO=1 -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
