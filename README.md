# <!--
#   仓库说明（中文注释）
#   文件: README.md
#   用途: 介绍仓库目的、主要目录和如何本地预览/部署。
#   编辑提示:
#    - 本仓库由 Jekyll 生成，主题为 minima。
#    - 本地预览命令（需安装 Ruby 与 bundler）: `bundle exec jekyll serve --livereload`
#    - 发布到 GitHub Pages: 推送到 `main` 分支，GitHub 会自动部署。
# -->

# 仓库介绍

## 🎯 仓库用途

这是一个 **GitHub Pages 个人博客网站** 仓库，属于用户 `liushihowe`（刘士豪）的个人主页和博客系统。

### 核心功能

- **个人主页展示**：介绍博主的学术背景、研究兴趣和技术栈
- **博客文章发布**：支持 Markdown 格式的博客文章
- **项目作品集**：展示个人项目和研究成果
- **在线简历**：作为个人品牌和学术展示平台

## 🏗️ 技术架构详解

### 1. **Jekyll 静态站点生成器**

```yaml
# _config.yml 核心配置
theme: "minima"           # 使用 Jekyll 的 minima 主题
plugins:
  - jekyll-feed          # RSS 订阅功能
  - jekyll-sitemap       # 自动生成站点地图
```

### 2. **GitHub Pages 托管**

- 仓库名 `liushihowe.github.io` 表明这是 GitHub Pages 的用户站点
- 访问地址：`https://liushihowe.github.io`
- 自动部署：推送到 `main` 分支即可自动更新网站

## 📁 目录结构详解

### **配置文件**

- _config.yml：Jekyll 站点配置，包含个人信息、主题设置、插件配置
- index.md：网站首页内容，展示个人介绍

### **页面布局**

```
_layouts/
├── post.html          # 博客文章页面模板
_includes/
├── head.html          # HTML 头部组件
├── navlinks.html      # 导航链接组件
└── sharelinks.html    # 社交分享组件
```

### **内容目录**

```
_posts/                # 博客文章目录
├── 2021-03-08-blog-post-title-from-file-name.md
archive.md             # 博客归档页面
```

### **静态资源**

```
css/
├── override.css       # 自定义样式覆盖
js/
├── highlightjs/       # 代码高亮功能
    ├── highlight.min.js
    ├── languages/     # 支持多种编程语言
    └── styles/        # 代码高亮主题
```

## 👨‍🎓 博主信息

根据配置文件，这是 **刘士豪** 的个人博客：

- **身份**：西安电子科技大学-广研院 计算机技术方向研究生
- **邮箱**：`shhliu@stu.xidian.edu.cn`
- **GitHub**：[@liushihowe](https://github.com/liushihowe)
- **研究方向**：深度学习、计算机视觉相关领域

## 🚀 功能特性

### **博客功能**

- ✅ Markdown 文章撰写
- ✅ 代码语法高亮（支持 T-SQL、PowerShell 等）
- ✅ 文章归档和分类
- ✅ RSS 订阅
- ✅ 社交分享

### **技术特色**

- 📱 响应式设计（minima 主题）
- 🔍 SEO 优化（sitemap、meta 信息）
- 💻 代码高亮（多语言支持）
- 🎨 自定义样式覆盖

## 🎯 使用场景

这个仓库非常适合：

1. **学术研究者**：展示研究成果、发表论文解读
2. **技术博客**：分享编程经验、项目实践
3. **求职展示**：作为在线简历和作品集
4. **知识分享**：记录学习笔记、技术总结

这是一个设计精良的个人技术博客网站，利用 GitHub Pages 的免费托管服务，为研究生阶段的学术和技术展示提供了专业的平台。
