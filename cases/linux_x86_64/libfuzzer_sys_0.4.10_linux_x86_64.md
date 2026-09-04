# `libfuzzer-sys` `0.4.10`

Platform: Linux x86_64

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

### Compilation

```text
c++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c++17 -o <object> -c <source>
```

### Static library construction

```text
ar cq <static library> <object files>
```
