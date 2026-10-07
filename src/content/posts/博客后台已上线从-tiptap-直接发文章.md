---
title: 博客后台已上线：从 TipTap 直接发文章
description: 验证整条链路：后台富文本编辑 → 转 Markdown + Firefly front-matter → 推送 GitHub → Netlify 自动重建。
image: "https://admin.carlos.cc.cd/images/ae18e28c-9d0a-48f1-b401-48582bbbbd53.png"
tags: []
category: 随笔
published: 2026-10-07
pinned: false
draft: false
slug: 博客后台已上线从-tiptap-直接发文章
---

这是通过后台发布的第一篇文章，用来验证整条链路：**TipTap 编辑器** → 转成 Markdown → 推送到 GitHub → Netlify 自动重建。

## 支持的语法

斜体、~~删除线~~、`行内代码`、[链接](https://admin.carlos.cc.cd) 都能正常转换。

- 无序列表
- 嵌套的有序列表

  1. 第一项
  2. 第二项

```javascript
console.log("hello from the admin");
```

> 引用块也会被保留。

| 功能 | 状态 |
| --- | --- |
| 富文本编辑 | 已上线 |

***

文章会出现在 `src/content/posts/` 目录，可随时在仓库里手动微调。
