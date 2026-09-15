# `lz4-sys` `1.11.1+lz4-1.10.0`

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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
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
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "-c",
    "liblz4/lib/lz4.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "liblz4/lib/lz4.c"
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
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "-c",
    "liblz4/lib/lz4frame.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "liblz4/lib/lz4frame.c"
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
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "-c",
    "liblz4/lib/lz4hc.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "liblz4/lib/lz4hc.c"
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
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "-c",
    "liblz4/lib/xxhash.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "liblz4/lib/xxhash.c"
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
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 7

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

### Other root-owned resolved-link records

#### Record 1

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400d2020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400d2298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400d22b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400d2300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400d2320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400d2338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400d2348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400d2358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400d23f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400d2408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400d2418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400d2448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400d2460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-link-link-13692-1783954392811796600.map",
  "pid": 13692,
  "ppid": 7404,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-link-link-13692-1783954392811796600.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/target/debug/build/lz4-sys-8877f31bf4edc40f/out/liblz4.a`

Owner: `lz4-sys` `1.11.1+lz4-1.10.0`

### Source files

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4frame.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/lz4hc.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/liblz4/lib/xxhash.c`

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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "-c",
    "liblz4/lib/lz4hc.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
  "src": "liblz4/lib/lz4hc.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "-c",
    "liblz4/lib/lz4frame.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
  "src": "liblz4/lib/lz4frame.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "-c",
    "liblz4/lib/xxhash.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
  "src": "liblz4/lib/xxhash.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "-c",
    "liblz4/lib/lz4.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
  "src": "liblz4/lib/lz4.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

### Archive records

