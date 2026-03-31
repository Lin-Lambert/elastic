# Elasticsearch 项目工作记忆

## 项目概述
- 当前 workspace 包含一系列 Elasticsearch 学习文档（elastic.md ~ elastic7.md）
- 文档体系：核心优势与原理(elastic2) → 查询流程(elastic1) → 核心概念(elastic3) → Node节点(elastic4) → 分页方式(elastic5) → 核心API五大类(elastic6) → 补充API六大类(elastic7) → 字段类型(elastic) → 全部核心API完全指南(elastic8)

## 文档风格约定
- 使用中文撰写，技术术语保留英文
- 代码示例使用 JSON 格式（Elasticsearch DSL）
- 使用 PlantUML 绘制流程图和架构图
- 每篇文档包含目录、代码示例、注意事项
- 通俗类比帮助理解抽象概念

## WorkBuddy Skills
- 已将 `.gemini/skills/` 下的两个 skill 转换为 WorkBuddy 格式
  - `markdown-writing-style` → `.workbuddy/skills/markdown-writing-style/SKILL.md`
  - `plantuml-guideline` → `.workbuddy/skills/plantuml-guideline/SKILL.md`

## 2026-03-24 工作记录
- 将 `.gemini/skills/` 中的 Gemini 格式 skill 转换为 WorkBuddy 格式（description 改为第三人称触发语，正文改为祈使句风格）
- 创建 `elastic7.md`：Elasticsearch 六大补充实用 API 指南（Ingest API、Multi-Search API、Index Template API、Snapshot API、Reindex API、Point In Time API），每个 API 含概念说明、内置组件速览、实战代码示例
- 创建 `elastic8.md`（1325 行）：从零重新整理 Elasticsearch 全部核心 API 完全指南，覆盖 12 大类 API（Index、Document、Search、Mapping、Ingest、Index Template、Reindex、Snapshot、PIT、Cluster、Cat、Suggesters），每个 API 配真实代码示例，含 SQL 类比、注意事项、速查表
