---
date: "2025-07-14T21:41:07+08:00"
draft: flase
title: 'My First Post'
---

### 1. 理解 Hugo 目录结构

Hugo 站点的目录结构如下：

```
my-blog/
├── content              # 存放所有内容文件
│   ├── _index.md        # 博客首页内容
│   ├── posts            # 博客文章
│   │   ├── first-post.md
│   │   └── second-post.md
│   └── pages            # 博客页面
│       └── about.md     # 关于页面
├── data                 # 存放站点数据
│   ├── authors.yml      # 作者信息
│   └── config.toml      # 站点配置文件
├── i18n                 # 国际化语言文件
│   ├── en.toml          # 英文语言文件
│   └── zh.toml          # 中文语言文件
├── layouts              # 存放页面模板
│   ├── _default         # 默认模板
│   ├── partials         # 模板片段
│   └── index.html       # 首页模板
├── assets               # 存放编译前的资源文件
│   ├── css              # 存放 CSS 源文件
│   ├── js               # 存放 JavaScript 源文件
│   └── images           # 存放图片源文件
├── resources            # 存放生成的资源文件
│   └── _gen             # 生成的资源文件
├── static               # 存放静态资源（如图片、CSS、JS）
│   ├── css              # 存放编译后的 CSS 文件
│   ├── js               # 存放编译后的 JavaScript 文件
│   └── images           # 存放图片文件
├── public               # 生成的网站文件
├── themes               # 存放主题文件
│   └── my-theme         # 自定义主题文件
│       ├── layouts      # 存放页面模板
│       ├── static       # 存放主题静态资源
│       └── theme.toml   # 主题配置文件
├── archetypes           # 内容模板文件
│   ├── default.md       # 默认内容模板
│   └── post.md          # 博客文章模板
└── hugo_build.lock      # Hugo 包管理文件
```

