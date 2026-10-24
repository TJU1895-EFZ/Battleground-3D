# 孤岛吃鸡 3D — 第一人称大逃杀

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Three.js](https://img.shields.io/badge/Three.js-r0.160-blue)](https://threejs.org/)

> 100 人空降孤岛，第一人称视角，活到最后吃鸡！

## 截图 / 预览

在浏览器中直接打开 `Battleground-3D.html` 即可游玩，无需安装任何依赖。

## 特性

- **100 人大逃杀** — 99 个 AI 对手，第一人称视角
- **5 种武器** — 手枪、突击步枪、狙击枪、霰弹枪、冲锋枪
- **智能 AI** — 人机具备巡逻、搜索、交战、躲避、拾取等行为逻辑
- **毒圈机制** — 多阶段安全区收缩，经典大逃杀体验
- **小地图** — 右下角实时显示敌人位置和圈型
- **HUD** — 血条、弹药、击杀数、淘汰播报
- **零依赖** — 单个 HTML 文件，Three.js 通过 CDN 加载

## 操作说明

| 按键 | 功能 |
|------|------|
| **WASD** | 移动 |
| **鼠标** | 视角控制 |
| **左键** | 射击 |
| **R** | 换弹 |
| **E** | 拾取武器 |
| **Shift** | 疾跑 |

## 快速开始

1. 下载或克隆本仓库
2. 双击 `Battleground-3D.html` 在浏览器中打开
3. 点击 **"点击进入战场"** 开始游戏

> 建议使用 Chrome / Edge / Firefox 等现代浏览器，支持 Pointer Lock API。

## 技术栈

- **Three.js r160** — 3D 渲染
- **原生 JavaScript (ES Module)** — 游戏逻辑
- **零构建工具** — 单文件即玩

## 文件结构

```
Battleground-3D/
├── Battleground-3D.html   # 游戏主文件（全部逻辑在一个文件中）
├── README.md              # 本文件
└── LICENSE                # MIT 许可证
```

## 开发

本项目为单文件游戏，无需构建步骤。直接编辑 `Battleground-3D.html` 即可。

## License

[MIT](LICENSE)
