<div align="center">

# Awesome-Embedded-Learning-Studio 社区

[![组织](https://img.shields.io/badge/Organization-Awesome--Embedded-orange?logo=github)](https://github.com/Awesome-Embedded-Learning-Studio)
[![许可证](https://img.shields.io/badge/License-MIT-lightgrey)](./LICENSE)
[![位置](https://img.shields.io/badge/Location-China-red?logo=googlemaps)]()

**欢迎来到我们的组织级社区交流中心！**

这里是讨论、公告、问答以及一切与嵌入式学习相关话题的聚集地。

[快速上手](#-快速上手) ·
[讨论区](#-讨论区) ·
[项目一览](#-项目一览) ·
[参与贡献](#-参与贡献) ·
[联系方式](#-联系方式)

</div>

---

## 关于我们

**Awesome-Embedded-Learning-Studio** 是一个开源的嵌入式学习工作室，由两位充满热情的开发者创立：

| 成员 | 角色 | 专注方向 |
|------|------|----------|
| [Charliechen114514](https://github.com/Charliechen114514) | C/C++ 程序员 | 固件开发、工具链、C++ 教程、构建系统 |
| [HNHKHNH](https://github.com/HNHKHNH) | 硬件工程师 | PCB 设计、原理图、硬件调试 |

我们的目标很简单：

> 做"能学到东西"的嵌入式小玩具——不只是展示成果，而是提供完整的固件、PCB 设计和教学资料，帮助更多人入门嵌入式。

---

## 快速上手

刚来到这里？按以下步骤开始：

1. **浏览我们的[中心仓库](https://github.com/Awesome-Embedded-Learning-Studio/Awesome-Embedded)** — 所有项目的出发点
2. **阅读 [Roadmap](https://github.com/Awesome-Embedded-Learning-Studio/Awesome-Embedded/blob/main/roadmap.md)** — 了解我们正在做什么以及接下来的计划
3. **参与讨论** — 打个招呼、提问或者分享你的想法
4. **选择一个项目** — 查看[项目清单](https://github.com/Awesome-Embedded-Learning-Studio/Awesome-Embedded/blob/main/ProjectLists.todo/ProjectLists.todo.md)，找到你感兴趣的

---

## 讨论区

本仓库承载整个组织的 **GitHub Discussions**，请按以下分类使用：

| 分类 | 用途 |
|------|------|
| **Announcements（公告）** | 版本发布、里程碑更新、组织级通知 |
| **General（综合讨论）** | 自由交流、自我介绍、闲聊 |
| **Ideas & Feedback（想法与反馈）** | 提出新项目建议、改进意见 |
| **Q&A（问答）** | 关于任何仓库的技术问题 |
| **Show and Tell（成果展示）** | 分享你使用我们项目做出的作品 |

### 讨论小贴士

- **先搜索** — 可能已经有人问过同样的问题
- **描述具体** — 附上错误信息、硬件型号或仓库链接
- **善用分类** — 帮助大家更快找到和筛选话题

---

## 项目一览

以下是我们正在进行的所有项目总览：

### 教程与学习资源

| 仓库 | 简介 |
|------|------|
| [Tutorial_STM32_BareMetal](https://github.com/Awesome-Embedded-Learning-Studio/Tutorial_STM32_BareMetal) | STM32 裸机编程教程（F103/F407） |
| [Tutorial_FreeRTOS](https://github.com/Awesome-Embedded-Learning-Studio/Tutorial_FreeRTOS) | FreeRTOS 开源教程系列 |
| [Tutorial_AwesomeModernCPP](https://github.com/Awesome-Embedded-Learning-Studio/Tutorial_AwesomeModernCPP) | 现代 C++（C++11–23）嵌入式开发教程 |
| [Tutorial_AwesomeQt](https://github.com/Awesome-Embedded-Learning-Studio/Tutorial_AwesomeQt) | Qt 开发教程 |
| [Tutorial_cpp_SimpleIniParser](https://github.com/Awesome-Embedded-Learning-Studio/Tutorial_cpp_SimpleIniParser) | 手搓一个最简单的 INI 解析器 |
| [Tutorial_EmbeddedCommonTools](https://github.com/Awesome-Embedded-Learning-Studio/Tutorial_EmbeddedCommonTools) | 嵌入式通用开发工具教程 |

### 驱动与平台支持

| 仓库 | 简介 |
|------|------|
| [ST-Forge](https://github.com/Awesome-Embedded-Learning-Studio/ST-Forge) | STM32 HAL 驱动与示例，原生 CMake 构建，无 IDE 依赖 |
| [BareMetal-Drivers](https://github.com/Awesome-Embedded-Learning-Studio/BareMetal-Drivers) | 面向所有 MCU 项目的共享裸机驱动库 |
| [imx-forge](https://github.com/Awesome-Embedded-Learning-Studio/imx-forge) | i.MX6ULL 补丁集：U-Boot、内核、根文件系统 |
| [rk-forge](https://github.com/Awesome-Embedded-Learning-Studio/rk-forge) | Rockchip 补丁集：U-Boot、内核、根文件系统 |

### 应用与产品项目

| 仓库 | 简介 |
|------|------|
| [Project_MicroWatch](https://github.com/Awesome-Embedded-Learning-Studio/Project_MicroWatch) | 面向资源受限 MCU 的智能手表 — 秒表、闹钟、Dino 小恐龙游戏、计步器、指南针 |
| [CFDesktop](https://github.com/Awesome-Embedded-Learning-Studio/CFDesktop) | 可部署到任意嵌入式设备的 Qt 桌面环境 |
| [Project_MakeAMemroyPool](https://github.com/Awesome-Embedded-Learning-Studio/Project_MakeAMemroyPool) | 手写简易内存池（配套 B 站视频教程） |
| [Project_CXXBaseComponents](https://github.com/Awesome-Embedded-Learning-Studio/Project_CXXBaseComponents) | C++ 基础组件库（配套 B 站动画讲解） |

### 基础设施与工具

| 仓库 | 简介 |
|------|------|
| [qt-compile-pipeline](https://github.com/Awesome-Embedded-Learning-Studio/qt-compile-pipeline) | Qt6 自动化交叉编译流水线，支持 ARM/ARM64 |
| [PenguinLab](https://github.com/Awesome-Embedded-Learning-Studio/PenguinLab) | 从内核到用户空间，掌握嵌入式 Linux 与桌面 Linux 内核的动手实验场 |
| [CFBox](https://github.com/Awesome-Embedded-Learning-Studio/CFBox) | 用现代 C++23 编写的极简 BusyBox 替代品 |

---

## 技术栈

<p align="left">
  <img src="https://img.shields.io/badge/C-language-blue?logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C++-modern-blueviolet?logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Python-informational?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Qt-UI-lightgrey?logo=qt&logoColor=white" alt="Qt" />
  <img src="https://img.shields.io/badge/Embedded_Linux-lightgrey?logo=linux&logoColor=white" alt="Embedded Linux" />
  <img src="https://img.shields.io/badge/STM32-MCU-success?logo=arm&logoColor=white" alt="STM32" />
  <img src="https://img.shields.io/badge/CMake-Build-064F8C?logo=cmake&logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/GitHub_Actions-CI-black?logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---

## 参与贡献

我们欢迎一切形式的贡献！你可以：

- **报告 Bug** — 在对应仓库提交 Issue
- **提出建议** — 在讨论区的 **Ideas & Feedback** 分类发起讨论
- **提交代码** — Fork → 分支开发 → 提交 Pull Request
- **完善文档** — 教程和文档的改进永远是受欢迎的
- **分享作品** — 在 **Show and Tell** 分类展示你的成果

所有仓库默认使用 **MIT License**，另有说明除外。

---

## 行为准则

尊重他人，友善交流，共同学习。我们聚在这里，都是因为觉得嵌入式很有趣。

---

## 联系方式

- **GitHub Discussions** — 就在这里，随时发帖
- **Issues & PRs** — 在各仓库中提交，针对具体问题和代码
- **组织主页** — [Awesome-Embedded-Learning-Studio](https://github.com/Awesome-Embedded-Learning-Studio)

---

<div align="center">

*Keep it small, make it fun.*

</div>