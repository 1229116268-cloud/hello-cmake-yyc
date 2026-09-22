# 算法第一次培训作业

## 1. 项目简介
本项目是 RoboMaster 新生第一次培训作业。使用 CMake 构建一个简单的 C++ 程序，预期输出 "Hello, RoboMaster!"。

## 2. 环境信息
- OS: macOS 27.0 (Apple Silicon)
- 编译器: AppleClang 16.0.0(兼容g++)
- 构建工具: CMake

## 3. 目录结构
- `src/`：源代码目录
- `images/`：成功截图目录
- `CMakeLists.txt`：CMake 构建脚本
- `.gitignore`：Git 忽略规则

## 4. 构建步骤
在仓库根目录下依次执行：
```bash
cmake -S . -B build
cmake --build build


## 5. 预期结果
执行‘。/build/hello',终端输出:
'''text
——“Hello, RoboMaster!"