#### Record 1

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
  "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "cargo_args": [
    "build"
  ],
  "workspace_default_members": [
    "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0"
  ],
  "packages": [
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
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
      "name": "lz4-sys",
      "version": "1.11.1+lz4-1.10.0",
      "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Cargo.toml",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0"
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "pid": 9644,
  "ppid": 5572,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:a8055f2f9e1d22f7:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:b3b69b375c45dace:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:b9c140a537c1b83a:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:74c40562cb45ab56:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:525892dd6b5c2a1f:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:0b9d3a9765f4bfdb:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "kernel32.lib",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "kernel32.lib",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "kernel32.lib",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:1db9512c4d5c31e6:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "ntdll.lib",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:861f0814f9c52599:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "userenv.lib",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:50848825683fdca9:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "ws2_32.lib",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "event_id": "used:link:e28a626e7bd4a22f:df7d4e53c08047f7:ab0d29e1acb7c4cd",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "static_library",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
  "path": "dbghelp.lib",
  "pid": 9644,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o"
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
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 9644,
  "ppid": 5572,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "/NOLOGO",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
    "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-link-link-9644-1783954392037965600.map",
  "pid": 9644,
  "ppid": 5572,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-link-link-9644-1783954392037965600.map"
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 13692,
  "ppid": 7404,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "link",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 13692,
  "ppid": 7404,
  "profile": null,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "success": true,
  "target": null,
  "tool": "link",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
    "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "directories": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
    "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000020       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000298       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000002b0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000300       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000320       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000338       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000348       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000358       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000003f0       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000408       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000418       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000448       ",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000460       "
  ],
  "exit_code": 0,
  "inputs": [
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
      "kind": "library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
      "source": "link_trace"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000020       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400d2020     advapi32:ADVAPI32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000298       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400d2298     kernel32:KERNEL32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000002b0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400d22b0     oleaut32:OLEAUT32.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000300       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400d2300     vcruntime:VCRUNTIME140.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000320       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400d2320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000338       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400d2338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000348       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400d2348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000358       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400d2358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000003f0       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400d23f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000408       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400d2408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000418       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400d2418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000448       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400d2448     ntdll:ntdll.dll",
      "source": "link_map"
    },
    {
      "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000460       ",
      "kind": "dynamic_library",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400d2460     ole32:ole32.dll",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-link-link-13692-1783954392811796600.map",
  "pid": 13692,
  "ppid": 7404,
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
  "success": true,
  "tool": "link",
  "trace_args": [
    "/nologo",
    "/verbose:lib",
    "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-link-link-13692-1783954392811796600.map"
  ],
  "trace_mode": "msvc_link",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 11960,
  "ppid": 8752,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:d0d4f0de453cfa00:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c",
  "pid": 11960,
  "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
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
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
  "pid": 11960,
  "ppid": 8752,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 17920,
  "ppid": 8752,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
  "pid": 17920,
  "ppid": 8752,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "-c",
    "liblz4/lib/lz4.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 15912,
  "ppid": 8752,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "-c",
    "liblz4/lib/lz4.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:3aaa426877509209:d2e300ddaf49b778",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
  "path": "liblz4/lib/lz4.c",
  "pid": 15912,
  "sha256": "9396f7de527bc8435de9c7569fb7998e56545a84b4f3c2d808c0235c01774539",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "-c",
    "liblz4/lib/lz4.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:780a898ef1ef9908:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
  "pid": 15912,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "-c",
    "liblz4/lib/lz4.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:3aaa426877509209:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "liblz4/lib/lz4.c",
  "pid": 15912,
  "sha256": "9396f7de527bc8435de9c7569fb7998e56545a84b4f3c2d808c0235c01774539",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "-c",
    "liblz4/lib/lz4.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
  "src": "liblz4/lib/lz4.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "-c",
    "liblz4/lib/lz4.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "liblz4/lib/lz4.c"
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
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "-c",
    "liblz4/lib/lz4.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
  "pid": 15912,
  "ppid": 8752,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "-c",
    "liblz4/lib/lz4frame.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 16600,
  "ppid": 8752,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "-c",
    "liblz4/lib/lz4frame.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:23a2d375a699ad5a:e43eec6d0bb0dd4a",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
  "path": "liblz4/lib/lz4frame.c",
  "pid": 16600,
  "sha256": "44f421bea199c7f11da263c717f063228cd2c8c05a8384d327b49cc81ccfbac4",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "-c",
    "liblz4/lib/lz4frame.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:b691430fafc47db7:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
  "pid": 16600,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "-c",
    "liblz4/lib/lz4frame.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:23a2d375a699ad5a:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "liblz4/lib/lz4frame.c",
  "pid": 16600,
  "sha256": "44f421bea199c7f11da263c717f063228cd2c8c05a8384d327b49cc81ccfbac4",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "-c",
    "liblz4/lib/lz4frame.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
  "src": "liblz4/lib/lz4frame.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "-c",
    "liblz4/lib/lz4frame.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "liblz4/lib/lz4frame.c"
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
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "-c",
    "liblz4/lib/lz4frame.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
  "pid": 16600,
  "ppid": 8752,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "-c",
    "liblz4/lib/lz4hc.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 2356,
  "ppid": 8752,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "-c",
    "liblz4/lib/lz4hc.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:c727ad0ebe1dc63e:5bb5a297d3ba6abc",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
  "path": "liblz4/lib/lz4hc.c",
  "pid": 2356,
  "sha256": "126cafafdb91767e6e55238298a910903851b35b2cee27ce80ae2280469ee232",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "-c",
    "liblz4/lib/lz4hc.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:825ec318d823159d:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
  "pid": 2356,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "-c",
    "liblz4/lib/lz4hc.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:c727ad0ebe1dc63e:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "liblz4/lib/lz4hc.c",
  "pid": 2356,
  "sha256": "126cafafdb91767e6e55238298a910903851b35b2cee27ce80ae2280469ee232",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "-c",
    "liblz4/lib/lz4hc.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
  "src": "liblz4/lib/lz4hc.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "-c",
    "liblz4/lib/lz4hc.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "liblz4/lib/lz4hc.c"
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
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "-c",
    "liblz4/lib/lz4hc.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
  "pid": 2356,
  "ppid": 8752,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "-c",
    "liblz4/lib/xxhash.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 4728,
  "ppid": 8752,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "-c",
    "liblz4/lib/xxhash.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "compiler",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:4b9d5f174024384a:8049aefc461a0fcf",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
  "path": "liblz4/lib/xxhash.c",
  "pid": 4728,
  "sha256": "b667033dc735fb5ea5648e0a61a2e065e5ef5bbda53669730063bd856c643c48",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "-c",
    "liblz4/lib/xxhash.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:a4106f9f01fa7456:e3b0c44298fc1c14",
  "exit_code": 0,
  "hash_skipped": "non_file_input",
  "input_kind": "object",
  "kind": "used_input",
  "output": null,
  "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
  "pid": 4728,
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "-c",
    "liblz4/lib/xxhash.c"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:cl:cc522c76e6faaa5e:4b9d5f174024384a:e3b0c44298fc1c14",
  "exit_code": 0,
  "input_kind": "source",
  "kind": "used_input",
  "output": null,
  "path": "liblz4/lib/xxhash.c",
  "pid": 4728,
  "sha256": "b667033dc735fb5ea5648e0a61a2e065e5ef5bbda53669730063bd856c643c48",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "-c",
    "liblz4/lib/xxhash.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "compile",
  "language": "c",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
  "src": "liblz4/lib/xxhash.c",
  "success": true,
  "tool": "cl",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "-c",
    "liblz4/lib/xxhash.c"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "liblz4/lib/xxhash.c"
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
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
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
    "-O2",
    "-Z7",
    "-Brepro",
    "-W4",
    "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
    "-c",
    "liblz4/lib/xxhash.c"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
  "pid": 4728,
  "ppid": 8752,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "cl",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 57

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 4268,
  "ppid": 8752,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 58

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:lib:cc522c76e6faaa5e:d2e300ddaf49b778:ba596f1fe4e0d61c",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
  "pid": 4268,
  "sha256": "130b43ef75dc00b4c2889b486608bf63bccc383e4ecbc10d611667d28a3c13ca",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 59

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:lib:cc522c76e6faaa5e:e43eec6d0bb0dd4a:ba596f1fe4e0d61c",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
  "pid": 4268,
  "sha256": "fc0a56e9870a385f5f12c7ab26c5e6a4d199299ccdad451c180c4f42dc5c1543",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 60

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:lib:cc522c76e6faaa5e:5bb5a297d3ba6abc:ba596f1fe4e0d61c",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
  "pid": 4268,
  "sha256": "a0075948bbdcd31d9b10a145394766a7e5060f310075b71cfabe69586212302f",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 61

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "archiver",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:lib:cc522c76e6faaa5e:8049aefc461a0fcf:ba596f1fe4e0d61c",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
  "pid": 4268,
  "sha256": "a51894975552194e2f4bea49ce6561f091ca63386426a9568c03aa23a2a6aced",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 62

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:lib:cc522c76e6faaa5e:d2e300ddaf49b778:625f2e929625b680",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
  "pid": 4268,
  "sha256": "130b43ef75dc00b4c2889b486608bf63bccc383e4ecbc10d611667d28a3c13ca",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 63

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:lib:cc522c76e6faaa5e:e43eec6d0bb0dd4a:625f2e929625b680",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
  "pid": 4268,
  "sha256": "fc0a56e9870a385f5f12c7ab26c5e6a4d199299ccdad451c180c4f42dc5c1543",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 64

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:lib:cc522c76e6faaa5e:5bb5a297d3ba6abc:625f2e929625b680",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
  "pid": 4268,
  "sha256": "a0075948bbdcd31d9b10a145394766a7e5060f310075b71cfabe69586212302f",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 65

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "consumer_kind": "linker",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "used:lib:cc522c76e6faaa5e:8049aefc461a0fcf:625f2e929625b680",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
  "pid": 4268,
  "sha256": "a51894975552194e2f4bea49ce6561f091ca63386426a9568c03aa23a2a6aced",
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 66

```json
{
  "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "kind": "archive",
  "objects": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 67

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "inputs": [
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "kind": "link",
  "lib_paths": [],
  "libs": [],
  "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "lib",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 68

```json
{
  "argv": [
    "lib",
    "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
    "-nologo",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
  ],
  "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "cargo_pkg_name": "lz4-sys",
  "cargo_pkg_version": "1.11.1+lz4-1.10.0",
  "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "exit_code": 0,
  "host": "x86_64-pc-windows-msvc",
  "kind": "exec_context",
  "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
  "num_jobs": "24",
  "opt_level": "0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
  "pid": 4268,
  "ppid": 8752,
  "profile": "debug",
  "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
  "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "tool": "lib",
  "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 69

```json
{
  "crate": "lz4-sys",
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "event_id": "bsrun:abf08351be1b8caf:704e0e7b6b001d42:4095c81cda1bdc11",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\build-script-build.exe",
  "host": "x86_64-pc-windows-msvc",
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
  "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
  "success": true,
  "target": "x86_64-pc-windows-msvc",
  "version": "1.11.1+lz4-1.10.0",
  "_owner": {
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
    "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 70

```json
{
  "crate": "libc",
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "event_id": "bsrun:a733304fa0307800:d4049e57ca0b142f:411186e64cbbf7b9",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/target/debug/build/libc-763fb040b2d663ab\\build-script-build.exe",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/target/debug/build/libc-763fb040b2d663ab/out",
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

#### Record 71

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
  "raw_event_count": 11816,
  "parsed_event_count": 11816,
  "parse_error_count": 0,
  "command_line_event_count": 11816,
  "build_script_root_event_count": 240,
  "file_io_event_count": 0,
  "file_io_attributed_event_count": 0,
  "internal_acquisition_event_count": 0,
  "attributed_event_count": 1116,
  "dropped_event_count": 6255
}
```

#### Record 72

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 4260,
  "ppid": 14208,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:53:12.242007+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 4260,
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
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/target/debug/build/libc-763fb040b2d663ab/out"
}
```

#### Record 73

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17492,
  "ppid": 4260,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
  ],
  "comm": "rustc-trace-wrapper.exe",
  "time": "2026-07-13T14:53:12.251376+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 4260,
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
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/target/debug/build/libc-763fb040b2d663ab/out",
  "_direct_build_script_child": true,
  "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 74

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13180,
  "ppid": 17492,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
  ],
  "comm": "rustc.exe",
  "time": "2026-07-13T14:53:12.259313+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 4260,
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
  "_build_script_out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/target/debug/build/libc-763fb040b2d663ab/out"
}
```

#### Record 75

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 8752,
  "ppid": 14208,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\build-script-build.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\build-script-build.exe"
  ],
  "comm": "build-script-build.exe",
  "time": "2026-07-13T14:53:13.199544+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\build-script-build.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 76

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 11960,
  "ppid": 8752,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:13.258153+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 77

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 1528,
  "ppid": 11960,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:13.270175+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 78

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 17920,
  "ppid": 8752,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:13.299808+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 79

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 12656,
  "ppid": 17920,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:13.304778+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 80

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 15912,
  "ppid": 8752,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:13.338888+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 81

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 3632,
  "ppid": 15912,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:13.344228+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 82

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 16600,
  "ppid": 8752,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:14.673123+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 83

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 5104,
  "ppid": 16600,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:14.678297+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 84

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 2356,
  "ppid": 8752,
  "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:14.919985+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 85

```json
{
  "event": "process_exec",
  "source": "windows_etw:kernel_process_provider_realtime",
  "pid": 13072,
  "ppid": 2356,
  "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "argv": [
    "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
  ],
  "comm": "cl.exe",
  "time": "2026-07-13T14:53:14.925604+00:00",
  "argv_source": "kernel_command_line",
  "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
  "root_cargo_pid": 16840,
  "build_script_root_pid": 8752,
  "build_script_related": true,
  "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
}
```

#### Record 86

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 17764,
  "ppid": 8548,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
  "time": "2026-07-13T14:53:11.549320+00:00",
  "end_time": "2026-07-13T14:53:11.567560+00:00",
  "start_unix_nanos": 1783954391549319400,
  "end_unix_nanos": 1783954391567560000,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 87

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 3600,
  "ppid": 8548,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
  "time": "2026-07-13T14:53:11.573934+00:00",
  "end_time": "2026-07-13T14:53:11.594961+00:00",
  "start_unix_nanos": 1783954391573934000,
  "end_unix_nanos": 1783954391594960700,
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

#### Record 88

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 8800,
  "ppid": 8548,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
  "time": "2026-07-13T14:53:11.721301+00:00",
  "end_time": "2026-07-13T14:53:11.740098+00:00",
  "start_unix_nanos": 1783954391721301000,
  "end_unix_nanos": 1783954391740097600,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 89

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 16908,
  "ppid": 14208,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
  "time": "2026-07-13T14:53:11.780425+00:00",
  "end_time": "2026-07-13T14:53:11.798664+00:00",
  "start_unix_nanos": 1783954391780424500,
  "end_unix_nanos": 1783954391798663600,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 90

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 14356,
  "ppid": 14208,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
  "time": "2026-07-13T14:53:11.804725+00:00",
  "end_time": "2026-07-13T14:53:11.825684+00:00",
  "start_unix_nanos": 1783954391804725200,
  "end_unix_nanos": 1783954391825684100,
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

#### Record 91

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 17548,
  "ppid": 14208,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
  "time": "2026-07-13T14:53:11.835589+00:00",
  "end_time": "2026-07-13T14:53:11.853918+00:00",
  "start_unix_nanos": 1783954391835589300,
  "end_unix_nanos": 1783954391853918400,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 92

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 6116,
  "ppid": 14208,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:11.873538+00:00",
  "end_time": "2026-07-13T14:53:12.237048+00:00",
  "start_unix_nanos": 1783954391873538200,
  "end_unix_nanos": 1783954392237048300,
  "crate_name": "find_msvc_tools",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps"
}
```

