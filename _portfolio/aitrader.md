---
title: "AiTrader"
excerpt: "OKX 生态量化交易平台 · Rust API + Python Agent + React 前端"
collection: portfolio
---

AiTrader 围绕 OKX 搭建量化交易平台，交易执行与 AI 策略解耦：Rust API 服务承载账户/持仓/行情与调度，Python Agent（DeepSeek 推理）处理策略分析与下单工具调用，React 前端提供看板和人工触发入口。支持手动、定时、波动三种触发模式，全部通过 `.env` 配置，附带一键构建与 nginx/systemd 部署脚本，方便在模拟盘或实盘间切换。  
技术：Rust、Python、React、OKX API、量化交易  
链接：<https://github.com/SwartzMss/AiTrader>
