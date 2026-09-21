# ESP32 Desktop Robot / ElectronBot Hardware Adaptation

> 基于 ElectronBot 相关开源资料与嘉立创 EDA 工程整理的桌面机器人硬件项目资料。  
> 本仓库重点展示硬件工程、PCB 适配、传感器/舵机相关板卡整理与调试记录；固件源码如后续找回，可继续补充到 `firmware/` 目录。

## 项目说明

本项目来自个人参与整理和修改的 `ElectronBot语音绿荫修改版` 嘉立创 EDA 工程。项目内容包含 ElectronBot 主板、语音/传感器相关板卡、舵机相关板卡等硬件设计资料。

该项目不是从零原创的完整机器人系统，而是基于 ElectronBot 相关开源项目/资料进行学习、修改、适配和调试。仓库后续补充原始开源链接后，应保留原作者信息和许可证说明。

## 我的参与内容

- 整理 ElectronBot 相关嘉立创 EDA 硬件工程。
- 修改/适配语音传感器、舵机控制相关板卡工程。
- 参与硬件连接、板卡调试、供电和接口适配。
- 根据实际装配情况进行项目版本整理和备份。
- 将云端工程导出为可在 GitHub 展示和归档的项目结构。

## 工程内容

从工程包中可识别到的板卡包括：

- `ElectronBot`
- `语音传感器二合一`
- `传感器二合一绿荫改版0.8mm`
- `舵机多合一`
- `舵机板绿荫改版0.8mm`
- `舵机板小肥羊版本备份`
- `小卡语音传感器二合一备份`

从工程元件信息中可见该项目涉及：

- STM32 系列 MCU
- MPU6050 姿态传感器
- Type-C / USB 相关接口
- 音频/语音相关芯片与接口
- 舵机连接与控制相关板卡
- LCD/显示、按键、电源管理等外围电路

具体器件清单见 [`docs/bom-summary.csv`](docs/bom-summary.csv)，板卡列表见 [`docs/board-list.csv`](docs/board-list.csv)。

## 目录结构

```text
.
├── README.md
├── docs/
│   ├── bom-summary.csv
│   └── board-list.csv
├── hardware/
│   └── source-package/
│       └── ProProject_ElectronBot语音绿荫修改版.epro
└── images/
    └── 项目截图、实物图待补
```

## 如何打开工程

1. 安装或打开嘉立创 EDA 专业版。
2. 导入 `hardware/source-package/ProProject_ElectronBot语音绿荫修改版.epro`。
3. 查看原理图、PCB、板卡和元器件库信息。

## 待补充资料

- [ ] 原 ElectronBot 开源项目链接
- [ ] 原项目许可证说明
- [ ] 机器人实物照片
- [ ] 调试过程照片或视频
- [ ] 固件源码或烧录说明
- [ ] 个人实际修改点的更详细记录

## 求职展示重点

这个项目主要体现：

- 对开源硬件项目的学习、复现和适配能力
- 嘉立创 EDA 工程整理能力
- 嵌入式硬件连接、供电、舵机/传感器板卡调试经验
- 项目资料归档和工程交付意识