#### Record 93

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 2964,
  "ppid": 14208,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=0add1c4e1ef78d62 -C extra-filename=-763fb040b2d663ab --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:11.875881+00:00",
  "end_time": "2026-07-13T14:53:12.146066+00:00",
  "start_unix_nanos": 1783954391875881300,
  "end_unix_nanos": 1783954392146066500,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab"
}
```

#### Record 94

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 4548,
  "ppid": 14208,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:11.877824+00:00",
  "end_time": "2026-07-13T14:53:11.979067+00:00",
  "start_unix_nanos": 1783954391877824200,
  "end_unix_nanos": 1783954391979067300,
  "crate_name": "shlex",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps"
}
```

#### Record 95

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 15532,
  "ppid": 14208,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--extern",
    "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
    "--extern",
    "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
    "--cap-lints",
    "allow"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:12.071054+00:00",
  "end_time": "2026-07-13T14:53:12.662540+00:00",
  "start_unix_nanos": 1783954392071054100,
  "end_unix_nanos": 1783954392662539700,
  "crate_name": "cc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps"
}
```

#### Record 96

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 17492,
  "ppid": 4260,
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
  "time": "2026-07-13T14:53:12.255601+00:00",
  "end_time": "2026-07-13T14:53:12.271222+00:00",
  "start_unix_nanos": 1783954392255601000,
  "end_unix_nanos": 1783954392271221900,
  "crate_name": null,
  "crate_type": [],
  "out_dir": null
}
```

