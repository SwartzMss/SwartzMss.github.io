---
title: "StudyGuardian"
excerpt: "孩子学习桌智能守护系统 · Pi + ESP32 本地人脸/坐姿监测"
collection: portfolio
link: https://github.com/SwartzMss/StudyGuardian
---

部署在孩子学习桌前的本地化守护系统：Raspberry Pi 5 拉取 ESP32-CAM 视频流，端侧做人脸识别与坐姿检测，判定低头/驼背/头部过近等姿势，滑动窗口去抖，支持声音/屏幕/推送提醒，事件与抓拍写入 PostgreSQL 便于复盘，隐私不出本地。  
技术：Python、OpenCV、face_recognition、MediaPipe Pose、Raspberry Pi 5、ESP32-CAM、PostgreSQL、Rust 后端、React、Nginx、systemd  
介绍视频：<https://www.bilibili.com/video/BV1cy2sBpEmN/>
