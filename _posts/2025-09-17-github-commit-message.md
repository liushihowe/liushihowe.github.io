---
title: "常见 commit message 模板清单"
date: 2025-09-17
author: "someone"
categories: [技术, 教程]
tags: [git]
description: "这是一个演示如何使用 Jekyll 和 GitHub Pages 创建博客的示例文章"
---

### **常见 commit message 模板清单**

---

<!--
	Post Front Matter 说明（中文注释）
	- title: 文章标题
	- date: 文章日期，格式 YYYY-MM-DD
	- author: 作者名字
	- categories/tags: 用于文章分组与检索
	- description/excerpt: 页面摘要，影响分享时的显示内容
	- toc/comments: 是否显示目录与评论功能（根据主题支持）
	编辑提示: 修改 front matter 后，请使用 `jekyll serve` 本地预览页面效果。
-->

### 🔹 常见分类（推荐用动词 + 分类前缀）

一般遵循 [Conventional Commits](https://www.conventionalcommits.org/) 风格：

+ **feat**：新增功能

```plain
feat: add search feature to header
```

+ **fix**：修复 bug

```plain
fix: correct typo in login form
```

+ **docs**：文档相关（README、注释、帮助文档等）

```plain
docs: update installation guide in README
```

+ **style**：代码风格（空格、缩进、格式化，不影响逻辑）

```plain
style: format code with prettier
```

+ **refactor**：代码重构（不改变功能逻辑，但结构优化）

```plain
refactor: simplify user authentication logic
```

+ **test**：测试相关

```plain
test: add unit tests for utils
```

+ **chore**：杂项（依赖管理、构建脚本、CI/CD 配置）

```plain
chore: update dependencies
```

+ **perf**：性能优化

```plain
perf: improve query efficiency in database
```

---

### 🔹 写 commit 的小技巧

1. **简洁**：一句话就够，不要写成长篇大论。
2. **动词开头**：add / update / fix / improve / remove / refactor …
3. **具体一点**：比起 `update README`，写成 `docs: add install section in README` 更清楚。