#### Record 97

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 3128,
  "ppid": 14208,
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
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
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=de34c0666a4c6d46 -C extra-filename=-751e763eb72b7eae --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --cap-lints allow --cfg freebsd12 --check-cfg cfg(emscripten_old_stat_abi) --check-cfg cfg(espidf_picolibc) --check-cfg cfg(espidf_time32) --check-cfg cfg(freebsd10) --check-cfg cfg(freebsd11) --check-cfg cfg(freebsd12) --check-cfg cfg(freebsd13) --check-cfg cfg(freebsd14) --check-cfg cfg(freebsd15) --check-cfg cfg(gnu_file_offset_bits64) --check-cfg cfg(gnu_time_bits64) --check-cfg cfg(libc_deny_warnings) --check-cfg cfg(linux_time_bits64) --check-cfg cfg(musl_v1_2_3) --check-cfg cfg(musl32_time64) --check-cfg cfg(musl_redir_time64) --check-cfg cfg(vxworks_lt_25_09) --check-cfg \"cfg(target_os,values(\\\"switch\\\",\\\"aix\\\",\\\"ohos\\\",\\\"hurd\\\",\\\"rtems\\\",\\\"visionos\\\",\\\"nuttx\\\",\\\"cygwin\\\",\\\"qurt\\\"))\" --check-cfg \"cfg(target_env,values(\\\"illumos\\\",\\\"wasi\\\",\\\"aix\\\",\\\"ohos\\\",\\\"nto71_iosock\\\",\\\"nto80\\\"))\" --check-cfg \"cfg(target_arch,values(\\\"loongarch64\\\",\\\"mips32r6\\\",\\\"mips64r6\\\",\\\"csky\\\"))\"",
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
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
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
  "time": "2026-07-13T14:53:12.281834+00:00",
  "end_time": "2026-07-13T14:53:12.371367+00:00",
  "start_unix_nanos": 1783954392281833900,
  "end_unix_nanos": 1783954392371367000,
  "crate_name": "libc",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps"
}
```

#### Record 98

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 8204,
  "ppid": 14208,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
    "cfg(feature, values())",
    "-C",
    "metadata=e43f0d342d4089c4",
    "-C",
    "extra-filename=-57858e87cc2d10d3",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=e43f0d342d4089c4 -C extra-filename=-57858e87cc2d10d3 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
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
    "cfg(feature, values())",
    "-C",
    "metadata=e43f0d342d4089c4",
    "-C",
    "extra-filename=-57858e87cc2d10d3",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--extern",
    "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:12.677716+00:00",
  "end_time": "2026-07-13T14:53:13.052451+00:00",
  "start_unix_nanos": 1783954392677716200,
  "end_unix_nanos": 1783954393052450600,
  "crate_name": "build_script_build",
  "crate_type": [
    "bin"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3"
}
```

#### Record 99

