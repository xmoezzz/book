# `bzip2-sys` `0.1.11+1.0.8`

Platform: Windows x86_64

This file contains the unabridged evidence for the corresponding manual-coding case.

## Root-owned build-level evidence

### Network / source acquisition records

_None._

### pkg-config / pkgconf records

_None._

### Other root-owned linker evidence

### Other root-owned link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "-c",
    "bzip2-1.0.8/blocksort.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "bzip2-1.0.8/blocksort.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "-c",
    "bzip2-1.0.8/huffman.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "bzip2-1.0.8/huffman.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "-c",
    "bzip2-1.0.8/crctable.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "bzip2-1.0.8/crctable.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "-c",
    "bzip2-1.0.8/randtable.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "bzip2-1.0.8/randtable.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "-c",
    "bzip2-1.0.8/compress.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "bzip2-1.0.8/compress.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "-c",
    "bzip2-1.0.8/decompress.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "bzip2-1.0.8/decompress.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "-c",
    "bzip2-1.0.8/bzlib.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "bzip2-1.0.8/bzlib.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\msvcrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\vcruntime.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400f0020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400f0298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400f02b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400f0300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400f0320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400f0338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400f0348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400f0358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400f03f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400f0408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400f0418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400f0448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400f0460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-link-link-17376-1783954233917209200.map",
  "pid": 17376,
  "ppid": 15160,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-link-link-17376-1783954233917209200.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/target/debug/build/bzip2-sys-a53f7c14e427c16f/out/lib/libbz2.a`

Owner: `bzip2-sys` `0.1.11+1.0.8`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/blocksort.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/bzlib.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/compress.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/crctable.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/decompress.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/huffman.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/bzip2-1.0.8/randtable.c`

### Source acquisition records

_None._

### Source preparation records

_None._

### Compilation records

#### Record 1

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "-c",
    "bzip2-1.0.8/compress.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
  "src": "bzip2-1.0.8/compress.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 2

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "-c",
    "bzip2-1.0.8/huffman.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
  "src": "bzip2-1.0.8/huffman.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "-c",
    "bzip2-1.0.8/bzlib.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
  "src": "bzip2-1.0.8/bzlib.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "-c",
    "bzip2-1.0.8/crctable.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
  "src": "bzip2-1.0.8/crctable.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "-c",
    "bzip2-1.0.8/decompress.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
  "src": "bzip2-1.0.8/decompress.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "-c",
    "bzip2-1.0.8/blocksort.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
  "src": "bzip2-1.0.8/blocksort.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "-c",
    "bzip2-1.0.8/randtable.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
  "src": "bzip2-1.0.8/randtable.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

### Native link records

_None._

### Resolved link records

_None._

### Resolved native inputs

_None._

## Complete analysis record stream

These are the recovered/enriched/generated records actually supplied to native-flow reconstruction.

### Analysis records

#### Record 1

```json
{
  "event": "native_trace_root_context",
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8"
  ],
  "packages": [
    {
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
      "name": "bzip2-sys",
      "version": "0.1.11+1.0.8",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
      "name": "cc",
      "version": "1.2.67",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
      "name": "find-msvc-tools",
      "version": "0.1.9",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.33",
      "name": "pkg-config",
      "version": "0.3.33",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1"
    }
  ]
}
```

