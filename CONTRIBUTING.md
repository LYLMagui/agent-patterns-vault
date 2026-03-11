# 维护规范

本仓库主要供个人使用，但仍保持一致的维护规则，避免后续难以检索。

## 目录规则

- 内容补齐关键信息后再整理到 `agents/`、`skills/`、`mcps/` 或 `patterns/`
- `catalog/` 只放索引和标签，不放正文

## 命名规则

- 文件和目录统一使用英文 `kebab-case`
- 正式条目使用独立目录
- 每个正式条目默认用 `README.md` 作为入口

## 状态规则

建议使用以下状态：

- `collected`：已收集，尚未整理
- `draft`：已初步整理
- `validated`：已验证，可复用
- `archived`：已归档，不建议继续使用

## 入库建议

### 正式条目

建议至少补齐：

- 用途
- 适用场景
- 输入输出约定
- 依赖工具
- 示例
- 限制与风险

## 索引更新

新增正式条目后，尽量同步更新：

- `catalog/agents-index.md`
- `catalog/skills-index.md`
- `catalog/mcps-index.md`
- `catalog/tags.md`

## 整理原则

- 先可检索，再追求完美
- 信息不足时先补齐关键上下文，不要急于入库
- 高价值内容优先沉淀为正式条目
