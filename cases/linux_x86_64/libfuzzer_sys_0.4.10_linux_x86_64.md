# `libfuzzer-sys` `0.4.10`

Platform: Linux x86_64

## Build-level coding evidence

### Build-script executable native dependencies

#### Linker process 1882978

Build-script executable: `/work/target/debug/build/libfuzzer-sys-3b15292f33882d3a/build_script_build-3b15292f33882d3a`

Working directory: `/work`

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)

## `/work/target/debug/build/libfuzzer-sys-ce1dd2ac925c188b/out/libfuzzer.a`

### Source origin

* under crate source directory `/work`

### Source directories

* `/work/libfuzzer`

### Source file examples

* `/work/libfuzzer/FuzzerCrossOver.cpp`
* `/work/libfuzzer/FuzzerDataFlowTrace.cpp`
* `/work/libfuzzer/FuzzerDriver.cpp`
* `/work/libfuzzer/FuzzerExtFunctionsDlsym.cpp`
* `/work/libfuzzer/FuzzerExtFunctionsWeak.cpp`

### Source preparation

Working directory: `/work`

```text
/usr/bin/c++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -o /work/target/debug/build/libfuzzer-sys-ce1dd2ac925c188b/out/e5f0d71fb86e9d6b-FuzzerUtilPosix.o -c libfuzzer/FuzzerUtilPosix.cpp
```

Working directory: `/work`

```text
/usr/bin/c++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -o /work/target/debug/build/libfuzzer-sys-ce1dd2ac925c188b/out/e5f0d71fb86e9d6b-FuzzerUtilWindows.o -c libfuzzer/FuzzerUtilWindows.cpp
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE libfuzzer/FuzzerUtilWindows.cpp -quiet -dumpdir /work/target/debug/build/libfuzzer-sys-ce1dd2ac925c188b/out/ -dumpbase e5f0d71fb86e9d6b-FuzzerUtilWindows.cpp -dumpbase-ext .cpp -m64 -mtune=generic -march=x86-64 -gdwarf-4 -O0 -std=c++17 -ffunction-sections ...
```

Working directory: `/work`

```text
/usr/bin/c++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -o /work/target/debug/build/libfuzzer-sys-ce1dd2ac925c188b/out/e5f0d71fb86e9d6b-FuzzerUtil.o -c libfuzzer/FuzzerUtil.cpp
```

Working directory: `/work`

```text
/usr/lib/gcc/x86_64-linux-gnu/12/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE libfuzzer/FuzzerUtilPosix.cpp -quiet -dumpdir /work/target/debug/build/libfuzzer-sys-ce1dd2ac925c188b/out/ -dumpbase e5f0d71fb86e9d6b-FuzzerUtilPosix.cpp -dumpbase-ext .cpp -m64 -mtune=generic -march=x86-64 -gdwarf-4 -O0 -std=c++17 -ffunction-sections ...
```

### Compilation

```text
c++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
