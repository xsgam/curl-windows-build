# curl-windows-build
build curl project - https://github.com/curl/curl  by VSCode on windows

# install Build-Env & Tool
- VS Code - Using GCC with MinGW - https://code.visualstudio.com/docs/cpp/config-mingw

```
  In this tutorial, you configure Visual Studio Code to use the GCC C++ compiler (g++) and GDB debugger from mingw-w64 to create programs that run on Windows. After configuring VS Code, you will compile, run, and debug a Hello World program.  
```
- VS Code plugin
  - CMake Tools

- MinGW64 Env (64bit)

```
pacman -S --needed base-devel mingw-w64-x86_64-toolchain
pacman -S mingw-w64-x86_64-gcc mingw-w64-x86_64-windows-default-manifest  mingw-w64-x86_64-winpthreads mingw-w64-x86_64-gdb
pacman -S mingw-w64-x86_64-openssl mingw-w64-x86_64-zlib
pacman -S mingw-w64-x86_64-curl
pacman -S mingw-w64-x86_64-libpsl

```
# Build in VSCode 

- git clone https://github.com/curl/curl
- Open curl folder in Code
- Use CMake tools build source code.
