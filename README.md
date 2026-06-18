# Lecto-MS-Agent
Smart Campus Lecture Recommendation Assistant: Automatically extracts lecture information from university emails, delivers personalized recommendations, and supports natural language Q&amp;A.

# Lecto-MS-Agent

**🎓 学校讲座智能推荐助手**  
基于 Microsoft Copilot Studio 构建的校园讲座推荐 Agent。

## ✨ 核心功能

- 智能识别学校邮件/公告中的讲座信息
- 根据用户兴趣精准推荐讲座
- 优先推送未来即将举办的活动
- 提供推荐理由（MatchScore）、讲者、日期、地点和报名链接
- 无匹配时推荐最接近的替代方案

## 🚀 快速测试 Agent

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
