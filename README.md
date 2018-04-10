## Introduction
LINES based on CryptoNote protocol which focused on privacy, security and untraceability. 

Our main goal is to provide maximal accessibility and ease to use.

## Building

## Ubuntu 14.XX LTS, 16.XX LTS

```
sudo apt-get update
sudo apt-get -y install build-essential gcc g++ git cmake libboost-all-dev
git clone https://github.com/linescoin/lines
cd lines
export CXXFLAGS="-std=gnu++11"
make
```
## One of the ways to compile sources on windows using Visual Studio 2017:
1. Download and install boost libraries(https://boost.org/), make sure you've installed msvc 14.1 version.
2. Get cmake 2.8.6 or later.
3. Install Visual Studio 2017 with “Desktop development with C++” and “VC++ v140 toolchain” packages.
4. Open the command line, go to the source directory that contains @cmakelists.txt
    Execute command
    ```
    cmake -G "Visual Studio 15 2017 Win64"
    ```
5. Now you have VS solution files. Just compile them to have binaries
  Good luck!
