# 🚀 太空跑酷 Space Runner

一个炫酷的 3D 太空无尽跑酷游戏，使用 Three.js 构建，所有视觉效果和音效均由程序化生成。

**🎮 [在线试玩 Play Now →](https://homodeus.github.io/space-runner/)**

![Space Runner](https://img.shields.io/badge/Game-Space%20Runner-00ffff?style=for-the-badge&logo=rocket&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-0.183.0-black?style=for-the-badge&logo=three.js)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## ✨ 游戏特色

- 🌌 **赛博朋克霓虹隧道** — 青色、紫色、粉色发光网格线构成的太空隧道
- 💎 **收集水晶得分** — 躲避障碍物，收集绿色发光水晶
- 🔮 **Bloom 辉光后处理** — 所有霓虹元素自带发光效果
- 🎆 **粒子尾迹 & 速度线** — 飞船拖尾效果，高速时速度线增强
- 💥 **碰撞屏幕震动** — 撞到障碍物时的震撼反馈
- 🎵 **程序化音效** — 环境低音、变道音效、水晶琶音、碰撞爆炸声
- ⚡ **逐步加速** — 速度从 1.0x 逐渐提升到 3.4x
- 📱 **支持触屏** — 手机端滑动和触屏按钮操控
- 🌟 **2000 颗星星背景** — 沉浸式太空氛围
- 🎮 **零外部素材** — 所有 3D 模型、特效、音效均程序化生成

## 🎮 操作方式

| 操作 | 键盘 | 手机 |
|------|------|------|
| 向左移动 | `←` 或 `A` | 左滑 / 点击左按钮 |
| 向右移动 | `→` 或 `D` | 右滑 / 点击右按钮 |
| 开始游戏 | `空格` 或 点击 | 点击屏幕 |

## 🛠️ 技术栈

- **Three.js** (v0.183.0) — 3D 渲染引擎
- **WebGL 2** — 硬件加速图形
- **EffectComposer** — Bloom 辉光后处理 + 自定义暗角着色器
- **Web Audio API** — 程序化音效合成
- **纯 HTML/CSS/JS** — 无需构建工具，单文件部署

## 🚀 本地运行

```bash
# 克隆仓库
git clone https://github.com/HomoDeus/space-runner.git
cd space-runner

# 用任意 HTTP 服务器打开（需要支持 ES modules）
npx serve .
# 或
python -m http.server 8000
```

然后在浏览器中打开 `http://localhost:8000`

## 📁 项目结构

```
space-runner/
├── index.html    ← 游戏主文件（所有代码集成在单文件中）
├── README.md     ← 本文件
└── LICENSE       ← MIT 开源协议
```

## 👦👧 作者

**杨乐天** & **杨乐达** — 8 岁小朋友

> 本游戏由 AI 辅助创建，展示了小朋友也可以用 AI 技术创造炫酷的 3D 游戏。

## 📄 开源协议

本项目基于 [MIT License](./LICENSE) 开源，欢迎自由使用和修改。

---

## English

### 🚀 Space Runner

A stunning 3D endless runner game set in a neon-lit space tunnel, built entirely with Three.js. All visuals and audio are procedurally generated — no external assets needed.

**Authors: Yang Letian & Yang Leda** — 8-year-old kids who created this game with the help of AI.

### Features
- Synthwave/cyberpunk neon tunnel with bloom glow effects
- Procedural spaceship, obstacles, collectibles, and particle effects
- Web Audio API synthesized sound effects and ambient drone
- Progressive difficulty with increasing speed
- Touch-friendly mobile controls
- Single HTML file, zero dependencies (beyond Three.js CDN)

### Play
👉 **[https://homodeus.github.io/space-runner/](https://homodeus.github.io/space-runner/)**
