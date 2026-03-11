# agent-patterns-vault

个人使用的 LLM 资产仓库，用来沉淀和检索值得长期复用的：

- agents
- skills
- MCP
- 提示词模式
- 工作流设计

仓库结构：

- `agents/`：整理好的可复用 agent
- `skills/`：整理好的可复用 skill
- `mcps/`：整理好的 MCP 配置、接入说明和案例
- `patterns/`：通用设计模式、提示词框架、流程方案
- `notes/`：个人理解、对比、学习记录
- `catalog/`：索引和标签，不放正文
- `templates/`：标准模板
- `scripts/`：后续自动化脚本

## 使用方式

### 1. 先补齐关键信息

新内容进入仓库前，至少先确认：

- 来源是否明确
- 用途是否明确
- 当前状态是否明确

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


## 命名约定

- 目录和文件优先使用英文 `kebab-case`
- 正式条目一个主题一个目录
- `README.md` 作为条目入口

## 最低元信息

正式条目的编目信息建议维护在 `catalog/` 对应索引中，至少包含：

- `title`
- `type`
- `tags`
- `source`
- `status`
- `summary`
