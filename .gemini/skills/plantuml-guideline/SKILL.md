---
name: plantuml-guideline
description: 在 Markdown 中生成 PlantUML 图表的规范。支持时序图、组件图、ER图等复杂拓扑，通过 Server-Side 渲染（如 Markdown Preview Enhanced）解决本地 Graphviz 依赖问题。
---

# PlantUML for Markdown 规范

## 核心原则
- **Server-Side 渲染**：利用在线渲染服务器（如 PlantUML Server 或 Kroki），解锁全部 PlantUML 语法特性。
- **Resilient Diagrams**：确保在不安装 Graphviz 的环境下也能通过 IDE 插件正常预览。

## 语法规范
1. **块标示**：使用 <code>```plantuml</code> 开启代码块。
2. **闭环**：内容必须由 `@startuml` 和 `@enduml` 包裹。
3. **中文处理**：使用英文别名 (alias)，显示文字使用双引号 `""` 包裹以防乱码。

## 推荐类型
1. **时序交互图 (Sequence Diagram)**：代替 Mermaid 处理服务调用栈。
2. **组件图 (Component Diagram)**：展示微服务拓扑和分组。

## 自检清单
- 是否使用了标准的 `@startuml` 声明？
- 是否在图表前后提供了文字铺垫与总结？
- 节点别名是否为英文？
