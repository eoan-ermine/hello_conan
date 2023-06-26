# hello_conan

Example of using the conan package manager

## Build

```shell
mkdir build && cd build
conan install .. -of .
cmake --preset conan-release .
cmake --build build
```