#### Record 2

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "exit_code": 0,
  "kind": "exec",
  "pid": 4720,
  "ppid": 11992,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 3

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:90ad33d1ed1d6121:2e05e811264381e5",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
  "pid": 4720,
  "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 4

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:7c1eb5c1ad49f827:2e05e811264381e5",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
  "pid": 4720,
  "sha256": "bc10b3d4f9e70cd4b21eeaf3a249f7fe3c94bd8e8d2bbf2d42598ed147ce160b",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 5

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:653e09884864f05a:2e05e811264381e5",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
  "pid": 4720,
  "sha256": "ec02ee9a055e4ec6617677d1a0b6c039e4659b89eb2952e9bc9eba87ec772979",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 6

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:783ba13db5deceb3:2e05e811264381e5",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
  "pid": 4720,
  "sha256": "ff6efff4075e0da6e4767eda3aabf950aaf5c03d0e10e6a5f00c853fbf3b38eb",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:0d89bddccb7dce86:2e05e811264381e5",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
  "pid": 4720,
  "sha256": "a9cb0655191f6f00d39679a0a0eb749cbf6d83f64b3515275338daaf08a919b7",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 8

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:376e2a274745ad0b:2e05e811264381e5",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
  "pid": 4720,
  "sha256": "acdad7f98ed1b9cdbe26be386469cca0a840b203efc6807977f688b63ef3ca21",
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 9

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2e05e811264381e5",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "kernel32.lib",
  "pid": 4720,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 10

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2e05e811264381e5",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "kernel32.lib",
  "pid": 4720,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 11

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2e05e811264381e5",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "kernel32.lib",
  "pid": 4720,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 12

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:1db9512c4d5c31e6:2e05e811264381e5",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "ntdll.lib",
  "pid": 4720,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:861f0814f9c52599:2e05e811264381e5",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "userenv.lib",
  "pid": 4720,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 14

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:50848825683fdca9:2e05e811264381e5",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "ws2_32.lib",
  "pid": 4720,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "used:link:e28a626e7bd4a22f:df7d4e53c08047f7:2e05e811264381e5",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "dbghelp.lib",
  "pid": 4720,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib"
  ],
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 4720,
  "ppid": 11992,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
    "kernel32.lib",
    "kernel32.lib",
    "kernel32.lib",
    "ntdll.lib",
    "userenv.lib",
    "ws2_32.lib",
    "dbghelp.lib",
    "/defaultlib:msvcrt",
    "/NXCOMPAT",
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
    "/OPT:REF,NOICF",
    "/DEBUG",
    "/PDBALTPATH:%_PDB%",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
    "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
  ],
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "directories": [
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       ",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\msvcrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\vcruntime.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140039200     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140039250     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140039270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140039288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140039298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400392a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140039340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140039358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140039388     ntdll:ntdll.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-link-link-4720-1783954233132752400.map",
  "pid": 4720,
  "ppid": 11992,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-link-link-4720-1783954233132752400.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17376,
  "ppid": 15160,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 17376,
  "ppid": 15160,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\msvcrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
      "kind": "library",
      "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\vcruntime.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400f0020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400f0298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400f02b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400f0300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400f0320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400f0338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400f0348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400f0358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400f03f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400f0408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400f0418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400f0448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400f0460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-link-link-17376-1783954233917209200.map",
  "pid": 17376,
  "ppid": 15160,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-link-link-17376-1783954233917209200.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 3272,
  "ppid": 16340,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:49e0e4242770f08d:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c",
  "pid": 3272,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "argv": [
    "cl",
    "-E",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "pid": 3272,
  "ppid": 16340,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 27

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 7364,
  "ppid": 16340,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

```json
{
  "argv": [
    "cl",
    "-?"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "pid": 7364,
  "ppid": 16340,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 29

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "-c",
    "bzip2-1.0.8/blocksort.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 3680,
  "ppid": 16340,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "-c",
    "bzip2-1.0.8/blocksort.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:78e6ee6a1370cecc:da5c17eda2344a86",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
  "path": "bzip2-1.0.8/blocksort.c",
  "pid": 3680,
  "sha256": "4e48cd2ccff44699e67a7c949b0e9576c05b8dcbe20f863475c4fcc8db11a409",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 31

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "-c",
    "bzip2-1.0.8/blocksort.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:b0e1265788dbddd5:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
  "pid": 3680,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 32

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "-c",
    "bzip2-1.0.8/blocksort.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:78e6ee6a1370cecc:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "bzip2-1.0.8/blocksort.c",
  "pid": 3680,
  "sha256": "4e48cd2ccff44699e67a7c949b0e9576c05b8dcbe20f863475c4fcc8db11a409",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 33

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "-c",
    "bzip2-1.0.8/blocksort.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
  "src": "bzip2-1.0.8/blocksort.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 34

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "-c",
    "bzip2-1.0.8/blocksort.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "bzip2-1.0.8/blocksort.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 35

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "-c",
    "bzip2-1.0.8/blocksort.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "pid": 3680,
  "ppid": 16340,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "-c",
    "bzip2-1.0.8/huffman.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 13172,
  "ppid": 16340,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 37

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "-c",
    "bzip2-1.0.8/huffman.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:e8fcc6136ffc09e2:02c4f6834e896e06",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
  "path": "bzip2-1.0.8/huffman.c",
  "pid": 13172,
  "sha256": "bdeb45f3f535546a672811b68aa87cc58fd395b28ecebc34fa3566a656a4d1d1",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 38

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "-c",
    "bzip2-1.0.8/huffman.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:2e1b0d2c22538668:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
  "pid": 13172,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 39

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "-c",
    "bzip2-1.0.8/huffman.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:e8fcc6136ffc09e2:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "bzip2-1.0.8/huffman.c",
  "pid": 13172,
  "sha256": "bdeb45f3f535546a672811b68aa87cc58fd395b28ecebc34fa3566a656a4d1d1",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 40

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "-c",
    "bzip2-1.0.8/huffman.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
  "src": "bzip2-1.0.8/huffman.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 41

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "-c",
    "bzip2-1.0.8/huffman.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "bzip2-1.0.8/huffman.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 42

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "-c",
    "bzip2-1.0.8/huffman.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "pid": 13172,
  "ppid": 16340,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 43

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "-c",
    "bzip2-1.0.8/crctable.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 10744,
  "ppid": 16340,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 44

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "-c",
    "bzip2-1.0.8/crctable.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:d4f7e42684e06817:413789dbb2467bc1",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
  "path": "bzip2-1.0.8/crctable.c",
  "pid": 10744,
  "sha256": "2fb7a564629386456e731f431a5cf4f5026747bace4cd10be8f5ecf082066a92",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 45

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "-c",
    "bzip2-1.0.8/crctable.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:70cb3ac631e18aff:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
  "pid": 10744,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 46

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "-c",
    "bzip2-1.0.8/crctable.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:d4f7e42684e06817:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "bzip2-1.0.8/crctable.c",
  "pid": 10744,
  "sha256": "2fb7a564629386456e731f431a5cf4f5026747bace4cd10be8f5ecf082066a92",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 47

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "-c",
    "bzip2-1.0.8/crctable.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
  "src": "bzip2-1.0.8/crctable.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 48

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "-c",
    "bzip2-1.0.8/crctable.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "bzip2-1.0.8/crctable.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 49

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "-c",
    "bzip2-1.0.8/crctable.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "pid": 10744,
  "ppid": 16340,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 50

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "-c",
    "bzip2-1.0.8/randtable.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 9468,
  "ppid": 16340,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 51

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "-c",
    "bzip2-1.0.8/randtable.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:2cdfec052db3836b:4e763192af6f71a8",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
  "path": "bzip2-1.0.8/randtable.c",
  "pid": 9468,
  "sha256": "407054ca6f54cd737dbc26ceb6b7874b55a0fcff86c2eb23cbec2fbdbb884815",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 52

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "-c",
    "bzip2-1.0.8/randtable.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:6626e14ba36726f7:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
  "pid": 9468,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 53

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "-c",
    "bzip2-1.0.8/randtable.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:2cdfec052db3836b:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "bzip2-1.0.8/randtable.c",
  "pid": 9468,
  "sha256": "407054ca6f54cd737dbc26ceb6b7874b55a0fcff86c2eb23cbec2fbdbb884815",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 54

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "-c",
    "bzip2-1.0.8/randtable.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
  "src": "bzip2-1.0.8/randtable.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 55

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "-c",
    "bzip2-1.0.8/randtable.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "bzip2-1.0.8/randtable.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 56

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "-c",
    "bzip2-1.0.8/randtable.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "pid": 9468,
  "ppid": 16340,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 57

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "-c",
    "bzip2-1.0.8/compress.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17136,
  "ppid": 16340,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 58

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "-c",
    "bzip2-1.0.8/compress.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:25376ab909f1353b:aa1206ea0a7caecc",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
  "path": "bzip2-1.0.8/compress.c",
  "pid": 17136,
  "sha256": "75995bd6e8c5f1e1dad05178f3cf53137df99ce860a1984324f78591f28deed3",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 59

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "-c",
    "bzip2-1.0.8/compress.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:41fa8ab89b033abb:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
  "pid": 17136,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 60

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "-c",
    "bzip2-1.0.8/compress.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:25376ab909f1353b:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "bzip2-1.0.8/compress.c",
  "pid": 17136,
  "sha256": "75995bd6e8c5f1e1dad05178f3cf53137df99ce860a1984324f78591f28deed3",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 61

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "-c",
    "bzip2-1.0.8/compress.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
  "src": "bzip2-1.0.8/compress.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 62

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "-c",
    "bzip2-1.0.8/compress.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "bzip2-1.0.8/compress.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 63

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "-c",
    "bzip2-1.0.8/compress.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "pid": 17136,
  "ppid": 16340,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 64

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "-c",
    "bzip2-1.0.8/decompress.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 16520,
  "ppid": 16340,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 65

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "-c",
    "bzip2-1.0.8/decompress.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:64b0fa5304cc159d:9cda31fe85fb49f1",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
  "path": "bzip2-1.0.8/decompress.c",
  "pid": 16520,
  "sha256": "31a89f8bf408ef0e4acae83e8be60a8eb4edece6c866d6e32b8f7e557ca54bc6",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 66

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "-c",
    "bzip2-1.0.8/decompress.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:e76d25979b79011f:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
  "pid": 16520,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 67

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "-c",
    "bzip2-1.0.8/decompress.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:64b0fa5304cc159d:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "bzip2-1.0.8/decompress.c",
  "pid": 16520,
  "sha256": "31a89f8bf408ef0e4acae83e8be60a8eb4edece6c866d6e32b8f7e557ca54bc6",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 68

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "-c",
    "bzip2-1.0.8/decompress.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
  "src": "bzip2-1.0.8/decompress.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 69

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "-c",
    "bzip2-1.0.8/decompress.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "bzip2-1.0.8/decompress.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 70

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "-c",
    "bzip2-1.0.8/decompress.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "pid": 16520,
  "ppid": 16340,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 71

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "-c",
    "bzip2-1.0.8/bzlib.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 4640,
  "ppid": 16340,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 72

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "-c",
    "bzip2-1.0.8/bzlib.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:85c0217da365dccb:0aee49091e7f0bd3",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
  "path": "bzip2-1.0.8/bzlib.c",
  "pid": 4640,
  "sha256": "d06cf1bd991df1f2dc8ef4f7713d186eb636767111cbd4807ef5fc4a54ca6838",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 73

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "-c",
    "bzip2-1.0.8/bzlib.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:4c2f27ac0878f5d8:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
  "pid": 4640,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 74

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "-c",
    "bzip2-1.0.8/bzlib.c"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:cl:5488b1e276495a54:85c0217da365dccb:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "bzip2-1.0.8/bzlib.c",
  "pid": 4640,
  "sha256": "d06cf1bd991df1f2dc8ef4f7713d186eb636767111cbd4807ef5fc4a54ca6838",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 75

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "-c",
    "bzip2-1.0.8/bzlib.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
  "src": "bzip2-1.0.8/bzlib.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 76

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "-c",
    "bzip2-1.0.8/bzlib.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "bzip2-1.0.8/bzlib.c"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": null,
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 77

```json
{
  "argv": [
    "cl",
    "-nologo",
    "-MD",
    "-Z7",
    "-Brepro",
    "-I",
    "bzip2-1.0.8",
    "-W0",
    "-D_WIN32",
    "-DBZ_EXPORT",
    "-D_FILE_OFFSET_BITS=64",
    "-DBZ_NO_STDIO",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
    "-c",
    "bzip2-1.0.8/bzlib.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "pid": 4640,
  "ppid": 16340,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 78

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "exec",
  "pid": 6708,
  "ppid": 16340,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 79

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:da5c17eda2344a86:eab349e2bc26e393",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
  "pid": 6708,
  "sha256": "9a0ec0880bc85982f60d6711ffa5bc55579fb316e8f18222f60c8001da13e238",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 80

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:02c4f6834e896e06:eab349e2bc26e393",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
  "pid": 6708,
  "sha256": "8f2966958c4fc17d6588a45cd38c408357f82b282e27e6bfa9dbea33b46fca82",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 81

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:413789dbb2467bc1:eab349e2bc26e393",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
  "pid": 6708,
  "sha256": "a6d1832ebead72f44c22c01aea45418dd6fd4ebba2d142dcb7ba90c42b8ba771",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 82

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:4e763192af6f71a8:eab349e2bc26e393",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
  "pid": 6708,
  "sha256": "2704eb689c76cac0692d4e333563c69e003abc086ca7e28ef07c86bd3be5bb73",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 83

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:aa1206ea0a7caecc:eab349e2bc26e393",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
  "pid": 6708,
  "sha256": "278f30119bf02d2ece80d3166a5b41b5db6fcf7e248a05954a749856d499d4e4",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 84

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:9cda31fe85fb49f1:eab349e2bc26e393",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
  "pid": 6708,
  "sha256": "2d6d8ec25dad5c85d3e3d04a1f6a342441a4ccc331d2fa135940568a0cba07f3",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 85

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:0aee49091e7f0bd3:eab349e2bc26e393",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
  "pid": 6708,
  "sha256": "a31d906a14ae396e85096add1e8ce2cadc4102ba7036b12d08f719a0ab86f373",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 86

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:da5c17eda2344a86:66abe07a8169e0e6",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
  "pid": 6708,
  "sha256": "9a0ec0880bc85982f60d6711ffa5bc55579fb316e8f18222f60c8001da13e238",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 87

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:02c4f6834e896e06:66abe07a8169e0e6",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
  "pid": 6708,
  "sha256": "8f2966958c4fc17d6588a45cd38c408357f82b282e27e6bfa9dbea33b46fca82",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 88

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:413789dbb2467bc1:66abe07a8169e0e6",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
  "pid": 6708,
  "sha256": "a6d1832ebead72f44c22c01aea45418dd6fd4ebba2d142dcb7ba90c42b8ba771",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 89

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:4e763192af6f71a8:66abe07a8169e0e6",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
  "pid": 6708,
  "sha256": "2704eb689c76cac0692d4e333563c69e003abc086ca7e28ef07c86bd3be5bb73",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 90

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:aa1206ea0a7caecc:66abe07a8169e0e6",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
  "pid": 6708,
  "sha256": "278f30119bf02d2ece80d3166a5b41b5db6fcf7e248a05954a749856d499d4e4",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 91

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:9cda31fe85fb49f1:66abe07a8169e0e6",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
  "pid": 6708,
  "sha256": "2d6d8ec25dad5c85d3e3d04a1f6a342441a4ccc331d2fa135940568a0cba07f3",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 92

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "used:lib:5488b1e276495a54:0aee49091e7f0bd3:66abe07a8169e0e6",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
  "pid": 6708,
  "sha256": "a31d906a14ae396e85096add1e8ce2cadc4102ba7036b12d08f719a0ab86f373",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 93

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 94

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 95

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "cargo_pkg_name": "bzip2-sys",
  "cargo_pkg_version": "0.1.11+1.0.8",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "pid": 6708,
  "ppid": 16340,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 96

```json
{
  "crate": "bzip2-sys",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "event_id": "bsrun:152c70d20f7ea708:3643d6ae074f55c5:be29f52f1add074c",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "0.1.11+1.0.8",
  "_owner": {
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
    "source": "cwd_prefix"
  }
}
```

#### Record 97

```json
{
  "crate": "libc",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "bsrun:a733304fa0307800:b7dbb3665b8070c3:8a254808bef4b34d",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/target/debug/build/libc-763fb040b2d663ab\\build-script-build.exe",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/target/debug/build/libc-763fb040b2d663ab/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
  "success": true,
  "target": null,
  "version": "0.2.186",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  }
}
```

#### Record 98

```json
{
  "event": "process_tracer_diagnostic",
  "platform": "windows_etw",
  "phase": "realtime",
  "argv": [],
  "spawn_error": null,
  "exit_status": null,
  "stdout": "",
  "stderr": "",
  "raw_event_count": 5492,
  "parsed_event_count": 5492,
  "parse_error_count": 0,
  "command_line_event_count": 5492,
  "build_script_root_event_count": 102,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 504,
  "dropped_event_count": 2867
}
```

#### Record 99

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12896,
  "ppid": 4080,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:50:33.320096+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
  "root_cargo_pid": 9164,
  "build_script_root_pid": 12896,
  "build_script_related": true,
  "build_script_target_dir": "libc-763fb040b2d663ab",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/target/debug/build/libc-763fb040b2d663ab/out"
}
```

#### Record 100

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 536,
  "ppid": 12896,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
  ],
  "comm": "rustc-trace-wrapper.exe",
  "time": "2026-07-13T14:50:33.328557+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "root_cargo_pid": 9164,
  "build_script_root_pid": 12896,
  "build_script_related": true,
  "build_script_target_dir": "libc-763fb040b2d663ab",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/target/debug/build/libc-763fb040b2d663ab/out",
  "_direct_build_script_child": true,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 101

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13552,
  "ppid": 536,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:50:33.337752+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 9164,
  "build_script_root_pid": 12896,
  "build_script_related": true,
  "build_script_target_dir": "libc-763fb040b2d663ab",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/target/debug/build/libc-763fb040b2d663ab/out"
}
```

#### Record 102

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16340,
  "ppid": 4080,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:50:34.246049+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\build-script-build.exe",
  "root_cargo_pid": 9164,
  "build_script_root_pid": 16340,
  "build_script_related": true,
  "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
}
```

#### Record 103

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 3272,
  "ppid": 16340,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:50:34.336275+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
  "root_cargo_pid": 9164,
  "build_script_root_pid": 16340,
  "build_script_related": true,
  "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
}
```

#### Record 104

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 5936,
  "ppid": 3272,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:50:34.344558+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 9164,
  "build_script_root_pid": 16340,
  "build_script_related": true,
  "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
}
```

#### Record 105

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 7364,
  "ppid": 16340,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:50:34.374402+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
  "root_cargo_pid": 9164,
  "build_script_root_pid": 16340,
  "build_script_related": true,
  "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
}
```

#### Record 106

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 6116,
  "ppid": 7364,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:50:34.379653+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 9164,
  "build_script_root_pid": 16340,
  "build_script_related": true,
  "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
}
```

#### Record 107

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 3680,
  "ppid": 16340,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:50:34.421567+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
  "root_cargo_pid": 9164,
  "build_script_root_pid": 16340,
  "build_script_related": true,
  "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
}
```

