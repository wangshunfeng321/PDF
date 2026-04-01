# PDF

一个基于 RAG（检索增强生成）架构的 PDF 智能问答系统。  
用户可以上传 PDF 文件，输入问题，系统会自动检索文档内容并生成对应答案。

---

## ✨ 项目简介

本项目是一个使用 **Streamlit** 搭建的 Web 应用，结合 **LangChain + OpenAI + FAISS** 实现对 PDF 文档内容的智能问答。

适合用于：

- 论文内容问答
- 简历 / 报告快速检索
- 电子书 / 学习资料问答
- 文档内容总结与理解

---

## 🚀 功能特点

- 支持上传 **PDF 文件**
- 支持输入问题并基于文档内容进行回答
- 使用 **向量检索** 提高回答相关性
- 支持 **多轮对话记忆**
- 页面简洁，操作方便，适合快速部署与演示

---

## 🛠 技术栈

- **前端 / 应用框架**：Streamlit
- **大模型调用**：OpenAI
- **文档处理**：PyPDF
- **文本切分**：LangChain Text Splitter
- **向量数据库**：FAISS
- **问答链**：ConversationalRetrievalChain

---

## 📂 项目结构

```bash
.
├── main.py             # Streamlit 主程序入口
├── utils.py            # PDF处理、向量检索、问答逻辑
├── requirements.txt    # 项目依赖
└── README.md           # 项目说明文件
