---
title: 知识库索引
tags:
  - meta
---

# 知识库索引 index

这里说明本知识库当前有哪些主题、资料和入口。每次新增资料或整理后更新本页。

## 这是什么

一个用「文件夹 + Markdown + Obsidian + Git」搭建的个人知识库，思路参考 Karpathy LLM Wiki。
不做企业级 RAG，不上复杂数据库，先用最小闭环把"收集原始资料 → 整理成知识条目 → 可追溯、可检查"跑通。

维护规则见 [`CLAUDE.md`](../CLAUDE.md)。

## 目录结构

```
raw/        原始资料，只增不改不删
  articles/   文章（标签 article；微信公众号追加 wechat）
  papers/     论文（标签 paper）
  clips/      网摘片段（标签 clip）
wiki/       整理后的知识条目
  sources/    来源摘要页（每份 raw 资料对应一张）
  concepts/   概念页
  entities/   实体页（人物、产品、框架、组织等）
  syntheses/  综合页（跨资料的主题梳理）
  index.md    本页：主题、资料与入口
  log.md      变更与健康检查日志
outputs/    产出物
  qa/         问答
  health/     健康检查报告
```

## 入口导航

- 来源摘要页模板与说明：[`wiki/sources/README.md`](sources/README.md)
- 健康检查说明：[`outputs/health/README.md`](../outputs/health/README.md)
- 变更日志：[`wiki/log.md`](log.md)

## 当前主题

### 智能体 / AI Agent

- 来源摘要：[[现有智能体框架分析]] — LangChain / AutoGen / CrewAI / LangGraph 四大框架分析（来源：《从零构建 AI Agent》第 2 章）
  - 原始资料：`raw/articles/现有智能体框架分析.md`
- 来源摘要：[[扣子智能体构建平台：功能、能力与应用]] — 字节跳动智能体构建平台 Coze 的定位、核心理念、五大功能模块与五类应用
  - 原始资料：`raw/articles/扣子智能体构建平台：功能、能力与应用.md`

## 资料清单

| 类型 | 文件 | 来源摘要页 | 状态 |
| --- | --- | --- | --- |
| article | `raw/articles/现有智能体框架分析.md` | [[现有智能体框架分析]] | 已收录 |
| article | `raw/articles/扣子智能体构建平台：功能、能力与应用.md` | [[扣子智能体构建平台：功能、能力与应用]] | 已收录 |

## 待办

- [ ] 从《现有智能体框架分析》提炼概念页（如 ReAct、链式推理、规划器、DAG 任务编排等）到 `wiki/concepts/`
- [ ] 为 LangChain / AutoGen / CrewAI / LangGraph 建立实体页到 `wiki/entities/`
- [ ] 补全来源摘要页的 `source_url`（当前为"待补充"，因来源是纸质 / 扫描书籍）
- [ ] 补全《扣子智能体构建平台》的 `source`/`source_url`（原始资料未注明出处）
