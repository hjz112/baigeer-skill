# 白格尔 · 街头哲学 Perspective Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-Compatible-blue)](https://skills.sh)

> *「哲学家总是在解释世界，而重要的是改变世界。所以我不谈空的理论，我只想让大家用马克思的眼睛看当下。」*

基于 白格尔（抖音博主 baigeer）**184 条「街头哲学系列」视频**（2025-05 ~ 2026-10，263,867 字转写）深度蒸馏的人物视角 Skill，适用于支持 Agent Skills 的工具（Codex / Claude Code / Cursor / Gemini CLI 等）。

**用法**：作为思维顾问，用白格尔的视角分析社会现象、个人困境、政治经济议题，提供 **马克思主义 + 精神分析** 的批判性思考。当你对他说「用白格尔的视角」「白格尔会怎么看」「街头哲学」「用马克思主义看看这个问题」时激活。

## 内容

- 6 个核心心智模型（生产资料透镜 / 历史唯物主义 / 结构优先 / 欲望透镜 / 概念澄清 / 实践能动性），含证据、应用与局限
- 10 条决策启发式（先分概念 / 看结构 / 问谁获益 / 可控二分 / 警惕二元对立 / 证据优先 / 打破虚假礼貌 / 给框架不替决定 / 理论落地 / 大白话检验）
- 完整表达 DNA（街头设问开场 / 大白话拆概念 / 生活化类比 / 引用带出处）
- 人物时间线、价值观与反模式、智识谱系、诚实边界
- 保真度评分卡（FIDELITY.md，92/100 · A 级）

## 安装

```bash
# 方式一：skills.sh 一键安装
npx skills add hjz112/baigeer-skill

# 方式二：手动复制整个目录到你的 skills 目录
```

## 素材来源与版权

| 材料 | 数量 | 说明 |
|---|---|---|
| 抖音「街头哲学系列」视频 | 184 条 | 2025-05-04 ~ 2026-10-10 全量，约 263,867 字 |
| 转写工具 | - | 本地 whisper.cpp large-v3 + 千问云端 ASR（qwen-audio-3.1-asr-flash） |

⚠️ **版权提示**：视频口播内容版权归 白格尔 所有，仅作研究归档，不得商业/二次分发。详见 [NOTICE.md](NOTICE.md)。

## 仓库结构

```text
baigeer-perspective/
├── SKILL.md
├── README.md
├── LICENSE          # 本仓库原创内容 MIT
├── NOTICE.md        # 版权/来源/脱敏说明
├── FIDELITY.md
└── references/research/
    ├── README.md
    └── transcripts/   # 184 条视频转写（一手来源，日期_作品ID_标题.txt）
```

## 免责声明

本 Skill 为公开内容蒸馏，不替代专业建议；立场为白格尔本人的左派马克思主义视角，请用于思维拓展而非立场灌输。
