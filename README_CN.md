# M5Stack 硬件开源仓库

中文 | [English](README.md)

欢迎来到 M5Stack 硬件开源仓库！本仓库包含 M5Stack 系列产品的硬件设计文件，包括 PCB 设计、结构文件和 KiCad 库。

## 📁 目录结构

```
M5_Hardware/
├── Common/              # 通用模块设计（Atomic、Module、Unit 类型）
├── Products/            # 具体到 SKU 的产品设计文件
│   ├── [SKU_Name]/
│   │   ├── PCB/        # PCB 设计文件
│   │   └── Structures/ # 2D/3D 结构文件
│   └── ...
├── KiCad/              # KiCad 库文件
│   ├── 3D/             # 3D 模型
│   ├── Footprints/     # 封装库
│   └── Symbols/        # 符号库
└── Docs/               # 文档资料
```
