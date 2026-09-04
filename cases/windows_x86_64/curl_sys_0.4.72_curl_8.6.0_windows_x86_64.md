# `curl-sys` `0.4.72+curl-8.6.0`

Platform: Windows x86_64

## `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/target/debug/build/curl-sys-957e0ed0826653c5/out/build/libcurl.a`

### Source origin

* under acquisition destination `c:/users/rustbuild/appdata/local/temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/curl`

### Source directories

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/curl/lib`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/curl/lib/vauth`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/curl/lib/vquic`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/curl/lib/vtls`

### Source file examples

* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/curl/lib/altsvc.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/curl/lib/asyn-thread.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/curl/lib/base64.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/curl/lib/bufq.c`
* `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0/curl/lib/bufref.c`

### Source acquisition

Working directory: `C:/Users/rustbuild/AppData/Local/Temp/crate-build-win-q1p319p7/src/curl-sys-0.4.72+curl-8.6.0`

```text
git submodule update --init curl
```

### Compilation

```text
cl -nologo -MD -Z7 -Brepro -I <include directory> -I <include directory> -I <include directory> -W0 -DBUILDING_LIBCURL -DCURL_DISABLE_DICT -DCURL_DISABLE_GOPHER -DCURL_DISABLE_IMAP -DCURL_DISABLE_LDAP -DCURL_DISABLE_LDAPS -DCURL_DISABLE_POP3 -DCURL_DISABLE_RTSP -DCURL_DISABLE_SMB -DCURL_DISABLE_SMTP -DCURL_DISABLE_TELNET -DCURL_DISABLE_TFTP -DCURL_STATICLIB -DENABLE_IPV6 -DHAVE_ASSERT_H -DOS="unknown" -DHAVE_ZLIB_H -DHAVE_LONGLONG -DHAVE_LIBZ -DHAVE_BOOL_T -DHAVE_STDBOOL_H -DHAVE_GETADDRINFO -DHAVE_GETPEERNAME -DHAVE_GETSOCKNAME -DCURL_DISABLE_NTLM -DCURL_DISABLE_FTP -DUSE_WINDOWS_SSPI -DUSE_SCHANNEL -DWIN32 -DUSE_THREADS_WIN32 -DHAVE_IOCTLSOCKET_FIONBIO -DUSE_WINSOCK <object> -c <source>
```

### Static library construction

```text
lib /OUT:<static library> <object files>
```
