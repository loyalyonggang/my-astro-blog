---
title: Astro 入门指南
description: Astro 是一个现代化的静态站点生成器，专注于内容驱动的网站。
published: 2025-06-10
category: 技术
tags:
  - astro
  - 教程
  - 前端
---

## 什么是 Astro？

Astro 是一个**内容驱动的**静态站点生成器，它的核心理念是：

> 发送更少的 JavaScript 到浏览器。

## 核心特性

### 群岛架构（Islands Architecture）

Astro 允许你在静态页面中插入交互式组件，这些组件被称为"群岛"。

```astro
---
import InteractiveCounter from '../components/Counter.jsx';
---

<!-- 静态内容 -->
<h1>我的页面</h1>

<!-- 交互式群岛 -->
<InteractiveCounter client:load />
```

### 零 JavaScript 默认

Astro 组件默认不发送任何 JavaScript 到客户端，这意味着页面加载速度极快。

## 为什么选择 Astro？

| 特性 | Astro | 其他框架 |
|------|-------|----------|
| 性能 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ |
| SEO | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| 学习曲线 | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| 灵活性 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ |

## 总结

如果你正在构建一个以内容为主的网站，Astro 是一个绝佳的选择。
