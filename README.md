# which-header

`which` for header files.
That is, `which-header` searches the paths for each header files.

## Examples

```sh
$ which-header fcntl.h
/usr/include/fcntl.h

$ which-header -a openssl/ssl.h
/usr/local/include/openssl/ssl.h
/usr/include/openssl/ssl.h

$ which-header -c++ ctime
/Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/../include/c++/v1/ctime
```
