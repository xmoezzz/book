# `utoipa-swagger-ui` `9.0.2`

Platform: Linux x86_64

## Build-level coding evidence

### Network / source acquisition activity

Working directory: `/work`

```text
curl -sSL -o /work/target/debug/build/utoipa-swagger-ui-2a440981763bd7ef/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip
```

Acquisition kind: `download_file`

Outcome: succeeded (exit code 0)

Working directory: `/work`

```text
internal_build_script_archive_output
```

Acquisition kind: `internal_build_script_archive_output`

Outcome: succeeded

Working directory: `/work`

```text
curl -sSL -o /work/target/debug/build/utoipa-swagger-ui-2a440981763bd7ef/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip
```

Outcome: succeeded (exit code 0)

Working directory: `/work`

```text
/usr/bin/curl -sSL -o /work/target/debug/build/utoipa-swagger-ui-2a440981763bd7ef/out/v5.17.14.zip https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip
```

Outcome: outcome unavailable in trace

Working directory: `/work`

```text
/usr/bin/curl -L --fail --silent --show-error -o /work/.tmp/native-trace-redownload-2038465-1784021900315696035.tmp https://github.com/swagger-api/swagger-ui/archive/refs/tags/v5.17.14.zip
```

Outcome: outcome unavailable in trace

### Build-script executable native dependencies

These libraries are consumed while linking the Rust build-script executable. They are shown separately from native artifacts produced by the crate.

#### Linker process 2038364

Build-script executable: `/work/target/debug/build/utoipa-swagger-ui-955475ecfbc08b0c/build_script_build-955475ecfbc08b0c`

Working directory: `/work`

Full linker command: retained in the raw case.

**Linker library inputs**

* `/usr/lib/gcc/x86_64-linux-gnu/12/../../../x86_64-linux-gnu/libgcc_s.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libm.so.6` (dynamic_library)
* `/lib/x86_64-linux-gnu/libmvec.so.1` (dynamic_library)
* `/lib/x86_64-linux-gnu/libc.so.6` (dynamic_library)
* `/lib64/ld-linux-x86-64.so.2` (dynamic_library)
