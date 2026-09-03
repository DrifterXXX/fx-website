# 期货投资分析考试备考平台 | China Futures Investment Analysis Exam Preparation Platform

中国期货投资分析资格考试在线备考平台，包含练习题、复习材料和音频背诵资源。

An online preparation platform for China's Futures Investment Analysis qualification exam, featuring practice questions, study materials, and audio memorization resources.

---

## 功能 | Features

- **复习宝典 Study Guide** — 按考试章节分类的完整复习材料 / Comprehensive review material organized by exam chapters
- **真题精练 Practice Questions** — 互动刷题模块，支持即时答案反馈 / Interactive quiz module with instant answer feedback
- **考前背诵 Pre-exam Memorization** — 核心考点快速记忆 / Quick recall of key exam points
- **音频支持 Audio Support** — 各章节配套 MP3/OGG 音频 / Chapter-aligned MP3/OGG audio

## 快速启动 | Quick Start

```bash
cd fx-website/public
python3 -m http.server 8080
```

打开 Open `http://localhost:8080`

## 构建 | Build

数据由 `exam-template` 工具从 JSON 数据生成：

Data is generated from JSON using the `exam-template` tool:

```bash
cd _archive/_build_tools
python3 build_final.py
```

## 技术栈 | Tech Stack

纯前端静态站点：HTML5 + CSS3 + JavaScript，JSON 数据驱动。

Static frontend site: HTML5 + CSS3 + JavaScript, driven by JSON data.

## 许可证 | License

MIT
