# cmake JSON 工程模板

## 一 编译

### 1.1 环境

在windows下使用`Vscode+cmake`进行编译与运行，使用的插件有`C/C++` `C++ Intellisense` `CMake` `CMake Tools`

### 1.2 文件结构

```
|
|-build
|-lib
  |--CMakeLists.txt
  |--cJSON.c
  |--cJSON.h
|-src
  |--CMakeLists.txt
  |--main.cpp
|-CMakeLists.txt

```

### 1.3 参考

CSDN博客：<https://blog.csdn.net/ALexander_Monster/article/details/106341754>

## 二 运行

1. 将`template\build\lib\`下生成的动态库文件`libCJSON.dll`复制到`template\build\src`下，也就是让动态库文件和可执行文件`.exe`放在一起
2. 按`F5`开始运行调试