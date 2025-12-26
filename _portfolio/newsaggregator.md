---
title: "NewsAggregator"
excerpt: "RSS 新闻聚合服务 · 多源抓取、智能去重、前后端一体"
collection: portfolio
link: https://github.com/SwartzMss/NewsAggregator
---

NewsAggregator 聚合多源 RSS/Atom，定时抓取并结合 ETag/Last-Modified 与标题相似度、DeepSeek 语义判定做智能去重，文章与来源写入 PostgreSQL，React + Vite 前端提供阅读、订阅管理与标题搜索，附带管理员后台和 nginx/systemd 部署脚本，适合自建新闻流或学习抓取/去重/前后端联调。  
技术：Rust、Axum、PostgreSQL、React、Vite、RSS、DeepSeek  
介绍视频：<https://www.bilibili.com/video/BV1dDCiBKE2B>