```json
{
  "event": "process_exec",
  "source": "rustc_trace_wrapper",
  "argv_source": "rustc_wrapper",
  "kind": "rustc_exec",
  "tool": "rustc",
  "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
  "root_process_pid": 16840,
  "pid": 17556,
  "ppid": 14208,
  "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
  "argv": [
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "lz4_sys",
    "--edition=2015",
    "src\\lib.rs",
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
    "cfg(feature, values())",
    "-C",
    "metadata=6901d98b442b82ad",
    "-C",
    "extra-filename=-2fc42070bea06191",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--extern",
    "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
    "-l",
    "static=lz4"
  ],
  "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name lz4_sys --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=6901d98b442b82ad -C extra-filename=-2fc42070bea06191 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --extern libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out -l static=lz4",
  "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
  "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
  "wrapper_argv": [
    "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
    "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
    "--crate-name",
    "lz4_sys",
    "--edition=2015",
    "src\\lib.rs",
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
    "cfg(feature, values())",
    "-C",
    "metadata=6901d98b442b82ad",
    "-C",
    "extra-filename=-2fc42070bea06191",
    "--out-dir",
    "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "-C",
    "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental",
    "-L",
    "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
    "--extern",
    "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
    "-L",
    "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
    "-l",
    "static=lz4"
  ],
  "exit_code": 0,
  "success": true,
  "time": "2026-07-13T14:53:16.858886+00:00",
  "end_time": "2026-07-13T14:53:16.952641+00:00",
  "start_unix_nanos": 1783954396858885600,
  "end_unix_nanos": 1783954396952641100,
  "crate_name": "lz4_sys",
  "crate_type": [
    "lib"
  ],
  "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps"
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "kind": "success",
  "time": "2026-07-13T14:53:17.890882+00:00",
  "crate": "lz4-sys",
  "version": "1.11.1+lz4-1.10.0",
  "duration_seconds": 28.85817329993006,
  "trace_record_count": 85,
  "trace_owner_summary": {
    "owner_package_count": 5,
    "owner_packages": [
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "C:/Users/rustbuild/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "manifest_path": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/Cargo.toml"
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
    "attributed_event_count": 69,
    "unattributed_event_count": 16,
    "owners": [
      {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "event_count": 51,
        "kind_counts": {
          "exec": 8,
          "link": 7,
          "exec_context": 8,
          "resolved_link": 1,
          "used_input": 21,
          "compile": 4,
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
      "cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "cargo_args": [
        "build"
      ],
      "workspace_default_members": [
        "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0"
      ],
      "packages": [
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
          "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
          "name": "lz4-sys",
          "version": "1.11.1+lz4-1.10.0",
          "manifest_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Cargo.toml",
          "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0"
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "pid": 9644,
      "ppid": 5572,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:a8055f2f9e1d22f7:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:b3b69b375c45dace:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:b9c140a537c1b83a:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:74c40562cb45ab56:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:525892dd6b5c2a1f:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:0b9d3a9765f4bfdb:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "kernel32.lib",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "kernel32.lib",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:1ceda9c220daf075:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "kernel32.lib",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:1db9512c4d5c31e6:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "ntdll.lib",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:861f0814f9c52599:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "userenv.lib",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:50848825683fdca9:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "ws2_32.lib",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "event_id": "used:link:e28a626e7bd4a22f:df7d4e53c08047f7:ab0d29e1acb7c4cd",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "static_library",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
      "path": "dbghelp.lib",
      "pid": 9644,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o"
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
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 9644,
      "ppid": 5572,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "/NOLOGO",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\rustc286LSb\\symbols.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.0.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.1.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.2.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.build_script_build.e2dac872b2faa222-cgu.3.rcgu.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.8kj88xivrhpj6t072ppfrppb9.rcgu.o",
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
        "/OUT:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build_script_build-763fb040b2d663ab.exe",
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
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-link-link-9644-1783954392037965600.map",
      "pid": 9644,
      "ppid": 5572,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-link-link-9644-1783954392037965600.map"
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 13692,
      "ppid": 7404,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "inputs": [],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "link",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 13692,
      "ppid": 7404,
      "profile": null,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "success": true,
      "target": null,
      "tool": "link",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\link.exe",
        "@C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\rustcav1MMu\\linker-arguments"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "directories": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
        "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\lib\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000020       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000298       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000002b0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000300       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000320       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000338       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000348       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000358       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000003f0       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000408       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000418       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000448       ",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000460       "
      ],
      "exit_code": 0,
      "inputs": [
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\kernel32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\advapi32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ole32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\oleaut32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ntdll.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\userenv.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\ws2_32.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\\\lib\\10.0.22621.0\\\\um\\x64\\dbghelp.lib",
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
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64",
          "kind": "library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\Kits\\10\\lib\\10.0.22621.0\\ucrt\\x64\\ucrt.lib",
          "source": "link_trace"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000020       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000020       \\177ADVAPI32_NULL_THUNK_DATA 00000001400d2020     advapi32:ADVAPI32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000298       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000298       \\177KERNEL32_NULL_THUNK_DATA 00000001400d2298     kernel32:KERNEL32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000002b0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000002b0       \\177OLEAUT32_NULL_THUNK_DATA 00000001400d22b0     oleaut32:OLEAUT32.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000300       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000300       \\177VCRUNTIME140_NULL_THUNK_DATA 00000001400d2300     vcruntime:VCRUNTIME140.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000320       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000320       \\177api-ms-win-core-synch-l1-2-0_NULL_THUNK_DATA 00000001400d2320     libstd-f6a1efc0b26a278e:api-ms-win-core-synch-l1-2-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000338       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000338       \\177api-ms-win-crt-heap-l1-1-0_NULL_THUNK_DATA 00000001400d2338     ucrt:api-ms-win-crt-heap-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000348       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000348       \\177api-ms-win-crt-locale-l1-1-0_NULL_THUNK_DATA 00000001400d2348     ucrt:api-ms-win-crt-locale-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000358       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000358       \\177api-ms-win-crt-math-l1-1-0_NULL_THUNK_DATA 00000001400d2358     ucrt:api-ms-win-crt-math-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000003f0       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:000003f0       \\177api-ms-win-crt-runtime-l1-1-0_NULL_THUNK_DATA 00000001400d23f0     ucrt:api-ms-win-crt-runtime-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000408       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000408       \\177api-ms-win-crt-stdio-l1-1-0_NULL_THUNK_DATA 00000001400d2408     ucrt:api-ms-win-crt-stdio-l1-1-0.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000418       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000418       \\177bcryptprimitives_NULL_THUNK_DATA 00000001400d2418     libstd-f6a1efc0b26a278e:bcryptprimitives.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000448       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000448       \\177ntdll_NULL_THUNK_DATA  00000001400d2448     ntdll:ntdll.dll",
          "source": "link_map"
        },
        {
          "directory": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000460       ",
          "kind": "dynamic_library",
          "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\0002:00000460       \\177ole32_NULL_THUNK_DATA  00000001400d2460     ole32:ole32.dll",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-link-link-13692-1783954392811796600.map",
      "pid": 13692,
      "ppid": 7404,
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\link.exe",
      "success": true,
      "tool": "link",
      "trace_args": [
        "/nologo",
        "/verbose:lib",
        "/map:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-link-link-13692-1783954392811796600.map"
      ],
      "trace_mode": "msvc_link",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 11960,
      "ppid": 8752,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:d0d4f0de453cfa00:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c",
      "pid": 11960,
      "sha256": "97ca4b021495611e828becea6187add37414186a16dfedd26c2947cbce6e8b2f",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
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
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-E",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\13066533444925609402detect_compiler_family.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
      "pid": 11960,
      "ppid": 8752,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 17920,
      "ppid": 8752,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-?"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
      "pid": 17920,
      "ppid": 8752,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "-c",
        "liblz4/lib/lz4.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 15912,
      "ppid": 8752,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "-c",
        "liblz4/lib/lz4.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:3aaa426877509209:d2e300ddaf49b778",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
      "path": "liblz4/lib/lz4.c",
      "pid": 15912,
      "sha256": "9396f7de527bc8435de9c7569fb7998e56545a84b4f3c2d808c0235c01774539",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "-c",
        "liblz4/lib/lz4.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:780a898ef1ef9908:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
      "pid": 15912,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "-c",
        "liblz4/lib/lz4.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:3aaa426877509209:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "liblz4/lib/lz4.c",
      "pid": 15912,
      "sha256": "9396f7de527bc8435de9c7569fb7998e56545a84b4f3c2d808c0235c01774539",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "-c",
        "liblz4/lib/lz4.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
      "src": "liblz4/lib/lz4.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "-c",
        "liblz4/lib/lz4.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "liblz4/lib/lz4.c"
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
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "-c",
        "liblz4/lib/lz4.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
      "pid": 15912,
      "ppid": 8752,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "-c",
        "liblz4/lib/lz4frame.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 16600,
      "ppid": 8752,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "-c",
        "liblz4/lib/lz4frame.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:23a2d375a699ad5a:e43eec6d0bb0dd4a",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
      "path": "liblz4/lib/lz4frame.c",
      "pid": 16600,
      "sha256": "44f421bea199c7f11da263c717f063228cd2c8c05a8384d327b49cc81ccfbac4",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "-c",
        "liblz4/lib/lz4frame.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:b691430fafc47db7:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
      "pid": 16600,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "-c",
        "liblz4/lib/lz4frame.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:23a2d375a699ad5a:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "liblz4/lib/lz4frame.c",
      "pid": 16600,
      "sha256": "44f421bea199c7f11da263c717f063228cd2c8c05a8384d327b49cc81ccfbac4",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "-c",
        "liblz4/lib/lz4frame.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
      "src": "liblz4/lib/lz4frame.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "-c",
        "liblz4/lib/lz4frame.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "liblz4/lib/lz4frame.c"
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
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "-c",
        "liblz4/lib/lz4frame.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
      "pid": 16600,
      "ppid": 8752,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "-c",
        "liblz4/lib/lz4hc.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 2356,
      "ppid": 8752,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "-c",
        "liblz4/lib/lz4hc.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:c727ad0ebe1dc63e:5bb5a297d3ba6abc",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
      "path": "liblz4/lib/lz4hc.c",
      "pid": 2356,
      "sha256": "126cafafdb91767e6e55238298a910903851b35b2cee27ce80ae2280469ee232",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "-c",
        "liblz4/lib/lz4hc.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:825ec318d823159d:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
      "pid": 2356,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "-c",
        "liblz4/lib/lz4hc.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:c727ad0ebe1dc63e:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "liblz4/lib/lz4hc.c",
      "pid": 2356,
      "sha256": "126cafafdb91767e6e55238298a910903851b35b2cee27ce80ae2280469ee232",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "-c",
        "liblz4/lib/lz4hc.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
      "src": "liblz4/lib/lz4hc.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "-c",
        "liblz4/lib/lz4hc.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "liblz4/lib/lz4hc.c"
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
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "-c",
        "liblz4/lib/lz4hc.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
      "pid": 2356,
      "ppid": 8752,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
        "-c",
        "liblz4/lib/xxhash.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 4728,
      "ppid": 8752,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
        "-c",
        "liblz4/lib/xxhash.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "compiler",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:4b9d5f174024384a:8049aefc461a0fcf",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
      "path": "liblz4/lib/xxhash.c",
      "pid": 4728,
      "sha256": "b667033dc735fb5ea5648e0a61a2e065e5ef5bbda53669730063bd856c643c48",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
        "-c",
        "liblz4/lib/xxhash.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:a4106f9f01fa7456:e3b0c44298fc1c14",
      "exit_code": 0,
      "hash_skipped": "non_file_input",
      "input_kind": "object",
      "kind": "used_input",
      "output": null,
      "path": "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
      "pid": 4728,
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
        "-c",
        "liblz4/lib/xxhash.c"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:cl:cc522c76e6faaa5e:4b9d5f174024384a:e3b0c44298fc1c14",
      "exit_code": 0,
      "input_kind": "source",
      "kind": "used_input",
      "output": null,
      "path": "liblz4/lib/xxhash.c",
      "pid": 4728,
      "sha256": "b667033dc735fb5ea5648e0a61a2e065e5ef5bbda53669730063bd856c643c48",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
        "-c",
        "liblz4/lib/xxhash.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "compile",
      "language": "c",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
      "src": "liblz4/lib/xxhash.c",
      "success": true,
      "tool": "cl",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
        "-c",
        "liblz4/lib/xxhash.c"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "inputs": [
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
        "liblz4/lib/xxhash.c"
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
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cl",
        "-nologo",
        "-MD",
        "-O2",
        "-Z7",
        "-Brepro",
        "-W4",
        "-FoC:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
        "-c",
        "liblz4/lib/xxhash.c"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
      "pid": 4728,
      "ppid": 8752,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\cl.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "cl",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 4268,
      "ppid": 8752,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:lib:cc522c76e6faaa5e:d2e300ddaf49b778:ba596f1fe4e0d61c",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
      "pid": 4268,
      "sha256": "130b43ef75dc00b4c2889b486608bf63bccc383e4ecbc10d611667d28a3c13ca",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:lib:cc522c76e6faaa5e:e43eec6d0bb0dd4a:ba596f1fe4e0d61c",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
      "pid": 4268,
      "sha256": "fc0a56e9870a385f5f12c7ab26c5e6a4d199299ccdad451c180c4f42dc5c1543",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:lib:cc522c76e6faaa5e:5bb5a297d3ba6abc:ba596f1fe4e0d61c",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
      "pid": 4268,
      "sha256": "a0075948bbdcd31d9b10a145394766a7e5060f310075b71cfabe69586212302f",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "archiver",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:lib:cc522c76e6faaa5e:8049aefc461a0fcf:ba596f1fe4e0d61c",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
      "pid": 4268,
      "sha256": "a51894975552194e2f4bea49ce6561f091ca63386426a9568c03aa23a2a6aced",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:lib:cc522c76e6faaa5e:d2e300ddaf49b778:625f2e929625b680",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
      "pid": 4268,
      "sha256": "130b43ef75dc00b4c2889b486608bf63bccc383e4ecbc10d611667d28a3c13ca",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:lib:cc522c76e6faaa5e:e43eec6d0bb0dd4a:625f2e929625b680",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
      "pid": 4268,
      "sha256": "fc0a56e9870a385f5f12c7ab26c5e6a4d199299ccdad451c180c4f42dc5c1543",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:lib:cc522c76e6faaa5e:5bb5a297d3ba6abc:625f2e929625b680",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
      "pid": 4268,
      "sha256": "a0075948bbdcd31d9b10a145394766a7e5060f310075b71cfabe69586212302f",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "consumer_kind": "linker",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "used:lib:cc522c76e6faaa5e:8049aefc461a0fcf:625f2e929625b680",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
      "path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o",
      "pid": 4268,
      "sha256": "a51894975552194e2f4bea49ce6561f091ca63386426a9568c03aa23a2a6aced",
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "archive": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "kind": "archive",
      "objects": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "inputs": [
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "kind": "link",
      "lib_paths": [],
      "libs": [],
      "output": "ut:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "lib",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "lib",
        "-out:C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\liblz4.a",
        "-nologo",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4frame.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-lz4hc.o",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out\\efce31824dbf3730-xxhash.o"
      ],
      "cargo_manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "cargo_pkg_name": "lz4-sys",
      "cargo_pkg_version": "1.11.1+lz4-1.10.0",
      "context_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-root-context.jsonl",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "exit_code": 0,
      "host": "x86_64-pc-windows-msvc",
      "kind": "exec_context",
      "metadata_path": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\events\\00000000-cargo-metadata.json",
      "num_jobs": "24",
      "opt_level": "0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
      "pid": 4268,
      "ppid": 8752,
      "profile": "debug",
      "real_tool": "C:\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\HostX64\\x64\\lib.exe",
      "root_cwd": "\\\\?\\C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "tool": "lib",
      "workspace_root": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "crate": "lz4-sys",
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "event_id": "bsrun:abf08351be1b8caf:704e0e7b6b001d42:4095c81cda1bdc11",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\build-script-build.exe",
      "host": "x86_64-pc-windows-msvc",
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
      "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
      "success": true,
      "target": "x86_64-pc-windows-msvc",
      "version": "1.11.1+lz4-1.10.0",
      "_owner": {
        "crate": "lz4-sys",
        "version": "1.11.1+lz4-1.10.0",
        "package_id": "path+file:///C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0#lz4-sys@1.11.1+lz4-1.10.0",
        "manifest_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "event_id": "bsrun:a733304fa0307800:d4049e57ca0b142f:411186e64cbbf7b9",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/target/debug/build/libc-763fb040b2d663ab\\build-script-build.exe",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186",
      "out_dir": "C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-36qa9ekf/src/lz4-sys-1.11.1+lz4-1.10.0/target/debug/build/libc-763fb040b2d663ab/out",
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
      "raw_event_count": 11816,
      "parsed_event_count": 11816,
      "parse_error_count": 0,
      "command_line_event_count": 11816,
      "build_script_root_event_count": 240,
      "file_io_event_count": 0,
      "file_io_attributed_event_count": 0,
      "internal_acquisition_event_count": 0,
      "attributed_event_count": 1116,
      "dropped_event_count": 6255
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 4260,
      "ppid": 14208,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:53:12.242007+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab\\build-script-build.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 4260,
      "build_script_related": true,
      "build_script_target_dir": "libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17492,
      "ppid": 4260,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe"
      ],
      "comm": "rustc-trace-wrapper.exe",
      "time": "2026-07-13T14:53:12.251376+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 4260,
      "build_script_related": true,
      "build_script_target_dir": "libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13180,
      "ppid": 17492,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe"
      ],
      "comm": "rustc.exe",
      "time": "2026-07-13T14:53:12.259313+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 4260,
      "build_script_related": true,
      "build_script_target_dir": "libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 8752,
      "ppid": 14208,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\build-script-build.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\build-script-build.exe"
      ],
      "comm": "build-script-build.exe",
      "time": "2026-07-13T14:53:13.199544+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3\\build-script-build.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 11960,
      "ppid": 8752,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:13.258153+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 1528,
      "ppid": 11960,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:13.270175+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 17920,
      "ppid": 8752,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:13.299808+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 12656,
      "ppid": 17920,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:13.304778+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 15912,
      "ppid": 8752,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:13.338888+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 3632,
      "ppid": 15912,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:13.344228+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 16600,
      "ppid": 8752,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:14.673123+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 5104,
      "ppid": 16600,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:14.678297+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 2356,
      "ppid": 8752,
      "image": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:14.919985+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\.tmp\\native-trace-18192-1783954391371\\shims\\cl.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "windows_etw:kernel_process_provider_realtime",
      "pid": 13072,
      "ppid": 2356,
      "image": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "argv": [
        "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe"
      ],
      "comm": "cl.exe",
      "time": "2026-07-13T14:53:14.925604+00:00",
      "argv_source": "kernel_command_line",
      "command_line": "\\Device\\HarddiskVolume3\\BuildTools2022\\VC\\Tools\\MSVC\\14.44.35207\\bin\\Hostx64\\x64\\cl.exe",
      "root_cargo_pid": 16840,
      "build_script_root_pid": 8752,
      "build_script_related": true,
      "build_script_target_dir": "lz4-sys-57858e87cc2d10d3"
    }
  ],
  "rustc_trace_records": [
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 17764,
      "ppid": 8548,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
      "time": "2026-07-13T14:53:11.549320+00:00",
      "end_time": "2026-07-13T14:53:11.567560+00:00",
      "start_unix_nanos": 1783954391549319400,
      "end_unix_nanos": 1783954391567560000,
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
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 3600,
      "ppid": 8548,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
      "time": "2026-07-13T14:53:11.573934+00:00",
      "end_time": "2026-07-13T14:53:11.594961+00:00",
      "start_unix_nanos": 1783954391573934000,
      "end_unix_nanos": 1783954391594960700,
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
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 8800,
      "ppid": 8548,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
      "time": "2026-07-13T14:53:11.721301+00:00",
      "end_time": "2026-07-13T14:53:11.740098+00:00",
      "start_unix_nanos": 1783954391721301000,
      "end_unix_nanos": 1783954391740097600,
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
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 16908,
      "ppid": 14208,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
      "time": "2026-07-13T14:53:11.780425+00:00",
      "end_time": "2026-07-13T14:53:11.798664+00:00",
      "start_unix_nanos": 1783954391780424500,
      "end_unix_nanos": 1783954391798663600,
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
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 14356,
      "ppid": 14208,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
      "time": "2026-07-13T14:53:11.804725+00:00",
      "end_time": "2026-07-13T14:53:11.825684+00:00",
      "start_unix_nanos": 1783954391804725200,
      "end_unix_nanos": 1783954391825684100,
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
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 17548,
      "ppid": 14208,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
      "time": "2026-07-13T14:53:11.835589+00:00",
      "end_time": "2026-07-13T14:53:11.853918+00:00",
      "start_unix_nanos": 1783954391835589300,
      "end_unix_nanos": 1783954391853918400,
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
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 6116,
      "ppid": 14208,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name find_msvc_tools --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\find-msvc-tools-0.1.9\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=a199b1cb5e329831 -C extra-filename=-824f9ded730dd358 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:11.873538+00:00",
      "end_time": "2026-07-13T14:53:12.237048+00:00",
      "start_unix_nanos": 1783954391873538200,
      "end_unix_nanos": 1783954392237048300,
      "crate_name": "find_msvc_tools",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 2964,
      "ppid": 14208,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=0add1c4e1ef78d62 -C extra-filename=-763fb040b2d663ab --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:11.875881+00:00",
      "end_time": "2026-07-13T14:53:12.146066+00:00",
      "start_unix_nanos": 1783954391875881300,
      "end_unix_nanos": 1783954392146066500,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\libc-763fb040b2d663ab"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 4548,
      "ppid": 14208,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name shlex --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\shlex-2.0.1\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"default\\\", \\\"std\\\"))\" -C metadata=181708ecadab3b47 -C extra-filename=-f9df91f0b2c0ecd4 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:11.877824+00:00",
      "end_time": "2026-07-13T14:53:11.979067+00:00",
      "start_unix_nanos": 1783954391877824200,
      "end_unix_nanos": 1783954391979067300,
      "crate_name": "shlex",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 15532,
      "ppid": 14208,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name cc --edition=2018 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\cc-1.2.67\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"jobserver\\\", \\\"parallel\\\"))\" -C metadata=98547e1a4afb2a03 -C extra-filename=-24e0405f325d0f68 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --extern find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta --extern shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta --cap-lints allow",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--extern",
        "find_msvc_tools=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libfind_msvc_tools-824f9ded730dd358.rmeta",
        "--extern",
        "shlex=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libshlex-f9df91f0b2c0ecd4.rmeta",
        "--cap-lints",
        "allow"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:12.071054+00:00",
      "end_time": "2026-07-13T14:53:12.662540+00:00",
      "start_unix_nanos": 1783954392071054100,
      "end_unix_nanos": 1783954392662539700,
      "crate_name": "cc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 17492,
      "ppid": 4260,
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
      "time": "2026-07-13T14:53:12.255601+00:00",
      "end_time": "2026-07-13T14:53:12.271222+00:00",
      "start_unix_nanos": 1783954392255601000,
      "end_unix_nanos": 1783954392271221900,
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
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 3128,
      "ppid": 14208,
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
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
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name libc --edition=2021 C:\\Users\\rustbuild\\.cargo\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\libc-0.2.186\\src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr --allow=clippy::non_minimal_cfg --allow=clippy::missing_safety_doc --warn=clippy::map_unwrap_or --warn=clippy::manual_assert --allow=clippy::identity_op --warn=clippy::explicit_iter_loop --allow=clippy::expl_impl_clone_on_copy --cfg \"feature=\\\"default\\\"\" --cfg \"feature=\\\"std\\\"\" --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values(\\\"align\\\", \\\"const-extern-fn\\\", \\\"default\\\", \\\"extra_traits\\\", \\\"rustc-dep-of-std\\\", \\\"rustc-std-workspace-core\\\", \\\"std\\\", \\\"use_std\\\"))\" -C metadata=de34c0666a4c6d46 -C extra-filename=-751e763eb72b7eae --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --cap-lints allow --cfg freebsd12 --check-cfg cfg(emscripten_old_stat_abi) --check-cfg cfg(espidf_picolibc) --check-cfg cfg(espidf_time32) --check-cfg cfg(freebsd10) --check-cfg cfg(freebsd11) --check-cfg cfg(freebsd12) --check-cfg cfg(freebsd13) --check-cfg cfg(freebsd14) --check-cfg cfg(freebsd15) --check-cfg cfg(gnu_file_offset_bits64) --check-cfg cfg(gnu_time_bits64) --check-cfg cfg(libc_deny_warnings) --check-cfg cfg(linux_time_bits64) --check-cfg cfg(musl_v1_2_3) --check-cfg cfg(musl32_time64) --check-cfg cfg(musl_redir_time64) --check-cfg cfg(vxworks_lt_25_09) --check-cfg \"cfg(target_os,values(\\\"switch\\\",\\\"aix\\\",\\\"ohos\\\",\\\"hurd\\\",\\\"rtems\\\",\\\"visionos\\\",\\\"nuttx\\\",\\\"cygwin\\\",\\\"qurt\\\"))\" --check-cfg \"cfg(target_env,values(\\\"illumos\\\",\\\"wasi\\\",\\\"aix\\\",\\\"ohos\\\",\\\"nto71_iosock\\\",\\\"nto80\\\"))\" --check-cfg \"cfg(target_arch,values(\\\"loongarch64\\\",\\\"mips32r6\\\",\\\"mips64r6\\\",\\\"csky\\\"))\"",
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
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
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
      "time": "2026-07-13T14:53:12.281834+00:00",
      "end_time": "2026-07-13T14:53:12.371367+00:00",
      "start_unix_nanos": 1783954392281833900,
      "end_unix_nanos": 1783954392371367000,
      "crate_name": "libc",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 8204,
      "ppid": 14208,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
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
        "cfg(feature, values())",
        "-C",
        "metadata=e43f0d342d4089c4",
        "-C",
        "extra-filename=-57858e87cc2d10d3",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=e43f0d342d4089c4 -C extra-filename=-57858e87cc2d10d3 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3 -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --extern cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib",
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
        "cfg(feature, values())",
        "-C",
        "metadata=e43f0d342d4089c4",
        "-C",
        "extra-filename=-57858e87cc2d10d3",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--extern",
        "cc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\libcc-24e0405f325d0f68.rlib"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:12.677716+00:00",
      "end_time": "2026-07-13T14:53:13.052451+00:00",
      "start_unix_nanos": 1783954392677716200,
      "end_unix_nanos": 1783954393052450600,
      "crate_name": "build_script_build",
      "crate_type": [
        "bin"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-57858e87cc2d10d3"
    },
    {
      "event": "process_exec",
      "source": "rustc_trace_wrapper",
      "argv_source": "rustc_wrapper",
      "kind": "rustc_exec",
      "tool": "rustc",
      "run_id": "lz4-sys:1.11.1+lz4-1.10.0:14896",
      "root_process_pid": 16840,
      "pid": 17556,
      "ppid": 14208,
      "cwd": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0",
      "argv": [
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "lz4_sys",
        "--edition=2015",
        "src\\lib.rs",
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
        "cfg(feature, values())",
        "-C",
        "metadata=6901d98b442b82ad",
        "-C",
        "extra-filename=-2fc42070bea06191",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--extern",
        "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
        "-l",
        "static=lz4"
      ],
      "command_line": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe --crate-name lz4_sys --edition=2015 src\\lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg \"cfg(feature, values())\" -C metadata=6901d98b442b82ad -C extra-filename=-2fc42070bea06191 --out-dir C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps -C incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental -L dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps --extern libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta -L native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out -l static=lz4",
      "real_rustc": "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
      "wrapper_path": "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
      "wrapper_argv": [
        "C:\\Users\\rustbuild\\.cargo\\bin\\rustc-trace-wrapper.exe",
        "C:\\Users\\rustbuild\\.rustup\\toolchains\\stable-x86_64-pc-windows-msvc\\bin\\rustc.exe",
        "--crate-name",
        "lz4_sys",
        "--edition=2015",
        "src\\lib.rs",
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
        "cfg(feature, values())",
        "-C",
        "metadata=6901d98b442b82ad",
        "-C",
        "extra-filename=-2fc42070bea06191",
        "--out-dir",
        "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "-C",
        "incremental=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\incremental",
        "-L",
        "dependency=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps",
        "--extern",
        "libc=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps\\liblibc-751e763eb72b7eae.rmeta",
        "-L",
        "native=C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\build\\lz4-sys-8877f31bf4edc40f\\out",
        "-l",
        "static=lz4"
      ],
      "exit_code": 0,
      "success": true,
      "time": "2026-07-13T14:53:16.858886+00:00",
      "end_time": "2026-07-13T14:53:16.952641+00:00",
      "start_unix_nanos": 1783954396858885600,
      "end_unix_nanos": 1783954396952641100,
      "crate_name": "lz4_sys",
      "crate_type": [
        "lib"
      ],
      "out_dir": "C:\\Users\\rustbuild\\AppData\\Local\\Temp\\crate-build-win-36qa9ekf\\src\\lz4-sys-1.11.1+lz4-1.10.0\\target\\debug\\deps"
    }
  ],
  "item": {
    "rank": 763,
    "crate": "lz4-sys",
    "version": "1.11.1+lz4-1.10.0",
    "crate_id": "7372",
    "version_id": "1281755",
    "downloads": 34147288,
    "cumulative_downloads": 83023971447,
    "cumulative_share_of_global": 0.3104074626737259,
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
