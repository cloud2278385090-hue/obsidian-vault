---
created: 2026-05-04
tags:
  - MOC
  - index
type: MOC
---

# 知识库索引 🧠

> 这是你的第二大脑总入口

---

## 📅 日常
[[00 - Daily/2026-05-04|今日日记]] | [[00 - Daily/日记模板|日记模板]]

## 📥 收集
[[01 - Inbox/收集箱]] — 所有临时想法

## 🚀 项目
[[02 - Projects/项目模板]] | [[02 - Projects/项目索引]]

## 🎯 领域
[[03 - Areas/领域索引]] — 专注领域和责任范围

## 📚 资源
[[04 - Resources/资源索引]] — 书籍、文章、课程

## 🗃️ 归档
[[05 - Archives/归档索引]]

---

## 📊 统计

- 插件: {{formula: (length list "obsidian-tasks-plugin")}}
- 模板: [[__Templates]]

---

## 🏷️ 热门标签

```dataview
TABLE tag AS "标签", length AS "数量"
FLATTEN file.tags AS tag
WHERE tag != "daily"
GROUP BY tag
SORT length DESC
LIMIT 20
```

---

*由 灵境🤖 管理 · 第二大脑启动于 2026-05-04*
