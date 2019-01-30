# VSCodeCMakeHelloWorldWithStaticLibrary
VSCode CMake Hello World with Static Library

## Setup Build

```
mkdir build
cd build
cmake ..
-- The C compiler identification is AppleClang 10.0.0.10001145
-- The CXX compiler identification is AppleClang 10.0.0.10001145
-- Check for working C compiler: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/cc
-- Check for working C compiler: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/c++
-- Check for working CXX compiler: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Configuring done
-- Generating done
-- Build files have been written to: /Users/william.best/Documents/GitHub/VSCodeCMakeHelloWorldWithStaticLibrary/build
```

## Build

```
cmake --build .
-- Configuring done
-- Generating done
-- Build files have been written to: /Users/william.best/Documents/GitHub/VSCodeCMakeHelloWorldWithStaticLibrary/build
Scanning dependencies of target helloworld
[ 25%] Building CXX object CMakeFiles/helloworld.dir/helloworld.cpp.o
[ 50%] Linking CXX static library libhelloworld.a
[ 50%] Built target helloworld
Scanning dependencies of target main.out
[ 75%] Building CXX object CMakeFiles/main.out.dir/main.cpp.o
[100%] Linking CXX executable main.out
[100%] Built target main.out
```

## Run

```
./main.out
Hello World
```