#### Record 108

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12112,
  "ppid": 3680,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:50:34.426893+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 9164,
  "build_script_root_pid": 16340,
  "build_script_related": true,
  "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
}
```

#### Record 109

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 4780,
  "ppid": 12252,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:32.647794+00:00",
  "end_time": "2026-07-13T14:50:32.664221+00:00",
  "start_unix_nanos": 1783954232647793700,
  "end_unix_nanos": 1783954232664220700,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 110

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 10500,
  "ppid": 12252,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-",
    "--crate-name",
    "___",
    "--print=file-names",
    "--crate-type",
    "bin",
    "--crate-type",
    "rlib",
    "--crate-type",
    "dylib",
    "--crate-type",
    "cdylib",
    "--crate-type",
    "staticlib",
    "--crate-type",
    "proc-macro",
    "--print=sysroot",
    "--print=split-debuginfo",
    "--print=crate-name",
    "--print=cfg",
    "-Wwarnings"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name --print=cfg -Wwarnings",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-",
    "--crate-name",
    "___",
    "--print=file-names",
    "--crate-type",
    "bin",
    "--crate-type",
    "rlib",
    "--crate-type",
    "dylib",
    "--crate-type",
    "cdylib",
    "--crate-type",
    "staticlib",
    "--crate-type",
    "proc-macro",
    "--print=sysroot",
    "--print=split-debuginfo",
    "--print=crate-name",
    "--print=cfg",
    "-Wwarnings"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:32.670097+00:00",
  "end_time": "2026-07-13T14:50:32.689003+00:00",
  "start_unix_nanos": 1783954232670096900,
  "end_unix_nanos": 1783954232689002900,
  "crate_name": "___",
  "crate_type": [
    "bin",
    "rlib",
    "dylib",
    "cdylib",
    "staticlib",
    "proc-macro"
  ],
  "out_dir": null
}
```

#### Record 111

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 11316,
  "ppid": 12252,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:32.810870+00:00",
  "end_time": "2026-07-13T14:50:32.828557+00:00",
  "start_unix_nanos": 1783954232810870100,
  "end_unix_nanos": 1783954232828557500,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 112

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 4528,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:32.881478+00:00",
  "end_time": "2026-07-13T14:50:32.899371+00:00",
  "start_unix_nanos": 1783954232881477900,
  "end_unix_nanos": 1783954232899370600,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 113

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 2652,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-",
    "--crate-name",
    "___",
    "--print=file-names",
    "--crate-type",
    "bin",
    "--crate-type",
    "rlib",
    "--crate-type",
    "dylib",
    "--crate-type",
    "cdylib",
    "--crate-type",
    "staticlib",
    "--crate-type",
    "proc-macro",
    "--print=sysroot",
    "--print=split-debuginfo",
    "--print=crate-name",
    "--print=cfg",
    "-Wwarnings"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name --print=cfg -Wwarnings",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-",
    "--crate-name",
    "___",
    "--print=file-names",
    "--crate-type",
    "bin",
    "--crate-type",
    "rlib",
    "--crate-type",
    "dylib",
    "--crate-type",
    "cdylib",
    "--crate-type",
    "staticlib",
    "--crate-type",
    "proc-macro",
    "--print=sysroot",
    "--print=split-debuginfo",
    "--print=crate-name",
    "--print=cfg",
    "-Wwarnings"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:32.905426+00:00",
  "end_time": "2026-07-13T14:50:32.926229+00:00",
  "start_unix_nanos": 1783954232905426000,
  "end_unix_nanos": 1783954232926228800,
  "crate_name": "___",
  "crate_type": [
    "bin",
    "rlib",
    "dylib",
    "cdylib",
    "staticlib",
    "proc-macro"
  ],
  "out_dir": null
}
```

#### Record 114

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 15424,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "-vV"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:32.936749+00:00",
  "end_time": "2026-07-13T14:50:32.954418+00:00",
  "start_unix_nanos": 1783954232936748400,
  "end_unix_nanos": 1783954232954418400,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 115

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 16844,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "find_msvc_tools",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=a199b1cb5e329831",
    "-C",
    "extra-filename=-824f9ded730dd358",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "find_msvc_tools",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=a199b1cb5e329831",
    "-C",
    "extra-filename=-824f9ded730dd358",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:32.971812+00:00",
  "end_time": "2026-07-13T14:50:33.347677+00:00",
  "start_unix_nanos": 1783954232971812400,
  "end_unix_nanos": 1783954233347676400,
  "crate_name": "find_msvc_tools",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
}
```

#### Record 116

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 10504,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "shlex",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--warn=unexpected_cfgs",
    "--check-cfg",
    "cfg(manual_codegen_check)",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=181708ecadab3b47",
    "-C",
    "extra-filename=-f9df91f0b2c0ecd4",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "shlex",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--warn=unexpected_cfgs",
    "--check-cfg",
    "cfg(manual_codegen_check)",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"default\", \"std\"))",
    "-C",
    "metadata=181708ecadab3b47",
    "-C",
    "extra-filename=-f9df91f0b2c0ecd4",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:32.973944+00:00",
  "end_time": "2026-07-13T14:50:33.084065+00:00",
  "start_unix_nanos": 1783954232973943700,
  "end_unix_nanos": 1783954233084065500,
  "crate_name": "shlex",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
}
```

#### Record 117

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 10488,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=0add1c4e1ef78d62",
    "-C",
    "extra-filename=-763fb040b2d663ab",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=0add1c4e1ef78d62 -C extra-filename=-763fb040b2d663ab --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=0add1c4e1ef78d62",
    "-C",
    "extra-filename=-763fb040b2d663ab",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:32.976263+00:00",
  "end_time": "2026-07-13T14:50:33.243261+00:00",
  "start_unix_nanos": 1783954232976263400,
  "end_unix_nanos": 1783954233243260900,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab"
}
```

