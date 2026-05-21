# AGENTS.md

## 项目信息

- 个人网站域名：`eliza-notes.com`
- GitHub 仓库：`eliza0908/eliza0908.github.io`

## 核心目录结构

- 文章目录：`content/posts/`
- 静态图片目录：`static/images/`

## 文章 Front Matter 规范

以后只要由 AI 生成或修改新文章，必须严格包含以下标准 YAML Front Matter 格式：

```yaml
---
title: "文章标题"
date: 创建时间
tags: ["标签1", "标签2"]
draft: false
---
```

## 后续工作流目标

打通以下写作与发布流程：

1. Obsidian 写作
2. Cursor 预览润色
3. GitHub Actions 自动部署
