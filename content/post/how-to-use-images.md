---
title: "博客使用指南：图片上传和文件下载"
date: 2026-07-19T16:00:00+08:00
draft: false
description: "详细介绍如何在博客中插入图片和提供文件下载"
categories:
  - 教程
tags:
  - 图床
  - PicGo
  - 使用指南
---

## 图片上传方案

本博客使用 **GitHub + jsDelivr + PicGo** 作为图床方案，完全免费且稳定。

### 方案特点

- ✅ **完全免费** - GitHub 仓库无限存储
- ✅ **全球 CDN** - jsDelivr 加速，访问速度快
- ✅ **永久保存** - 数据存储在 GitHub，不会丢失
- ✅ **一键上传** - 使用 PicGo 工具，截图后自动上传

### 使用步骤

1. **安装 PicGo** - 从 [GitHub Releases](https://github.com/Molunerfinn/PicGo/releases) 下载安装
2. **配置图床** - 在 PicGo 中设置 GitHub 图床参数
3. **上传图片** - 截图或拖拽图片到 PicGo，自动上传并复制链接
4. **插入文章** - 在 Markdown 中粘贴链接即可

### 示例图片

下面是一张示例图片：

![示例图片](https://cdn.jsdelivr.net/gh/Shema-Sunf/blog-images@main/images/example.png)

> 提示：实际使用时，将 `example.png` 替换为你上传的真实图片文件名。

---

## 文件下载功能

本博客支持提供文件下载功能。

### 如何使用

1. 将文件放入博客目录的 `static/downloads/` 文件夹
2. 在文章中使用 Markdown 链接引用：

```markdown
[点击下载示例文件](downloads/example.pdf)
```

### 示例下载

📎 [点击下载示例文档](/downloads/readme.txt)

> 提示：上面的链接是一个示例，你需要在 `static/downloads/` 目录下放入真实文件才能下载。

---

## 支持的文件类型

博客支持几乎所有常见的文件类型：

- 📄 文档：PDF、DOC、DOCX、TXT、MD
- 🖼️ 图片：JPG、PNG、GIF、SVG、WebP
- 📦 压缩包：ZIP、RAR、7Z、TAR
- 📊 数据：CSV、JSON、XML
- 🎵 音频：MP3、WAV、OGG
- 🎬 视频：MP4、WebM、OGV

---

## 注意事项

1. **GitHub 单文件限制** - 通过 GitHub 上传的文件单个不能超过 100MB
2. **大文件建议** - 超过 25MB 的文件建议使用云盘链接（如百度网盘、阿里云盘）
3. **版权注意** - 上传和分享的文件请确保拥有版权或符合开源协议

---

有任何问题，欢迎在下方评论区留言！💬