#### Record 118

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 7560,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "pkg_config",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=850bf69d60833204",
    "-C",
    "extra-filename=-3e67ae996f5d4ab8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name pkg_config --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=850bf69d60833204 -C extra-filename=-3e67ae996f5d4ab8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "pkg_config",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values())",
    "-C",
    "metadata=850bf69d60833204",
    "-C",
    "extra-filename=-3e67ae996f5d4ab8",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:32.978694+00:00",
  "end_time": "2026-07-13T14:50:33.227503+00:00",
  "start_unix_nanos": 1783954232978694200,
  "end_unix_nanos": 1783954233227502800,
  "crate_name": "pkg_config",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
}
```

#### Record 119

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 9496,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"jobserver\", \"parallel\"))",
    "-C",
    "metadata=98547e1a4afb2a03",
    "-C",
    "extra-filename=-24e0405f325d0f68",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "cc",
    "--edition=2018",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "--allow=unexpected_cfgs",
    "--check-cfg",
    "cfg(disable_clang_cl_tests)",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"jobserver\", \"parallel\"))",
    "-C",
    "metadata=98547e1a4afb2a03",
    "-C",
    "extra-filename=-24e0405f325d0f68",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:33.186785+00:00",
  "end_time": "2026-07-13T14:50:33.797933+00:00",
  "start_unix_nanos": 1783954233186785300,
  "end_unix_nanos": 1783954233797932700,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
}
```

#### Record 120

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 536,
  "ppid": 12896,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--version"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --version",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--version"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:33.333166+00:00",
  "end_time": "2026-07-13T14:50:33.350063+00:00",
  "start_unix_nanos": 1783954233333165800,
  "end_unix_nanos": 1783954233350063000,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 121

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 16584,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libc",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=de34c0666a4c6d46",
    "-C",
    "extra-filename=-751e763eb72b7eae",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "--cfg",
    "freebsd12",
    "--check-cfg",
    "cfg(emscripten_old_stat_abi)",
    "--check-cfg",
    "cfg(espidf_picolibc)",
    "--check-cfg",
    "cfg(espidf_time32)",
    "--check-cfg",
    "cfg(freebsd10)",
    "--check-cfg",
    "cfg(freebsd11)",
    "--check-cfg",
    "cfg(freebsd12)",
    "--check-cfg",
    "cfg(freebsd13)",
    "--check-cfg",
    "cfg(freebsd14)",
    "--check-cfg",
    "cfg(freebsd15)",
    "--check-cfg",
    "cfg(gnu_file_offset_bits64)",
    "--check-cfg",
    "cfg(gnu_time_bits64)",
    "--check-cfg",
    "cfg(libc_deny_warnings)",
    "--check-cfg",
    "cfg(linux_time_bits64)",
    "--check-cfg",
    "cfg(musl_v1_2_3)",
    "--check-cfg",
    "cfg(musl32_time64)",
    "--check-cfg",
    "cfg(musl_redir_time64)",
    "--check-cfg",
    "cfg(vxworks_lt_25_09)",
    "--check-cfg",
    "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\",\"qurt\"))",
    "--check-cfg",
    "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
    "--check-cfg",
    "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=de34c0666a4c6d46 -C extra-filename=-751e763eb72b7eae --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --cap-lints allow --cfg freebsd12 --check-cfg cfg(emscripten_old_stat_abi) --check-cfg cfg(espidf_picolibc) --check-cfg cfg(espidf_time32) --check-cfg cfg(freebsd10) --check-cfg cfg(freebsd11) --check-cfg cfg(freebsd12) --check-cfg cfg(freebsd13) --check-cfg cfg(freebsd14) --check-cfg cfg(freebsd15) --check-cfg cfg(gnu_file_offset_bits64) --check-cfg cfg(gnu_time_bits64) --check-cfg cfg(libc_deny_warnings) --check-cfg cfg(linux_time_bits64) --check-cfg cfg(musl_v1_2_3) --check-cfg cfg(musl32_time64) --check-cfg cfg(musl_redir_time64) --check-cfg cfg(vxworks_lt_25_09) --check-cfg \"cfg(target_os,values(\\\"switch\\\",\\\"aix\\\",\\\"ohos\\\",\\\"hurd\\\",\\\"rtems\\\",\\\"visionos\\\",\\\"nuttx\\\",\\\"cygwin\\\",\\\"qurt\\\"))\" --check-cfg \"cfg(target_env,values(\\\"illumos\\\",\\\"wasi\\\",\\\"aix\\\",\\\"ohos\\\",\\\"nto71_iosock\\\",\\\"nto80\\\"))\" --check-cfg \"cfg(target_arch,values(\\\"loongarch64\\\",\\\"mips32r6\\\",\\\"mips64r6\\\",\\\"csky\\\"))\"",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "libc",
    "--edition=2021",
    "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--allow=clippy::used_underscore_binding",
    "--allow=unused_qualifications",
    "--warn=clippy::unnecessary_semicolon",
    "--allow=clippy::unnecessary_cast",
    "--allow=clippy::uninlined_format_args",
    "--warn=clippy::ptr_as_ptr",
    "--allow=clippy::non_minimal_cfg",
    "--allow=clippy::missing_safety_doc",
    "--warn=clippy::map_unwrap_or",
    "--warn=clippy::manual_assert",
    "--allow=clippy::identity_op",
    "--warn=clippy::explicit_iter_loop",
    "--allow=clippy::expl_impl_clone_on_copy",
    "--cfg",
    "feature=\"default\"",
    "--cfg",
    "feature=\"std\"",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
    "-C",
    "metadata=de34c0666a4c6d46",
    "-C",
    "extra-filename=-751e763eb72b7eae",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--cap-lints",
    "allow",
    "--cfg",
    "freebsd12",
    "--check-cfg",
    "cfg(emscripten_old_stat_abi)",
    "--check-cfg",
    "cfg(espidf_picolibc)",
    "--check-cfg",
    "cfg(espidf_time32)",
    "--check-cfg",
    "cfg(freebsd10)",
    "--check-cfg",
    "cfg(freebsd11)",
    "--check-cfg",
    "cfg(freebsd12)",
    "--check-cfg",
    "cfg(freebsd13)",
    "--check-cfg",
    "cfg(freebsd14)",
    "--check-cfg",
    "cfg(freebsd15)",
    "--check-cfg",
    "cfg(gnu_file_offset_bits64)",
    "--check-cfg",
    "cfg(gnu_time_bits64)",
    "--check-cfg",
    "cfg(libc_deny_warnings)",
    "--check-cfg",
    "cfg(linux_time_bits64)",
    "--check-cfg",
    "cfg(musl_v1_2_3)",
    "--check-cfg",
    "cfg(musl32_time64)",
    "--check-cfg",
    "cfg(musl_redir_time64)",
    "--check-cfg",
    "cfg(vxworks_lt_25_09)",
    "--check-cfg",
    "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\",\"qurt\"))",
    "--check-cfg",
    "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
    "--check-cfg",
    "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:33.360842+00:00",
  "end_time": "2026-07-13T14:50:33.437870+00:00",
  "start_unix_nanos": 1783954233360841900,
  "end_unix_nanos": 1783954233437869700,
  "crate_name": "libc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
}
```

#### Record 122

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 13748,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2015",
    "build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"static\"))",
    "-C",
    "metadata=4f07c35b85d21d48",
    "-C",
    "extra-filename=-ac58be4c0227d725",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "--extern",
    "pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libpkg_config-3e67ae996f5d4ab8.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"static\\\"))\" -C metadata=4f07c35b85d21d48 -C extra-filename=-ac58be4c0227d725 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib --extern pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libpkg_config-3e67ae996f5d4ab8.rlib",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "build_script_build",
    "--edition=2015",
    "build.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "bin",
    "--emit=dep-info,link",
    "-C",
    "embed-bitcode=no",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"static\"))",
    "-C",
    "metadata=4f07c35b85d21d48",
    "-C",
    "extra-filename=-ac58be4c0227d725",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
    "--extern",
    "pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libpkg_config-3e67ae996f5d4ab8.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:33.812422+00:00",
  "end_time": "2026-07-13T14:50:34.093029+00:00",
  "start_unix_nanos": 1783954233812422200,
  "end_unix_nanos": 1783954234093029300,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725"
}
```

