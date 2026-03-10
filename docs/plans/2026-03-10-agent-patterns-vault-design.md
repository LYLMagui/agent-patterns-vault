# agent-patterns-vault 设计文档

- 日期：2026-03-10 22:00 UTC+8
- 执行者：Codex
- 状态：已确认

## 目标

创建一个个人使用的 Git 仓库，用来统一沉淀和管理：

- 自建 agent
- 收集或改造的 skill
- MCP 配置与案例
- 通用提示词模式
- 工作流与设计方法
- 学习笔记

## 设计结论

采用“混合型、类型优先”的结构：

- 混合型：同时支持快速收集与长期沉淀
- 类型优先：按 `agents/`、`skills/`、`mcps/`、`patterns/` 分类
- 索引补主题：通过 `catalog/` 和标签管理主题，而不是按主题拆顶层目录

## 目录结构

- `inbox/`：原始收集区
- `agents/`：正式 agent
- `skills/`：正式 skill
- `mcps/`：正式 MCP
- `patterns/`：设计模式
- `notes/`：个人笔记
- `catalog/`：索引与标签
- `templates/`：条目模板
- `scripts/`：后续自动化脚本

## 元信息

正式条目建议统一保留：

- `title`
- `type`
- `tags`
- `source`
- `status`
- `summary`

状态采用：

- `collected`
- `draft`
- `validated`
- `archived`

## 使用流程

1. 新内容先进入 `inbox/`
2. 有价值的内容再整理为正式条目
3. 同步更新 `catalog/`
4. 经验、对比、踩坑进入 `notes/`

## 设计理由

- 仅做归档会导致后续复用成本高
- 仅做模板库会导致前期整理门槛高
- 混合型结构更适合个人长期积累与逐步沉淀

## 后续可扩展项

- 自动生成索引脚本
- 按标签搜索脚本
- 条目批量标准化脚本
- 版本化模板演进记录
