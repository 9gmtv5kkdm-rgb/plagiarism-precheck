---
name: plagiarism-precheck
slug: plagiarism-precheck
version: 1.0.0
displayName: 查重预检与降重
summary: 系统性查重规则解读与结构性降重方法论，帮助研究者理解重复率成因并进行合规降重。
description: |
  查重预检与降重方法论技能——不是查重工具，而是"查重规则理解 + 结构性降重方法论"的综合指南。
  覆盖 CNKI/Turnitin 查重原理、6 级降重策略金字塔、引用边界判定、AI 痕迹+查重双重策略、
  投稿前自查清单与工作流。与 SkillHub 已有的 plagiarism-checker（检测原创性）、
  paper-plagiarism-reducer（降重助手）互补——它们是操作工具，本技能教方法论。

  Plagiarism pre-check and reduction methodology skill — not a detection tool, but a comprehensive
  guide to understanding plagiarism check rules and structural reduction strategies. Covers
  CNKI/Turnitin principles, 6-tier rewriting pyramid, citation boundaries, AI+plagiarism dual
  strategy, and pre-submission checklist workflow. Complements existing plagiarism-checker and
  paper-plagiarism-reducer skills (detection tools) by providing the methodology those tools lack.

  触发词/triggers: 查重 降重 重复率 plagiarism 查重规则 CNKI查重 Turnitin 引用边界 学术不端检测
  学术降重 论文查重 知网查重 降重策略 改写降重 查重预检
---

# 查重预检与降重方法论

## 定位

本技能不是查重工具，而是**"查重规则理解 + 结构性降重方法论"**的综合指南。
帮助研究者理解"为什么重复"，并系统性降低重复率——不牺牲学术诚信，不依赖近义词机械替换。

## 与 SkillHub 已有技能的互补关系

| 已有技能 | 定位 | 与本技能的关系 |
|---|---|---|
| `plagiarism-checker` | 检测原创性 + AI 内容识别 | **互补** — 它检测，本技能教你理解检测结果并制定降重策略 |
| `paper-plagiarism-reducer` | 降重助手（检测+替换） | **互补** — 它做局部替换，本技能教结构性降重方法论和全局策略 |
| `plagiarism-detection` | 完整查重 Web 应用 | **互补** — 它是工具链，本技能是知识体系 |

**它们解决"是什么"（检测结果），本技能解决"为什么"（成因诊断）和"怎么做"（方法论）。**

## 技能结构

```
plagiarism-precheck/
├── SKILL.md                              ← 本文件（入口 + 概述）
├── README.md                             ← 中英双语导览
└── references/
    ├── plagiarism-rules-guide.md         ← CNKI/Turnitin 查重规则详解
    ├── rewriting-strategies.md           ← 6 级降重策略金字塔 + 改写技巧库
    ├── citation-boundaries.md            ← 引用边界判定指南
    ├── ai-plagiarism-dual-check.md       ← AI 痕迹 + 查重双重策略
    └── checklist-and-workflow.md         ← 投稿前自查清单 + 工作流
```

## 使用指南

### 快速上手（推荐路径）

1. **先了解规则** → 阅读 `plagiarism-rules-guide.md`，理解 CNKI/Turnitin 的判断逻辑
2. **掌握降重方法论** → 阅读 `rewriting-strategies.md`，学习 6 级策略金字塔
3. **检查引用边界** → 阅读 `citation-boundaries.md`，确保引用合规
4. **处理 AI 内容** → 阅读 `ai-plagiarism-dual-check.md`，了解 AI+查重双重策略
5. **投稿前执行** → 使用 `checklist-and-workflow.md` 的清单逐项检查

### 典型场景

- **"论文查重率 35%，怎么降到 15% 以下？"** → 先读 rules-guide 理解为何标红，再用 rewriting-strategies 制定降重计划
- **"AI 写的部分会不会被查重？"** → 读 ai-plagiarism-dual-check.md
- **"引用太多会不会标红？"** → 读 citation-boundaries.md
- **"投稿前要做哪些检查？"** → 使用 checklist-and-workflow.md

## 核心原则

1. **降重 ≠ 逃避学术诚信** — 目标是表达原创性，而非欺骗检测系统
2. **理解优于替换** — 真正理解文献后再用自己的话表达，优于近义词替换
3. **结构性改写 > 表面改写** — 段落重组、逻辑重构胜于词汇层面的微调
4. **引用是最低成本的降重** — 规范引用既保护学术诚信，又有效降低重复率

## 隐私声明

本技能中所有示例段落均为虚构文本（如"近年来，数字化转型已成为制造业发展的重要趋势…"），
不包含任何真实论文内容、真实作者信息或真实研究数据。
