---
# ===============================
# 页面说明（中文注释）
# 文件: archive.md
# 用途: 本页用于按标签/分类列出站点文章的存档。
# 编辑提示: 这是一个普通的 Jekyll 页面，内容使用 Liquid 模板语法循环 `site.tags`。
# 如果要修改显示格式，编辑下面的 HTML/Liquid 代码块；修改完可在本地用 `jekyll serve` 预览。
# ===============================

layout: page
title: 笔记
---

{% for tag in site.tags %}

### {{ tag[0] }}

{% for post in tag[1] %}

- [{{ post.date | date: "%B %Y" }} - {{ post.title }}]({{ post.url }})

{% endfor %}

{% endfor %}
