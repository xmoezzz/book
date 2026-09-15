# `tracy-client-sys` `0.21.0`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 2058477

Build-script executable: `/work/target/debug/build/tracy-client-sys-b3e6dedc78d50ead/build_script_build-b3e6dedc78d50ead`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/tracy-client-sys-75d8993126f749f9/out/libtracy-client.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/tracy`

### Source file examples

* `/work/tracy/TracyClient.cpp`

### Source preparation

Working directory: `/work`

```text
/usr/bin/c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -DTRACY_ENABLE -o /work/target/debug/build/tracy-client-sys-75d8993126f749f9/out/b558eb55dea76cee-TracyClient.o -c tracy/TracyClient.cpp
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE -D TRACY_ENABLE tracy/TracyClient.cpp -quiet -dumpdir /work/target/debug/build/tracy-client-sys-75d8993126f749f9/out/ -dumpbase b558eb55dea76cee-TracyClient.cpp -dumpbase-ext .cpp -m64 -mtune=generic -march=x86-64 -g -gdwarf-4 ...
```

### Compilation

```text
c++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -w -DTRACY_ENABLE -o <object> -c <source>
```

### Static library construction

```text
ar cqD <static library> <object files>
```
