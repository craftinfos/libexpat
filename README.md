#〈〉 Craftinfo to build the expat parser library

[libexpat](https://github.com/libexpat/libexpat)


## Install

Uses a slightly modified version from [mulle-nat](https://github.com/mulle-nat) without tests and a `CMakeLists.txt` bugfix, to
not require a C++ compiler:


```console
mulle-sde dependency add --c --singlephase https://github.com/mulle-nat/libexpat/archive/R_2_2_1.C.tar.gz
```
