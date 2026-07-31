# resume_manage
This is a serverless, browser-native web application designed to automatically synthesize professional resumes and act as a personal experience retrieval assistant. It runs entirely locally within a single HTML file, ensuring ultimate data privacy while maintaining powerful AI capabilities.
# AI Resume & Knowledge Graph Manager
> 一个基于纯前端架构 (Pure Frontend Architecture) 的零依赖、高隐私 AI 简历与全景图谱管理工具。

## 项目简介 (Project Introduction)
本项目是一个完全在浏览器端运行的 AI 工具，旨在通过大语言模型 (Large Language Model, LLM) 自动提取、提炼和排版个人经历，生成高度结构化的 Markdown 简历。同时，内置了轻量级的细节回忆助手，帮助应对面试中的深度提问。

核心设计理念是**绝对的数据隐私 (Absolute Data Privacy)**：无需任何后端服务器 (Backend Server) 或数据库 (Database)，所有敏感的简历数据和应用编程接口密钥 (Application Programming Interface Key, API Key) 均通过本地存储 (Local Storage) 保存在用户设备上。

## 核心特性 (Core Features)
* ** 多模型兼容 (Multi-Model Compatibility)**: 无缝对接 DeepSeek、OpenAI 或任何兼容官方数据格式的自定义接口，通过跨域资源共享 (Cross-Origin Resource Sharing, CORS) 直接发起调用。
* ** 前端朴素检索增强生成 (Frontend Naive Retrieval-Augmented Generation, RAG)**: 无需沉重的向量数据库 (Vector Database)，在浏览器内存中通过原生 JavaScript 实现极简检索引擎，完美解决超长学术文献（如毕业论文）带来的中间丢失 (Lost in the Middle) 效应。
* ** 智能数据管道 (Smart Data Pipeline)**: 针对长文本采用滑动窗口切分 (Sliding Window Chunking) 与词频打分 (Term Frequency Scoring) 机制，实现精准的 Top-K 召回 (Top-K Retrieval)。
* ** 现代交互体验 (Modern UX/UI)**: 包含拖拽上传区 (Drag & Drop Zone)、局部加载状态 (Localized Loading State) 以及原生折叠面板，排版精美且符合专业简历规范。

##  快速开始 (Quick Start)
本项目追求极致的极客体验，**零环境配置 (Zero Environment Configuration)**。

1. 克隆或下载本仓库到本地。
2. 双击打开 `resume.html` 文件（推荐使用 Chrome 或 Edge 浏览器）。
3. 在左侧设置面板输入你的 API Key。
4. 拖拽你的 PDF 或 TXT 经历文件到虚线框内，点击生成即可！

## 🛠️ 技术栈 (Tech Stack)
* **前端 (Frontend)**: HTML5, CSS3, Vanilla JavaScript
* **文档解析 (Document Parsing)**: PDF.js, Marked.js

## 👩‍💻 关于作者 (About the Author)
目前就读于南洋理工大学 (NTU) 信号处理与机器学习 (Signal Processing and Machine Learning, SPML) 方向的硕士研究生，致力于未来在科研导向的博士项目中继续深造。本项目源于日常学术研究和项目开发中对高效、安全的信息管理工具的真实需求。

## 📄 开源协议 (License)
MIT License
