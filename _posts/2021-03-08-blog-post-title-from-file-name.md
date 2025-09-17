---
title: "Blog Post Title From First Header"
date: 2021-03-08
author: "Shihao Liu"
categories: [技术, 教程]
tags: [Jekyll, GitHub Pages, 博客]
description: "这是一个演示如何使用 Jekyll 和 GitHub Pages 创建博客的示例文章"
excerpt: "学习如何在 Jekyll 博客中添加代码高亮和格式化内容"
image: "/assets/images/default-post.jpg"  # 可选：文章封面图
toc: true  # 可选：显示目录
comments: true  # 可选：允许评论
---

## Blog Post Title From First Header

Due to a plugin called `jekyll-titles-from-headings` which is supported by GitHub Pages by default. The above header (in the markdown file) will be automatically used as the pages title.

If the file does not start with a header, then the post title will be derived from the filename.

This is a sample blog post. You can talk about all sorts of fun things here.

---

## This is a header

### Some T-SQL Code

```tsql
SELECT This, [Is], A, Code, Block -- Using SSMS style syntax highlighting
    , REVERSE('abc')
FROM dbo.SomeTable s
    CROSS JOIN dbo.OtherTable o;
```

### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```
