
## dockpack.base_clang
[![Galaxy](https://img.shields.io/badge/galaxy-dockpack.base__clang-blue.svg?style=flat)](https://galaxy.ansible.com/dockpack/base_clang)

Ansible role to install LLVM and Clang.

- llvm-toolset-7.0 contains clang 7.0.1 (on Centos7/RHEL7)
- llvm-toolset contains clang 10.0.1 (on Centos8/RHEL8)

If you checkout this role and run `molecule converge`, then you'll have 2 Docker image with llvm-toolset, CMake, Git 2

```yaml
molecule dependencies:
 - dockpack.base_epel
 - dockpack.base_cmake
 - dockpack.base_git
```
