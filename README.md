# agent-patterns-vault

个人使用的 LLM 资产仓库，用来沉淀和检索值得长期复用的：

- agents
- skills
- MCP
- 提示词模式
- 工作流设计
- 学习笔记与踩坑记录

本仓库采用“混合型、类型优先”的组织方式：

- `inbox/`：刚收集进来的原始内容，先入库再整理
- `agents/`：整理好的可复用 agent
- `skills/`：整理好的可复用 skill
- `mcps/`：整理好的 MCP 配置、接入说明和案例
- `patterns/`：通用设计模式、提示词框架、流程方案
- `notes/`：个人理解、对比、学习记录
- `catalog/`：索引和标签，不放正文
- `templates/`：标准模板
- `scripts/`：后续自动化脚本

## 使用方式

### 1. 快速收集

新看到的内容先放到 `inbox/`，最低要求：

- 记录来源
- 记录一句用途说明
- 记录当前状态

### 2. 整理沉淀

当某条内容值得长期复用时，再整理到正式目录：

- agent -> `agents/`
- skill -> `skills/`
- MCP -> `mcps/`
- 设计方法 -> `patterns/`

### 3. 查找

优先通过 `catalog/` 查找，再进入具体目录查看正文。

建议按以下维度检索：

- 类型：agent / skill / mcp / pattern / note
- 标签：code-review / rag / browser / research / orchestration
- 状态：collected / draft / validated / archived

## 推荐工作流

1. 先把内容存进 `inbox/`
2. 判断是否值得长期保留
3. 用 `templates/` 里的模板整理
4. 更新 `catalog/` 中的索引和标签
5. 再补 `notes/` 里的经验总结

## 命名约定

- 目录和文件优先使用英文 `kebab-case`
- 正式条目一个主题一个目录
- `README.md` 作为条目入口

## 最低元信息

正式条目建议至少包含：

- `title`
- `type`
- `tags`
- `source`
- `status`
- `summary`

## 当前状态

这是第一版基础骨架，适合先开始收集和整理，后续再根据使用习惯补自动化脚本和更细的索引。
