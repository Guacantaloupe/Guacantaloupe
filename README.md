<div align="center">

<img src="https://capsule-render.vercel.app/api?type=transparent&height=100&text=Guacantaloupe&fontSize=42&fontColor=9C59D1&animation=fadeIn" alt="Guacantaloupe" />

<img src="https://img.shields.io/badge/Systems-FF218C?style=flat-square&labelColor=17151F" alt="Systems" /> <img src="https://img.shields.io/badge/Reverse%20Engineering-FFD800?style=flat-square&labelColor=17151F" alt="Reverse Engineering" /> <img src="https://img.shields.io/badge/Graphics-21B1FF?style=flat-square&labelColor=17151F" alt="Graphics" /> <img src="https://img.shields.io/badge/Machine%20Learning-9C59D1?style=flat-square&labelColor=17151F" alt="Machine Learning" />

<p><strong>Program Analysis · Decompilation · Reverse Engineering</strong></p>

</div>

I work on low-level systems, reverse engineering, graphics, and machine learning.  
我主要开发底层系统、逆向工程、图形和机器学习相关项目。

## 📚 Projects / 项目

| Project / 项目 | Area / 领域 | Overview / 简介 |
| :--- | :--- | :--- |
| **[glslPerftEngine](https://github.com/Guacantaloupe/glslPerftEngine)** <img src="https://img.shields.io/badge/-%20-FF218C?style=flat-square" height="12" alt="" /> | GPU Computing · Chess | An OpenGL compute-shader-based chess Perft program that counts legal move sequences on the GPU. It is not a complete chess AI. During development, I reported **NVIDIA GLSL compiler bug 6630275**, which NVIDIA confirmed and fixed.<br><br>使用 OpenGL 计算着色器，在 GPU 上统计国际象棋合法走法序列的 Perft 程序。它不是完整的国际象棋 AI。开发过程中，我报告了 NVIDIA GLSL 编译器错误 **6630275**，NVIDIA 已确认并修复。 |
| **[Reviewcentrifuge](https://github.com/Guacantaloupe/Reviewcentrifuge)** <img src="https://img.shields.io/badge/-%20-FF218C?style=flat-square" height="12" alt="" /> | Reverse Engineering · Program Analysis | Selected core code from a closed-source reverse-engineering project, shared for architecture and code-quality review. The project includes SSA, MemorySSA, and symbolic execution for program analysis, with opaque-predicate analysis as a related application. This repository is not the complete project and cannot be built on its own.<br><br>一个闭源逆向工程项目的部分核心代码，用于架构和代码质量评审。项目包含 SSA、MemorySSA 和符号执行，用于程序分析；不透明谓词分析是相关应用方向。仓库不是完整项目，无法直接构建。 |
| **[ReviewUefiVmxAppPkg](https://github.com/Guacantaloupe/ReviewUefiVmxAppPkg)** <img src="https://img.shields.io/badge/-%20-21B1FF?style=flat-square" height="12" alt="" /> | UEFI · Virtualization | Selected C source code from a UEFI and Intel VMX project for code review, covering VMX initialization, memory mapping, nested virtualization, and Windows boot loading. This repository is incomplete and cannot be built on its own.<br><br>用于代码评审的 UEFI 和 Intel VMX 项目部分 C 源码，涉及 VMX 初始化、内存映射、嵌套虚拟化和 Windows 启动加载。仓库不是完整项目，无法直接构建。 |
| **[paper](https://github.com/Guacantaloupe/paper)** <img src="https://img.shields.io/badge/-%20-FFD800?style=flat-square" height="12" alt="" /> | Static Analysis · MCP | A Windows executable static-analysis tool with disassembly, function analysis, control-flow graphs, and cross-references. It also provides MCP tools for AI clients.<br><br>用于 Windows 可执行文件静态分析的程序。支持反汇编、函数分析、控制流图和交叉引用，也提供供 AI 客户端通过 MCP 调用的工具。 |
| **[imgui-overlay](https://github.com/Guacantaloupe/imgui-overlay)** <img src="https://img.shields.io/badge/-%20-21B1FF?style=flat-square" height="12" alt="" /> | Graphics · API Hooking | A Dear ImGui-based overlay project with graphics API hooking code for DirectX 11, DirectX 12, OpenGL, and Vulkan.<br><br>基于 Dear ImGui 的覆盖层项目，包含 DirectX 11、DirectX 12、OpenGL 和 Vulkan 的图形 API Hook 代码。 |
| **[guadbg](https://github.com/Guacantaloupe/guadbg)** <img src="https://img.shields.io/badge/-%20-9C59D1?style=flat-square" height="12" alt="" /> | Windows Debugging · MCP | An experimental Windows debugger based on vectored exception handling (VEH), with breakpoints, memory inspection, an ImGui interface, and MCP tools.<br><br>基于向量化异常处理（VEH）的实验性 Windows 调试器，支持断点、内存查看、ImGui 界面和 MCP 工具。 |

## Related technologies / 相关技术

| Technology / 技术 | Reference / 相关链接 |
| :--- | :--- |
| **UEFI** | <a href="https://github.com/Guacantaloupe/ReviewUefiVmxAppPkg"><img src="./uefi.svg" alt="UEFI logo" height="55"></a> |
| **NASM** | <a href="https://www.nasm.us/"><img src="./nasm.png" alt="NASM logo" height="55"></a> |
