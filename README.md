# docker-crossbuild-cmake-tools

cmake toolchain file

## build-win
`cmake -DCMAKE_TOOLCHAIN_FILE=./tools/win.cmake`
## build-osx
`cmake -DCMAKE_TOOLCHAIN_FILE=./tools/osx.cmake`
## build-linux
`cmake -DCMAKE_TOOLCHAIN_FILE=./tools/linux.cmake`

## docker env
- multiarch/crossbuild: https://github.com/multiarch/crossbuild