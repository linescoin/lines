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
