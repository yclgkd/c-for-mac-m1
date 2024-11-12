# C++ Environment Setup for Mac M Series

[中文版本](#中文版本)

## Introduction

This project provides a quick setup for running and debugging C++ files on a Mac with M series chips. With Clang and the recommended plugins installed, you can easily run and debug C++ files from the sidebar's "Run and Debug" section.

## Requirements

- macOS on an M series chip
- Clang compiler
- Visual Studio Code (VS Code)
- Recommended VS Code extensions:
    - C/C++ by Microsoft
    - C++ Intellisense

## Setup Instructions

1. **Install Clang**:
     ```sh
     xcode-select --install
     ```

2. **Install Visual Studio Code**:
     Download and install VS Code from [here](https://code.visualstudio.com/).

3. **Install Recommended Extensions**:
     Open VS Code and install the following extensions:
     - C/C++ by Microsoft
     - C++ Intellisense

## Usage

1. Clone this project.
2. Open your C++ project in VS Code.
3. Navigate to the "Run and Debug" sidebar.
4. Select the `clang++ - Build and debug active file` configuration and click "Run" or "Debug".

---

# 中文版本

## 介绍

这个项目提供了一个在 Mac M 系列芯片上运行和调试 C++ 文件的快速设置。只需安装 Clang 和推荐的插件，您就可以轻松地从侧边栏的“运行和调试”部分运行和调试 C++ 文件。

## 要求

- 运行在 M 系列芯片上的 macOS
- Clang 编译器
- Visual Studio Code (VS Code)
- 推荐的 VS Code 扩展：
    - Microsoft 的 C/C++
    - C++ Intellisense

## 设置说明

1. **安装 Clang**：
     ```sh
     xcode-select --install
     ```

2. **安装 Visual Studio Code**：
     从[这里](https://code.visualstudio.com/)下载并安装 VS Code。

3. **安装推荐的扩展**：
     打开 VS Code 并安装以下扩展：
     - Microsoft 的 C/C++
     - C++ Intellisense

## 使用方法

1. 克隆本项目
2. 在 VS Code 中打开您的 C++ 项目。
3. 导航到“运行和调试”侧边栏。
4. 选择`clang++ - Build and debug active file`配置并点击“运行”或“调试”。
