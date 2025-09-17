---
title: "常见 commit message 模板清单"
date: 2025-09-17
author: "someone"
categories: [技术, 教程]
tags: [git]
description: "这是一个演示如何使用 Jekyll 和 GitHub Pages 创建博客的示例文章"
excerpt: "学习如何在 Jekyll 博客中添加代码高亮和格式化内容"
image: "/assets/images/default-post.jpg"  # 可选：文章封面图
toc: true  # 可选：显示目录
comments: true  # 可选：允许评论
---

## **常见 commit message 模板清单**

---

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
