---
title: 变更日志
tags:
  - meta
---

# 变更日志 log

记录每次新增资料、编译资料、更新页面和健康检查的结果。最新的写在最上面。

## 2026-06-29

### 初始化知识库基础设施

- 新建 `wiki/sources/README.md` — 来源摘要页模板与说明
- 新建 `outputs/health/README.md` — 健康检查说明（含七项检查清单与报告模板）
- 新建 `wiki/index.md` — 知识库索引与入口导航
- 新建 `wiki/log.md` — 本变更日志

### 收录资料：现有智能体框架分析

- 新增原始资料 `raw/articles/现有智能体框架分析.md`（标签 `article`）
  - 来源：《从零构建 AI Agent：大模型驱动的智能体设计与实践》第 2 章 2.4 节（第 25–31 页），扫描件经 OCR 整理
  - 内容：LangChain / AutoGen / CrewAI / LangGraph 四大框架分析 + 能力对比（表 2.2、图 2.4）
- 生成来源摘要页 `wiki/sources/现有智能体框架分析.md`
- 更新 `wiki/index.md`：在"当前主题 / 资料清单"中登记该资料

### 待办与待核验

- `wiki/sources/现有智能体框架分析.md` 的 `source_url` 标为"待补充"（纸质 / 扫描书籍，暂无网络链接）
- 概念页、实体页尚未提炼，已列入 index 待办
