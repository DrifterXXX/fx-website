# 期货投资分析考试备考平台

中国期货投资分析资格考试在线备考平台，包含练习题、复习材料和音频背诵资源。

## 功能

- **复习宝典** — 按考试章节分类的完整复习材料
- **真题精练** — 互动刷题模块，支持即时答案反馈
- **考前背诵** — 核心考点快速记忆
- **音频支持** — 各章节配套 MP3/OGG 音频

## 快速启动

```bash
cd fx-website
cd public
python3 -m http.server 8080
```

打开 `http://localhost:8080` 即可访问。

## 构建

数据由 `exam-template` 工具从 JSON 数据生成：

```bash
cd _archive/_build_tools
python3 build_final.py
```

## 许可证

MIT
