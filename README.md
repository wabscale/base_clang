
## dockpack.base_clang
[![Galaxy](https://img.shields.io/badge/galaxy-dockpack.base__clang-blue.svg?style=flat)](https://galaxy.ansible.com/dockpack/base_clang)
![Build Status](https://api.travis-ci.com/dockpack/base_clang.svg)

Ansible role to install or compile LLVM and Clang.

- llvm-toolset-7 contains LLVM 5.0.1.
- llvm-toolset-6.0 contains LLVM 6.0.1
- llvm-toolset-7.0 contains LLVM 7.0

llvm-toolset-6.0 is made available from Springdale Linux.

If you checkout this role and run `molecule converge`, then you'll have a Docker image with llvm-toolset-6.0, CMake, GCC 8.3.1.


molecule dependencies:
 - dockpack.base\_epel
 - dockpack.base\_cmake
 - dockpack.base\_gcc
 - dockpack.base\_git
