# `zmq-sys` `0.12.0`

Platform: Windows x86_64

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-wcmjk8kj/src/zmq-sys-0.12.0/target/debug/build/zmq-sys-b94b087ac1cfb57c/out/lib/libzmq.a`

### Source origin

* under crate source directory `C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4`

### Source directories

* `C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/external/sha1`
* `C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/external/wepoll`
* `C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/src`

### Source file examples

* `C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/external/sha1/sha1.c`
* `C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/external/wepoll/wepoll.c`
* `C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/src/address.cpp`
* `C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/src/channel.cpp`
* `C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zeromq-src-0.2.6+4.3.4/vendor/src/client.cpp`

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -I <include directory> -W4 /GL- /EHsc -DZMQ_BUILD_TESTS=OFF -DZMQ_USE_CV_IMPL_STL11=1 -DZMQ_STATIC=1 -DZMQ_USE_BUILTIN_SHA1=1 -DZMQ_HAVE_WS=1 -DZMQ_IOTHREAD_POLLER_USE_EPOLL=1 -DZMQ_POLL_BASED_ON_POLL=1 -D_WIN32_WINNT=0x0600 -DZMQ_HAVE_IPC=1 <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
