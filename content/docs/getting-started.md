---
title: 快速开始
date: 2026-05-13T21:00:00+08:00
draft: false
weight: 1
---

## 当前状态

这个站点已经完成了 Hextra 的基础接入：

- 使用 Hugo 创建站点骨架
- 使用 Git submodule 安装 `themes/hextra`
- 将配置拆分到 `config/_default`
- 创建首页和文档入口

## 常用命令

启动本地预览：

```bash
hugo server --buildDrafts --disableFastRender
```

生成静态文件：

```bash
hugo
```

更新 Hextra 子模块：

```bash
git submodule update --remote themes/hextra
```

## 下一步

建议优先补齐这些内容：

1. 修改站点标题、描述和导航链接。
2. 创建 `content/posts/` 用于博客文章。
3. 增加关于页面和部署流程。
4. 确认是否开启搜索、评论和多语言。