#### Record 123

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
  "root_process_pid": 9164,
  "pid": 4852,
  "ppid": 4080,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "bzip2_sys",
    "--edition=2015",
    "lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"static\"))",
    "-C",
    "metadata=b41de59d987f5ba8",
    "-C",
    "extra-filename=-c3840b29ee4080cf",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--extern",
    "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib",
    "-l",
    "static=bz2"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name bzip2_sys --edition=2015 lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"static\\\"))\" -C metadata=b41de59d987f5ba8 -C extra-filename=-c3840b29ee4080cf --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --extern libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib -l static=bz2",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "bzip2_sys",
    "--edition=2015",
    "lib.rs",
    "--error-format=json",
    "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
    "--crate-type",
    "lib",
    "--emit=dep-info,metadata,link",
    "-C",
    "embed-bitcode=no",
    "-C",
    "debuginfo=2",
    "--check-cfg",
    "cfg(docsrs,test)",
    "--check-cfg",
    "cfg(feature, values(\"static\"))",
    "-C",
    "metadata=b41de59d987f5ba8",
    "-C",
    "extra-filename=-c3840b29ee4080cf",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
    "--extern",
    "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib",
    "-l",
    "static=bz2"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:50:35.752937+00:00",
  "end_time": "2026-07-13T14:50:35.844438+00:00",
  "start_unix_nanos": 1783954235752937300,
  "end_unix_nanos": 1783954235844437500,
  "crate_name": "bzip2_sys",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:50:36.769812+00:00",
  "crate": "bzip2-sys",
  "version": "0.1.11+1.0.8",
  "duration_seconds": 26.51574940001592,
  "trace_record_count": 108,
  "trace_owner_summary": {
    "owner_package_count": 6,
    "owner_packages": [
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/Cargo.toml"
      },
      {
        "crate": "pkg-config",
        "version": "0.3.33",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.33",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "2.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml"
      }
    ],
    "attributed_event_count": 96,
    "unattributed_event_count": 12,
    "owners": [
      {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "event_count": 78,
        "kind_counts": {
          "exec": 11,
          "link": 10,
          "exec_context": 11,
          "resolved_link": 1,
          "used_input": 36,
          "compile": 7,
          "archive": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "event_count": 18,
        "kind_counts": {
          "exec": 1,
          "used_input": 13,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8"
      ],
      "packages": [
        {
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
          "name": "bzip2-sys",
          "version": "0.1.11+1.0.8",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
          "name": "cc",
          "version": "1.2.67",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
          "name": "find-msvc-tools",
          "version": "0.1.9",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.33",
          "name": "pkg-config",
          "version": "0.3.33",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1"
        }
      ]
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "exit_code": 0,
      "kind": "exec",
      "pid": 4720,
      "ppid": 11992,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:90ad33d1ed1d6121:2e05e811264381e5",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
      "pid": 4720,
      "sha256": "a6dba254d9446c1fcf0218b88a23f6c2072198565c24a06c942b27194d69a8d1",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:7c1eb5c1ad49f827:2e05e811264381e5",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
      "pid": 4720,
      "sha256": "bc10b3d4f9e70cd4b21eeaf3a249f7fe3c94bd8e8d2bbf2d42598ed147ce160b",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:653e09884864f05a:2e05e811264381e5",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
      "pid": 4720,
      "sha256": "ec02ee9a055e4ec6617677d1a0b6c039e4659b89eb2952e9bc9eba87ec772979",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:783ba13db5deceb3:2e05e811264381e5",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
      "pid": 4720,
      "sha256": "ff6efff4075e0da6e4767eda3aabf950aaf5c03d0e10e6a5f00c853fbf3b38eb",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:0d89bddccb7dce86:2e05e811264381e5",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
      "pid": 4720,
      "sha256": "a9cb0655191f6f00d39679a0a0eb749cbf6d83f64b3515275338daaf08a919b7",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:376e2a274745ad0b:2e05e811264381e5",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
      "pid": 4720,
      "sha256": "acdad7f98ed1b9cdbe26be386469cca0a840b203efc6807977f688b63ef3ca21",
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2e05e811264381e5",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "kernel32.lib",
      "pid": 4720,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2e05e811264381e5",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "kernel32.lib",
      "pid": 4720,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:2e05e811264381e5",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "kernel32.lib",
      "pid": 4720,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:1db9512c4d5c31e6:2e05e811264381e5",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "ntdll.lib",
      "pid": 4720,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:861f0814f9c52599:2e05e811264381e5",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "userenv.lib",
      "pid": 4720,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:50848825683fdca9:2e05e811264381e5",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "ws2_32.lib",
      "pid": 4720,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "used:link:e28a626e7bd4a22f:df7d4e53c08047f7:2e05e811264381e5",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "dbghelp.lib",
      "pid": 4720,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib"
      ],
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 4720,
      "ppid": 11992,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\rustcCrLW4v\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd-f6a1efc0b26a278e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libpanic_unwind-90f24475c2dadfb3.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcfg_if-2d70a11e4a249f4c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libwindows_link-a36b0a9019dd5e28.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_demangle-20df77ba1ccb827e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libstd_detect-72562e3bcf55d18a.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libhashbrown-379c2b5854b7942b.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_alloc-0fc8fdb483aa915c.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libunwind-63d02d00483a3a96.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\librustc_std_workspace_core-f5fff62847b8386e.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\liballoc-4007f5acb6859617.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcore-d378bf52e32e9198.rlib",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\x86_64-pc-windows-msvc\\lib\\libcompiler_builtins-0cdac2e568b3eee7.rlib",
        "kernel32.lib",
        "kernel32.lib",
        "kernel32.lib",
        "ntdll.lib",
        "userenv.lib",
        "ws2_32.lib",
        "dbghelp.lib",
        "/defaultlib:msvcrt",
        "/NXCOMPAT",
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
        "/OPT:REF,NOICF",
        "/DEBUG",
        "/PDBALTPATH:%_PDB%",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\intrinsic.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\liballoc.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libcore.natvis",
        "/NATVIS:C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\lib\\rustlib\\etc\\libstd.natvis"
      ],
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "directories": [
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       ",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
          "kind": "library",
          "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\msvcrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
          "kind": "library",
          "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\vcruntime.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000200       \\177KERNEL32_NULL_THUNK_DATA 0000000140039200     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000250       \\177VCRUNTIME140_NULL_THUNK_DATA 0000000140039250     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000270       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 0000000140039270     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000288       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 0000000140039288     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000298       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 0000000140039298     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:000002a8       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400392a8     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000340       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 0000000140039340     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000358       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 0000000140039358     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\0002:00000388       \\177ntdll_NULL_THUNK_DATA  0000000140039388     ntdll:ntdll.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-link-link-4720-1783954233132752400.map",
      "pid": 4720,
      "ppid": 11992,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-link-link-4720-1783954233132752400.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17376,
      "ppid": 15160,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 17376,
      "ppid": 15160,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\rustcuMd0Np\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000300       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000320       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000003f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000418       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000448       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000460       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
          "kind": "library",
          "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\msvcrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
          "kind": "library",
          "path": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64\\vcruntime.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400f0020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400f0298     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400f02b0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000300       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400f0300     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000320       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400f0320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400f0338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400f0348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400f0358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000003f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400f03f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400f0408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000418       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400f0418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000448       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400f0448     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000460       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400f0460     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-link-link-17376-1783954233917209200.map",
      "pid": 17376,
      "ppid": 15160,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-link-link-17376-1783954233917209200.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 3272,
      "ppid": 16340,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:49e0e4242770f08d:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c",
      "pid": 3272,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\9567505575489908734detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "pid": 3272,
      "ppid": 16340,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 7364,
      "ppid": 16340,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "pid": 7364,
      "ppid": 16340,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "-c",
        "bzip2-1.0.8/blocksort.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 3680,
      "ppid": 16340,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "-c",
        "bzip2-1.0.8/blocksort.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:78e6ee6a1370cecc:da5c17eda2344a86",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
      "path": "bzip2-1.0.8/blocksort.c",
      "pid": 3680,
      "sha256": "4e48cd2ccff44699e67a7c949b0e9576c05b8dcbe20f863475c4fcc8db11a409",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "-c",
        "bzip2-1.0.8/blocksort.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:b0e1265788dbddd5:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
      "pid": 3680,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "-c",
        "bzip2-1.0.8/blocksort.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:78e6ee6a1370cecc:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "bzip2-1.0.8/blocksort.c",
      "pid": 3680,
      "sha256": "4e48cd2ccff44699e67a7c949b0e9576c05b8dcbe20f863475c4fcc8db11a409",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "-c",
        "bzip2-1.0.8/blocksort.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
      "src": "bzip2-1.0.8/blocksort.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "-c",
        "bzip2-1.0.8/blocksort.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "bzip2-1.0.8/blocksort.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "-c",
        "bzip2-1.0.8/blocksort.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "pid": 3680,
      "ppid": 16340,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "-c",
        "bzip2-1.0.8/huffman.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 13172,
      "ppid": 16340,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "-c",
        "bzip2-1.0.8/huffman.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:e8fcc6136ffc09e2:02c4f6834e896e06",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
      "path": "bzip2-1.0.8/huffman.c",
      "pid": 13172,
      "sha256": "bdeb45f3f535546a672811b68aa87cc58fd395b28ecebc34fa3566a656a4d1d1",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "-c",
        "bzip2-1.0.8/huffman.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:2e1b0d2c22538668:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
      "pid": 13172,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "-c",
        "bzip2-1.0.8/huffman.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:e8fcc6136ffc09e2:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "bzip2-1.0.8/huffman.c",
      "pid": 13172,
      "sha256": "bdeb45f3f535546a672811b68aa87cc58fd395b28ecebc34fa3566a656a4d1d1",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "-c",
        "bzip2-1.0.8/huffman.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
      "src": "bzip2-1.0.8/huffman.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "-c",
        "bzip2-1.0.8/huffman.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "bzip2-1.0.8/huffman.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "-c",
        "bzip2-1.0.8/huffman.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "pid": 13172,
      "ppid": 16340,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "-c",
        "bzip2-1.0.8/crctable.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 10744,
      "ppid": 16340,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "-c",
        "bzip2-1.0.8/crctable.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:d4f7e42684e06817:413789dbb2467bc1",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
      "path": "bzip2-1.0.8/crctable.c",
      "pid": 10744,
      "sha256": "2fb7a564629386456e731f431a5cf4f5026747bace4cd10be8f5ecf082066a92",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "-c",
        "bzip2-1.0.8/crctable.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:70cb3ac631e18aff:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
      "pid": 10744,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "-c",
        "bzip2-1.0.8/crctable.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:d4f7e42684e06817:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "bzip2-1.0.8/crctable.c",
      "pid": 10744,
      "sha256": "2fb7a564629386456e731f431a5cf4f5026747bace4cd10be8f5ecf082066a92",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "-c",
        "bzip2-1.0.8/crctable.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
      "src": "bzip2-1.0.8/crctable.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "-c",
        "bzip2-1.0.8/crctable.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "bzip2-1.0.8/crctable.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "-c",
        "bzip2-1.0.8/crctable.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "pid": 10744,
      "ppid": 16340,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "-c",
        "bzip2-1.0.8/randtable.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 9468,
      "ppid": 16340,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "-c",
        "bzip2-1.0.8/randtable.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:2cdfec052db3836b:4e763192af6f71a8",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
      "path": "bzip2-1.0.8/randtable.c",
      "pid": 9468,
      "sha256": "407054ca6f54cd737dbc26ceb6b7874b55a0fcff86c2eb23cbec2fbdbb884815",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "-c",
        "bzip2-1.0.8/randtable.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:6626e14ba36726f7:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
      "pid": 9468,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "-c",
        "bzip2-1.0.8/randtable.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:2cdfec052db3836b:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "bzip2-1.0.8/randtable.c",
      "pid": 9468,
      "sha256": "407054ca6f54cd737dbc26ceb6b7874b55a0fcff86c2eb23cbec2fbdbb884815",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "-c",
        "bzip2-1.0.8/randtable.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
      "src": "bzip2-1.0.8/randtable.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "-c",
        "bzip2-1.0.8/randtable.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "bzip2-1.0.8/randtable.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "-c",
        "bzip2-1.0.8/randtable.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "pid": 9468,
      "ppid": 16340,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "-c",
        "bzip2-1.0.8/compress.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17136,
      "ppid": 16340,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "-c",
        "bzip2-1.0.8/compress.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:25376ab909f1353b:aa1206ea0a7caecc",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
      "path": "bzip2-1.0.8/compress.c",
      "pid": 17136,
      "sha256": "75995bd6e8c5f1e1dad05178f3cf53137df99ce860a1984324f78591f28deed3",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "-c",
        "bzip2-1.0.8/compress.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:41fa8ab89b033abb:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
      "pid": 17136,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "-c",
        "bzip2-1.0.8/compress.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:25376ab909f1353b:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "bzip2-1.0.8/compress.c",
      "pid": 17136,
      "sha256": "75995bd6e8c5f1e1dad05178f3cf53137df99ce860a1984324f78591f28deed3",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "-c",
        "bzip2-1.0.8/compress.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
      "src": "bzip2-1.0.8/compress.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "-c",
        "bzip2-1.0.8/compress.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "bzip2-1.0.8/compress.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "-c",
        "bzip2-1.0.8/compress.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "pid": 17136,
      "ppid": 16340,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "-c",
        "bzip2-1.0.8/decompress.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 16520,
      "ppid": 16340,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "-c",
        "bzip2-1.0.8/decompress.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:64b0fa5304cc159d:9cda31fe85fb49f1",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
      "path": "bzip2-1.0.8/decompress.c",
      "pid": 16520,
      "sha256": "31a89f8bf408ef0e4acae83e8be60a8eb4edece6c866d6e32b8f7e557ca54bc6",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "-c",
        "bzip2-1.0.8/decompress.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:e76d25979b79011f:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
      "pid": 16520,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "-c",
        "bzip2-1.0.8/decompress.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:64b0fa5304cc159d:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "bzip2-1.0.8/decompress.c",
      "pid": 16520,
      "sha256": "31a89f8bf408ef0e4acae83e8be60a8eb4edece6c866d6e32b8f7e557ca54bc6",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "-c",
        "bzip2-1.0.8/decompress.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
      "src": "bzip2-1.0.8/decompress.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "-c",
        "bzip2-1.0.8/decompress.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "bzip2-1.0.8/decompress.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "-c",
        "bzip2-1.0.8/decompress.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "pid": 16520,
      "ppid": 16340,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
        "-c",
        "bzip2-1.0.8/bzlib.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 4640,
      "ppid": 16340,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
        "-c",
        "bzip2-1.0.8/bzlib.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:85c0217da365dccb:0aee49091e7f0bd3",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
      "path": "bzip2-1.0.8/bzlib.c",
      "pid": 4640,
      "sha256": "d06cf1bd991df1f2dc8ef4f7713d186eb636767111cbd4807ef5fc4a54ca6838",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
        "-c",
        "bzip2-1.0.8/bzlib.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:4c2f27ac0878f5d8:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
      "pid": 4640,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
        "-c",
        "bzip2-1.0.8/bzlib.c"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:cl:5488b1e276495a54:85c0217da365dccb:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "bzip2-1.0.8/bzlib.c",
      "pid": 4640,
      "sha256": "d06cf1bd991df1f2dc8ef4f7713d186eb636767111cbd4807ef5fc4a54ca6838",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
        "-c",
        "bzip2-1.0.8/bzlib.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
      "src": "bzip2-1.0.8/bzlib.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
        "-c",
        "bzip2-1.0.8/bzlib.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
        "bzip2-1.0.8/bzlib.c"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": null,
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-Z7",
        "-Brepro",
        "-I",
        "bzip2-1.0.8",
        "-W0",
        "-D_WIN32",
        "-DBZ_EXPORT",
        "-D_FILE_OFFSET_BITS=64",
        "-DBZ_NO_STDIO",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
        "-c",
        "bzip2-1.0.8/bzlib.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "pid": 4640,
      "ppid": 16340,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "exec",
      "pid": 6708,
      "ppid": 16340,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:da5c17eda2344a86:eab349e2bc26e393",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
      "pid": 6708,
      "sha256": "9a0ec0880bc85982f60d6711ffa5bc55579fb316e8f18222f60c8001da13e238",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:02c4f6834e896e06:eab349e2bc26e393",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
      "pid": 6708,
      "sha256": "8f2966958c4fc17d6588a45cd38c408357f82b282e27e6bfa9dbea33b46fca82",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:413789dbb2467bc1:eab349e2bc26e393",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
      "pid": 6708,
      "sha256": "a6d1832ebead72f44c22c01aea45418dd6fd4ebba2d142dcb7ba90c42b8ba771",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:4e763192af6f71a8:eab349e2bc26e393",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
      "pid": 6708,
      "sha256": "2704eb689c76cac0692d4e333563c69e003abc086ca7e28ef07c86bd3be5bb73",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:aa1206ea0a7caecc:eab349e2bc26e393",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
      "pid": 6708,
      "sha256": "278f30119bf02d2ece80d3166a5b41b5db6fcf7e248a05954a749856d499d4e4",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:9cda31fe85fb49f1:eab349e2bc26e393",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
      "pid": 6708,
      "sha256": "2d6d8ec25dad5c85d3e3d04a1f6a342441a4ccc331d2fa135940568a0cba07f3",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:0aee49091e7f0bd3:eab349e2bc26e393",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
      "pid": 6708,
      "sha256": "a31d906a14ae396e85096add1e8ce2cadc4102ba7036b12d08f719a0ab86f373",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:da5c17eda2344a86:66abe07a8169e0e6",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
      "pid": 6708,
      "sha256": "9a0ec0880bc85982f60d6711ffa5bc55579fb316e8f18222f60c8001da13e238",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:02c4f6834e896e06:66abe07a8169e0e6",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
      "pid": 6708,
      "sha256": "8f2966958c4fc17d6588a45cd38c408357f82b282e27e6bfa9dbea33b46fca82",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:413789dbb2467bc1:66abe07a8169e0e6",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
      "pid": 6708,
      "sha256": "a6d1832ebead72f44c22c01aea45418dd6fd4ebba2d142dcb7ba90c42b8ba771",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:4e763192af6f71a8:66abe07a8169e0e6",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
      "pid": 6708,
      "sha256": "2704eb689c76cac0692d4e333563c69e003abc086ca7e28ef07c86bd3be5bb73",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:aa1206ea0a7caecc:66abe07a8169e0e6",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
      "pid": 6708,
      "sha256": "278f30119bf02d2ece80d3166a5b41b5db6fcf7e248a05954a749856d499d4e4",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:9cda31fe85fb49f1:66abe07a8169e0e6",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
      "pid": 6708,
      "sha256": "2d6d8ec25dad5c85d3e3d04a1f6a342441a4ccc331d2fa135940568a0cba07f3",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "used:lib:5488b1e276495a54:0aee49091e7f0bd3:66abe07a8169e0e6",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o",
      "pid": 6708,
      "sha256": "a31d906a14ae396e85096add1e8ce2cadc4102ba7036b12d08f719a0ab86f373",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\libbz2.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-blocksort.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-huffman.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-crctable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-randtable.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-compress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-decompress.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib\\a9dc8ba631b1466a-bzlib.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "cargo_pkg_name": "bzip2-sys",
      "cargo_pkg_version": "0.1.11+1.0.8",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "pid": 6708,
      "ppid": 16340,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "bzip2-sys",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "event_id": "bsrun:152c70d20f7ea708:3643d6ae074f55c5:be29f52f1add074c",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "0.1.11+1.0.8",
      "_owner": {
        "crate": "bzip2-sys",
        "version": "0.1.11+1.0.8",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8#bzip2-sys@0.1.11+1.0.8",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "bsrun:a733304fa0307800:b7dbb3665b8070c3:8a254808bef4b34d",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/target/debug/build/libc-763fb040b2d663ab\\build-script-build.exe",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-s0gqjxr5/src/bzip2-sys-0.1.11+1.0.8/target/debug/build/libc-763fb040b2d663ab/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "success": true,
      "target": null,
      "version": "0.2.186",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cwd_prefix"
      }
    },
    {
      "event": "process_tracer_diagnostic",
      "platform": "windows_etw",
      "phase": "realtime",
      "argv": [],
      "spawn_error": null,
      "exit_status": null,
      "stdout": "",
      "stderr": "",
      "raw_event_count": 5492,
      "parsed_event_count": 5492,
      "parse_error_count": 0,
      "command_line_event_count": 5492,
      "build_script_root_event_count": 102,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 504,
      "dropped_event_count": 2867
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12896,
      "ppid": 4080,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:50:33.320096+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
      "root_cargo_pid": 9164,
      "build_script_root_pid": 12896,
      "build_script_related": true,
      "build_script_target_dir": "libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 536,
      "ppid": 12896,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
      ],
      "comm": "rustc-trace-wrapper.exe",
      "time": "2026-07-13T14:50:33.328557+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "root_cargo_pid": 9164,
      "build_script_root_pid": 12896,
      "build_script_related": true,
      "build_script_target_dir": "libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13552,
      "ppid": 536,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:50:33.337752+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 9164,
      "build_script_root_pid": 12896,
      "build_script_related": true,
      "build_script_target_dir": "libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16340,
      "ppid": 4080,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:50:34.246049+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725\\build-script-build.exe",
      "root_cargo_pid": 9164,
      "build_script_root_pid": 16340,
      "build_script_related": true,
      "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 3272,
      "ppid": 16340,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:50:34.336275+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
      "root_cargo_pid": 9164,
      "build_script_root_pid": 16340,
      "build_script_related": true,
      "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 5936,
      "ppid": 3272,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:50:34.344558+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 9164,
      "build_script_root_pid": 16340,
      "build_script_related": true,
      "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 7364,
      "ppid": 16340,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:50:34.374402+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
      "root_cargo_pid": 9164,
      "build_script_root_pid": 16340,
      "build_script_related": true,
      "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 6116,
      "ppid": 7364,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:50:34.379653+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 9164,
      "build_script_root_pid": 16340,
      "build_script_related": true,
      "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 3680,
      "ppid": 16340,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:50:34.421567+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\.tmp\\native-trace-14128-1783954232469\\shims\\cl.exe",
      "root_cargo_pid": 9164,
      "build_script_root_pid": 16340,
      "build_script_related": true,
      "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12112,
      "ppid": 3680,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:50:34.426893+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 9164,
      "build_script_root_pid": 16340,
      "build_script_related": true,
      "build_script_target_dir": "bzip2-sys-ac58be4c0227d725"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 4780,
      "ppid": 12252,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:32.647794+00:00",
      "end_time": "2026-07-13T14:50:32.664221+00:00",
      "start_unix_nanos": 1783954232647793700,
      "end_unix_nanos": 1783954232664220700,
      "crate_name": null,
      "crate_type": [],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 10500,
      "ppid": 12252,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-",
        "--crate-name",
        "___",
        "--print=file-names",
        "--crate-type",
        "bin",
        "--crate-type",
        "rlib",
        "--crate-type",
        "dylib",
        "--crate-type",
        "cdylib",
        "--crate-type",
        "staticlib",
        "--crate-type",
        "proc-macro",
        "--print=sysroot",
        "--print=split-debuginfo",
        "--print=crate-name",
        "--print=cfg",
        "-Wwarnings"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name --print=cfg -Wwarnings",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-",
        "--crate-name",
        "___",
        "--print=file-names",
        "--crate-type",
        "bin",
        "--crate-type",
        "rlib",
        "--crate-type",
        "dylib",
        "--crate-type",
        "cdylib",
        "--crate-type",
        "staticlib",
        "--crate-type",
        "proc-macro",
        "--print=sysroot",
        "--print=split-debuginfo",
        "--print=crate-name",
        "--print=cfg",
        "-Wwarnings"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:32.670097+00:00",
      "end_time": "2026-07-13T14:50:32.689003+00:00",
      "start_unix_nanos": 1783954232670096900,
      "end_unix_nanos": 1783954232689002900,
      "crate_name": "___",
      "crate_type": [
        "bin",
        "rlib",
        "dylib",
        "cdylib",
        "staticlib",
        "proc-macro"
      ],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 11316,
      "ppid": 12252,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:32.810870+00:00",
      "end_time": "2026-07-13T14:50:32.828557+00:00",
      "start_unix_nanos": 1783954232810870100,
      "end_unix_nanos": 1783954232828557500,
      "crate_name": null,
      "crate_type": [],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 4528,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:32.881478+00:00",
      "end_time": "2026-07-13T14:50:32.899371+00:00",
      "start_unix_nanos": 1783954232881477900,
      "end_unix_nanos": 1783954232899370600,
      "crate_name": null,
      "crate_type": [],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 2652,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-",
        "--crate-name",
        "___",
        "--print=file-names",
        "--crate-type",
        "bin",
        "--crate-type",
        "rlib",
        "--crate-type",
        "dylib",
        "--crate-type",
        "cdylib",
        "--crate-type",
        "staticlib",
        "--crate-type",
        "proc-macro",
        "--print=sysroot",
        "--print=split-debuginfo",
        "--print=crate-name",
        "--print=cfg",
        "-Wwarnings"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name --print=cfg -Wwarnings",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-",
        "--crate-name",
        "___",
        "--print=file-names",
        "--crate-type",
        "bin",
        "--crate-type",
        "rlib",
        "--crate-type",
        "dylib",
        "--crate-type",
        "cdylib",
        "--crate-type",
        "staticlib",
        "--crate-type",
        "proc-macro",
        "--print=sysroot",
        "--print=split-debuginfo",
        "--print=crate-name",
        "--print=cfg",
        "-Wwarnings"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:32.905426+00:00",
      "end_time": "2026-07-13T14:50:32.926229+00:00",
      "start_unix_nanos": 1783954232905426000,
      "end_unix_nanos": 1783954232926228800,
      "crate_name": "___",
      "crate_type": [
        "bin",
        "rlib",
        "dylib",
        "cdylib",
        "staticlib",
        "proc-macro"
      ],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 15424,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe -vV",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "-vV"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:32.936749+00:00",
      "end_time": "2026-07-13T14:50:32.954418+00:00",
      "start_unix_nanos": 1783954232936748400,
      "end_unix_nanos": 1783954232954418400,
      "crate_name": null,
      "crate_type": [],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 16844,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "find_msvc_tools",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=a199b1cb5e329831",
        "-C",
        "extra-filename=-824f9ded730dd358",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "find_msvc_tools",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=a199b1cb5e329831",
        "-C",
        "extra-filename=-824f9ded730dd358",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:32.971812+00:00",
      "end_time": "2026-07-13T14:50:33.347677+00:00",
      "start_unix_nanos": 1783954232971812400,
      "end_unix_nanos": 1783954233347676400,
      "crate_name": "find_msvc_tools",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 10504,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "shlex",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--warn=unexpected_cfgs",
        "--check-cfg",
        "cfg(manual_codegen_check)",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=181708ecadab3b47",
        "-C",
        "extra-filename=-f9df91f0b2c0ecd4",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "shlex",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--warn=unexpected_cfgs",
        "--check-cfg",
        "cfg(manual_codegen_check)",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"default\", \"std\"))",
        "-C",
        "metadata=181708ecadab3b47",
        "-C",
        "extra-filename=-f9df91f0b2c0ecd4",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:32.973944+00:00",
      "end_time": "2026-07-13T14:50:33.084065+00:00",
      "start_unix_nanos": 1783954232973943700,
      "end_unix_nanos": 1783954233084065500,
      "crate_name": "shlex",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 10488,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=0add1c4e1ef78d62",
        "-C",
        "extra-filename=-763fb040b2d663ab",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=0add1c4e1ef78d62 -C extra-filename=-763fb040b2d663ab --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=0add1c4e1ef78d62",
        "-C",
        "extra-filename=-763fb040b2d663ab",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:32.976263+00:00",
      "end_time": "2026-07-13T14:50:33.243261+00:00",
      "start_unix_nanos": 1783954232976263400,
      "end_unix_nanos": 1783954233243260900,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 7560,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "pkg_config",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=850bf69d60833204",
        "-C",
        "extra-filename=-3e67ae996f5d4ab8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name pkg_config --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=850bf69d60833204 -C extra-filename=-3e67ae996f5d4ab8 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "pkg_config",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\pkg-config-0.3.33\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values())",
        "-C",
        "metadata=850bf69d60833204",
        "-C",
        "extra-filename=-3e67ae996f5d4ab8",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:32.978694+00:00",
      "end_time": "2026-07-13T14:50:33.227503+00:00",
      "start_unix_nanos": 1783954232978694200,
      "end_unix_nanos": 1783954233227502800,
      "crate_name": "pkg_config",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 9496,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"jobserver\", \"parallel\"))",
        "-C",
        "metadata=98547e1a4afb2a03",
        "-C",
        "extra-filename=-24e0405f325d0f68",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "cc",
        "--edition=2018",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "--allow=unexpected_cfgs",
        "--check-cfg",
        "cfg(disable_clang_cl_tests)",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"jobserver\", \"parallel\"))",
        "-C",
        "metadata=98547e1a4afb2a03",
        "-C",
        "extra-filename=-24e0405f325d0f68",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:33.186785+00:00",
      "end_time": "2026-07-13T14:50:33.797933+00:00",
      "start_unix_nanos": 1783954233186785300,
      "end_unix_nanos": 1783954233797932700,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 536,
      "ppid": 12896,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--version"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --version",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--version"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:33.333166+00:00",
      "end_time": "2026-07-13T14:50:33.350063+00:00",
      "start_unix_nanos": 1783954233333165800,
      "end_unix_nanos": 1783954233350063000,
      "crate_name": null,
      "crate_type": [],
      "out_dir": null
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 16584,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libc",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=de34c0666a4c6d46",
        "-C",
        "extra-filename=-751e763eb72b7eae",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "--cfg",
        "freebsd12",
        "--check-cfg",
        "cfg(emscripten_old_stat_abi)",
        "--check-cfg",
        "cfg(espidf_picolibc)",
        "--check-cfg",
        "cfg(espidf_time32)",
        "--check-cfg",
        "cfg(freebsd10)",
        "--check-cfg",
        "cfg(freebsd11)",
        "--check-cfg",
        "cfg(freebsd12)",
        "--check-cfg",
        "cfg(freebsd13)",
        "--check-cfg",
        "cfg(freebsd14)",
        "--check-cfg",
        "cfg(freebsd15)",
        "--check-cfg",
        "cfg(gnu_file_offset_bits64)",
        "--check-cfg",
        "cfg(gnu_time_bits64)",
        "--check-cfg",
        "cfg(libc_deny_warnings)",
        "--check-cfg",
        "cfg(linux_time_bits64)",
        "--check-cfg",
        "cfg(musl_v1_2_3)",
        "--check-cfg",
        "cfg(musl32_time64)",
        "--check-cfg",
        "cfg(musl_redir_time64)",
        "--check-cfg",
        "cfg(vxworks_lt_25_09)",
        "--check-cfg",
        "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\",\"qurt\"))",
        "--check-cfg",
        "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
        "--check-cfg",
        "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=de34c0666a4c6d46 -C extra-filename=-751e763eb72b7eae --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --cap-lints allow --cfg freebsd12 --check-cfg cfg(emscripten_old_stat_abi) --check-cfg cfg(espidf_picolibc) --check-cfg cfg(espidf_time32) --check-cfg cfg(freebsd10) --check-cfg cfg(freebsd11) --check-cfg cfg(freebsd12) --check-cfg cfg(freebsd13) --check-cfg cfg(freebsd14) --check-cfg cfg(freebsd15) --check-cfg cfg(gnu_file_offset_bits64) --check-cfg cfg(gnu_time_bits64) --check-cfg cfg(libc_deny_warnings) --check-cfg cfg(linux_time_bits64) --check-cfg cfg(musl_v1_2_3) --check-cfg cfg(musl32_time64) --check-cfg cfg(musl_redir_time64) --check-cfg cfg(vxworks_lt_25_09) --check-cfg \"cfg(target_os,values(\\\"switch\\\",\\\"aix\\\",\\\"ohos\\\",\\\"hurd\\\",\\\"rtems\\\",\\\"visionos\\\",\\\"nuttx\\\",\\\"cygwin\\\",\\\"qurt\\\"))\" --check-cfg \"cfg(target_env,values(\\\"illumos\\\",\\\"wasi\\\",\\\"aix\\\",\\\"ohos\\\",\\\"nto71_iosock\\\",\\\"nto80\\\"))\" --check-cfg \"cfg(target_arch,values(\\\"loongarch64\\\",\\\"mips32r6\\\",\\\"mips64r6\\\",\\\"csky\\\"))\"",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "libc",
        "--edition=2021",
        "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--allow=clippy::used_underscore_binding",
        "--allow=unused_qualifications",
        "--warn=clippy::unnecessary_semicolon",
        "--allow=clippy::unnecessary_cast",
        "--allow=clippy::uninlined_format_args",
        "--warn=clippy::ptr_as_ptr",
        "--allow=clippy::non_minimal_cfg",
        "--allow=clippy::missing_safety_doc",
        "--warn=clippy::map_unwrap_or",
        "--warn=clippy::manual_assert",
        "--allow=clippy::identity_op",
        "--warn=clippy::explicit_iter_loop",
        "--allow=clippy::expl_impl_clone_on_copy",
        "--cfg",
        "feature=\"default\"",
        "--cfg",
        "feature=\"std\"",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"align\", \"const-extern-fn\", \"default\", \"extra_traits\", \"rustc-dep-of-std\", \"rustc-std-workspace-core\", \"std\", \"use_std\"))",
        "-C",
        "metadata=de34c0666a4c6d46",
        "-C",
        "extra-filename=-751e763eb72b7eae",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--cap-lints",
        "allow",
        "--cfg",
        "freebsd12",
        "--check-cfg",
        "cfg(emscripten_old_stat_abi)",
        "--check-cfg",
        "cfg(espidf_picolibc)",
        "--check-cfg",
        "cfg(espidf_time32)",
        "--check-cfg",
        "cfg(freebsd10)",
        "--check-cfg",
        "cfg(freebsd11)",
        "--check-cfg",
        "cfg(freebsd12)",
        "--check-cfg",
        "cfg(freebsd13)",
        "--check-cfg",
        "cfg(freebsd14)",
        "--check-cfg",
        "cfg(freebsd15)",
        "--check-cfg",
        "cfg(gnu_file_offset_bits64)",
        "--check-cfg",
        "cfg(gnu_time_bits64)",
        "--check-cfg",
        "cfg(libc_deny_warnings)",
        "--check-cfg",
        "cfg(linux_time_bits64)",
        "--check-cfg",
        "cfg(musl_v1_2_3)",
        "--check-cfg",
        "cfg(musl32_time64)",
        "--check-cfg",
        "cfg(musl_redir_time64)",
        "--check-cfg",
        "cfg(vxworks_lt_25_09)",
        "--check-cfg",
        "cfg(target_os,values(\"switch\",\"aix\",\"ohos\",\"hurd\",\"rtems\",\"visionos\",\"nuttx\",\"cygwin\",\"qurt\"))",
        "--check-cfg",
        "cfg(target_env,values(\"illumos\",\"wasi\",\"aix\",\"ohos\",\"nto71_iosock\",\"nto80\"))",
        "--check-cfg",
        "cfg(target_arch,values(\"loongarch64\",\"mips32r6\",\"mips64r6\",\"csky\"))"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:33.360842+00:00",
      "end_time": "2026-07-13T14:50:33.437870+00:00",
      "start_unix_nanos": 1783954233360841900,
      "end_unix_nanos": 1783954233437869700,
      "crate_name": "libc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 13748,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2015",
        "build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"static\"))",
        "-C",
        "metadata=4f07c35b85d21d48",
        "-C",
        "extra-filename=-ac58be4c0227d725",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "--extern",
        "pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libpkg_config-3e67ae996f5d4ab8.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"static\\\"))\" -C metadata=4f07c35b85d21d48 -C extra-filename=-ac58be4c0227d725 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib --extern pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libpkg_config-3e67ae996f5d4ab8.rlib",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "build_script_build",
        "--edition=2015",
        "build.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "bin",
        "--emit=dep-info,link",
        "-C",
        "embed-bitcode=no",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"static\"))",
        "-C",
        "metadata=4f07c35b85d21d48",
        "-C",
        "extra-filename=-ac58be4c0227d725",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
        "--extern",
        "pkg_config=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\libpkg_config-3e67ae996f5d4ab8.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:33.812422+00:00",
      "end_time": "2026-07-13T14:50:34.093029+00:00",
      "start_unix_nanos": 1783954233812422200,
      "end_unix_nanos": 1783954234093029300,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-ac58be4c0227d725"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "bzip2-sys:0.1.11+1.0.8:2896",
      "root_process_pid": 9164,
      "pid": 4852,
      "ppid": 4080,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "bzip2_sys",
        "--edition=2015",
        "lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"static\"))",
        "-C",
        "metadata=b41de59d987f5ba8",
        "-C",
        "extra-filename=-c3840b29ee4080cf",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--extern",
        "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib",
        "-l",
        "static=bz2"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name bzip2_sys --edition=2015 lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"static\\\"))\" -C metadata=b41de59d987f5ba8 -C extra-filename=-c3840b29ee4080cf --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps --extern libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib -l static=bz2",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "bzip2_sys",
        "--edition=2015",
        "lib.rs",
        "--error-format=json",
        "--json=diagnostic-rendered-ansi,artifacts,future-incompat",
        "--crate-type",
        "lib",
        "--emit=dep-info,metadata,link",
        "-C",
        "embed-bitcode=no",
        "-C",
        "debuginfo=2",
        "--check-cfg",
        "cfg(docsrs,test)",
        "--check-cfg",
        "cfg(feature, values(\"static\"))",
        "-C",
        "metadata=b41de59d987f5ba8",
        "-C",
        "extra-filename=-c3840b29ee4080cf",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps",
        "--extern",
        "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\build\\bzip2-sys-a53f7c14e427c16f\\out\\lib",
        "-l",
        "static=bz2"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:50:35.752937+00:00",
      "end_time": "2026-07-13T14:50:35.844438+00:00",
      "start_unix_nanos": 1783954235752937300,
      "end_unix_nanos": 1783954235844437500,
      "crate_name": "bzip2_sys",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-s0gqjxr5\\src\\bzip2-sys-0.1.11+1.0.8\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 466,
    "crate": "bzip2-sys",
    "version": "0.1.11+1.0.8",
    "crate_id": "76",
    "version_id": "388093",
    "downloads": 67231508,
    "cumulative_downloads": 68843927212,
    "cumulative_share_of_global": 0.2573915508247319,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "build.rs",
    "build_script_exists": true,
    "package_build_field": "build.rs",
    "build_script_reason": "package_build_path",
    "download_source": "local"
  }
}
```
