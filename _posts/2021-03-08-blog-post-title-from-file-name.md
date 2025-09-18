---
title: "Blog Post Title From First Header"
date: 2021-03-08
author: "Ssomeone"
categories: [技术, 教程]
tags: [Jekyll, GitHub Pages]
description: "这是一个演示创建笔记的示例"
excerpt: "学习如何在 Jekyll 博客中添加代码高亮和格式化内容"
image: "/assets/images/default-post.jpg"  # 可选：文章封面图
# toc: true  # 可选：显示目录
comments: true  # 可选：允许评论
---

## 这是一篇示例博客文章。您可以在这里讨论各种有趣的事情

---

## 支持语言高亮

---

### Python 示例

```python
def fibonacci(n: int) -> int:
    """返回斐波那契数列的第 n 项"""
    if n <= 1:
        return n
    a, b = 0, 1
    for _ in range(2, n + 1):
        a, b = b, a + b
    return b


print(f"斐波那契数列第 {10} 项是: {fibonacci(10)}")
```

### TypeScript 示例

```typescript
interface User {
    id: number;
    name: string;
    email: string;
}

function createUser(id: number, name: string, email: string): User {
    return { id, name, email };
}

const user = createUser(1, "someone", "abc@example.com");
console.log(user);
```
