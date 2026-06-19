# Lecto-MS-Agent
Smart Campus Lecture Recommendation Assistant: Automatically extracts lecture information from university emails, delivers personalized recommendations, and supports natural language Q&amp;A.


## ✨ Features

- Automatically extracts lecture information from Outlook emails
- AI-powered lecture recommendations based on user interests
- Prioritizes upcoming events
- Natural language Q&A about lectures and seminars
- Provides speaker, venue, registration link, and deadline
- Real-time retrieval from SharePoint using Power Automate Actions
- Built entirely with Microsoft Power Platform (No Code / Low Code)

## 🏗️  overview

```text
                 University Outlook
                         │
                New Lecture Email
                         │
                         ▼
          Power Automate Email Trigger
                         │
                         ▼
      AI Lecture Information Extraction
                         │
                         ▼
         SharePoint LectureEvents List
          (Structured Lecture Database)
                         │
                         ▼
         Microsoft Copilot Studio (LectO)
                         │
               User Natural Language Query
                         │
                         ▼
             Power Automate Action (Flow)
                         │
                         ▼
             SharePoint Get Items
                         │
                         ▼
          Read Structured Lecture Information
                         │
                         ▼
       AI Recommendation & Response Generation
                         │
                         ▼
            Personalized Lecture Recommendation
```



## 🚀 Test Agent

**[🔗 在线测试 Lecto Agent](https://copilotstudio.preview.microsoft.com/environments/f96d48ea-4f2a-ed23-b57b-17fbbc352a19/bots/crcce_Lecture_ttS834/canvas?__version__=2&enableFileAttachment=false&cliAgent=true)**

> 此链接为 Copilot Studio 预览界面，可直接与 Agent 对话测试讲座推荐功能。
> 
> **注意**：此为预览链接，仅限有权限的用户访问。正式使用请通过 Teams 搜索 Lecto。

## 🛠️ 技术信息

- **平台**：Microsoft Copilot Studio
- **模型**：Claude Sonnet 4.5
- **Solution 类型**：Managed
- **版本**：1.0.0.2
- **导出日期**：2026-06-18

## 📥 如何导入使用

1. 在 Copilot Studio 中打开 **Solutions**
2. 点击 **Import solution**，上传 `Lecto_MS_xxx_managed.zip`
3. 导入完成后，重新添加 Knowledge Sources（SharePoint / PDF 等）
4. Publish Agent 到 Teams / Microsoft 365

## 📁 文件结构

- `Lecto_xxx_managed.zip` —— Copilot Studio 解决方案包
- `solution.xml` —— Agent 核心配置（解压后可见）

## 🔄 版本历史

- **v1.0.0.1** (2026-06-18)：初始发布版本

## 📧 联系与反馈

欢迎提交 Issue 或联系作者优化 Agent。

---

*Powered by Microsoft Copilot Studio*
