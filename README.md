# 🥠 AI Interaction Lab: 极简幸运饼干 (Fortune Cookie)

> **本项目作为 PPT 成果展示：探讨 AI 驱动下的极简交互设计与快速原型开发。**

这是一个基于 Web 技术的交互式原型，旨在展示如何通过 **AI 辅助编程**，在极短时间内完成从“视觉构思”到“自动化部署”的全流程。
操作操作指令：设计一个极简风格的幸运饼干 fortune cookie 交互界面。整体采用可爱手绘风。 用户点击幸运饼干后，饼干从中间打开，出现一张写有中英文正向能量有哲理寄语的便签纸。饼干裂开时伴随真实的“卡擦卡擦”模拟音效。用户可以点击抽出这张便签纸放大查看，便签纸上的中英文文字是老式打印机字体。不要图片

## 🚀 访问地址
**[点击立即体验](https://m25king.github.io/lucky-cookie/)**
*(建议使用 iPad 或手机访问，并“添加到主屏幕”以获得最佳 App 级体验)*

---

## 💡 PPT 核心展示方法论 (Methodology)

本项目开发过程严格遵循了我在 PPT 中提到的 **AI 辅助开发三部曲**：

### 1. 模块化提示词工程 (Modular Prompt Engineering)
不要求 AI 一次性生成完美代码，而是将需求拆解为：
* **视觉层 (CSS Drawing):** 采用纯代码绘制手绘风饼干，实现零图片加载（Zero-Image）。
* **交互层 (Physics Motion):** 利用贝塞尔曲线（Cubic-Bezier）模拟真实的物理阻力与回弹。
* **反馈层 (Audio Context):** 使用浏览器原生的 `Web Audio API` 实时合成碎裂声，而非加载音频文件。

### 2. 用户体验反馈循环 (UX Feedback Loop)
针对 iPad 端的特殊性进行针对性调优：
* **防缩放处理：** 锁定 `viewport` 防止双击缩放。
* **触控响应：** 移除 `-webkit-tap-highlight-color` 以获得更自然的点击反馈。

### 3. CI/CD 自动化部署
利用 **GitHub Actions** 实现代码提交即发布的“秒级更新”，体现了 AI 时代敏捷开发的极致速度。

---

## 🛠️ 技术栈 (Tech Stack)

* **HTML5 / CSS3:** 负责极简手绘风格的构筑。
* **JavaScript (Vanilla):** 处理随机语录库与交互逻辑。
* **Web Audio API:** 实时生成频率脉冲，模拟饼干折断声。
* **GitHub Pages:** 提供全球 CDN 托管。

---

## 🤖 关键提示词 (Key Prompts)

在演示中，你可以参考以下引导 AI 的核心 Prompt：

> "设计一个极简风格的幸运饼干交互界面。要求采用纯代码手绘风，不使用任何外部图片。用户点击后，利用 Web Audio API 模拟出真实的‘卡擦’音效，并伴随一个带阻尼感的裂开动画，随后展示中英文对照的能量语录。"

---

## 📜 能量语录库 (Sample Quotes)
* **"The best way to predict the future is to create it."** (预测未来最好的方式是创造它)
* **"Stay hungry, stay foolish."** (求知若渴，虚心若愚)
* **"AI is not the goal, but the compass."** (AI 不是终点，而是指引方向的指南针)

---

最后更新：2026.03.23  
**© 2026 M25KING Interaction Design Lab**
