---
layout: default
title: 使用说明 | MAS ArXiv Daily
---

# 📚 MAS ArXiv Daily 使用指南

## 🎯 项目简介

**MAS ArXiv Daily** 是一个自动化的多智能体系统(Multi-Agent Systems)论文追踪工具，帮助研究者和学生及时了解该领域的最新研究进展。

### ✨ 主要特性

- **🤖 全自动化**：每8小时自动从ArXiv获取最新论文
- **📊 智能分类**：按研究主题自动分类展示
- **🔍 快速搜索**：支持标题、作者、关键词搜索
- **🔗 直接访问**：一键跳转到论文PDF和代码仓库
- **📱 响应式设计**：完美适配PC端和移动端
- **🌐 中英双语**：界面友好，支持中文用户

## 🔍 搜索与浏览

### 搜索功能
在页面顶部的搜索框中输入关键词，可以实时筛选论文：
- **论文标题搜索**：输入论文标题的任意部分
- **作者搜索**：输入作者姓名
- **关键词搜索**：输入技术关键词，如"reinforcement learning"、"MARL"等

### 快速导航
使用页面顶部的导航栏快速跳转到感兴趣的研究领域：

| 图标 | 领域 | 包含内容 |
|------|------|----------|
| 🧠 | 多智能体强化学习 | MARL、协作学习、竞争学习 |
| 🕸️ | 多智能体系统 | 分布式AI、MAS架构 |
| 🤝 | 多智能体协调 | 协调算法、任务分配 |
| 💬 | 多智能体通信 | 通信协议、信息传递 |
| ♟️ | 博弈论与MAS | 博弈论、机制设计 |
| 🐝 | 群体智能 | 蚁群算法、粒子群优化 |
| ⚖️ | 一致性与协议 | 分布式一致性、拜占庭容错 |
| 🎲 | 多智能体仿真 | ABM、仿真平台 |

## 📖 论文信息解读

每篇论文的展示包含以下信息：

### 📅 发布日期
论文在ArXiv上的最新更新日期

### 📝 论文标题
点击标题可以查看论文摘要（部分浏览器支持）

### 👨‍🎓 作者信息
显示第一作者，完整作者列表可在PDF中查看

### 📄 PDF链接
直接链接到ArXiv上的论文PDF文件

### 💻 代码链接
- **绿色按钮**：表示有官方代码仓库
- **"null"**：表示暂未发现公开代码

## 🚀 高级功能

### 📊 统计信息
页面顶部显示：
- **总论文数**：当前数据库中的论文总数
- **今日新增**：当天新增的论文数量
- **研究领域**：覆盖的研究方向数量
- **更新频率**：数据更新的时间间隔

### 🔖 个人收藏
- 使用浏览器书签功能收藏感兴趣的论文
- 推荐为论文页面添加标签，方便后续查找

### 📤 分享论文
- 复制论文链接分享给同事或朋友
- 使用社交媒体分享按钮

## 🔧 开发者信息

### 数据来源
- **ArXiv API**：获取论文元数据
- **Papers with Code**：获取代码仓库信息
- **GitHub Search**：补充代码链接

### 更新机制
1. **定时触发**：GitHub Actions每8小时运行一次
2. **关键词搜索**：基于预定义的关键词列表
3. **智能筛选**：过滤重复和不相关论文
4. **自动分类**：根据论文内容分配到相应类别

### 技术栈
- **后端**：Python + ArXiv API
- **前端**：Jekyll + GitHub Pages
- **自动化**：GitHub Actions
- **样式**：现代化CSS + Font Awesome图标

## 📞 反馈与建议

### 🐛 问题报告
如果您发现了问题，请：
1. 访问 [GitHub Issues](https://github.com/Alex-gitss/mas-arxiv-daily/issues)
2. 详细描述问题
3. 提供复现步骤（如果适用）

### 💡 功能建议
欢迎提出改进建议：
- 新的研究领域分类
- 搜索功能优化
- 界面改进建议
- 其他创新想法

### 📧 联系方式
- **GitHub**：[@Alex-gitss](https://github.com/Alex-gitss)
- **项目地址**：[mas-arxiv-daily](https://github.com/Alex-gitss/mas-arxiv-daily)

## 📚 相关资源

### 学习资源
- [多智能体系统导论](https://example.com) - 推荐教材
- [OpenAI Multi-Agent](https://openai.com/research/multiagent) - 研究进展
- [AAMAS会议](https://www.aamas-conference.org/) - 顶级会议

### 工具推荐
- **Zotero**：论文管理工具
- **Notion**：笔记整理
- **Overleaf**：LaTeX写作平台

---

<div style="text-align: center; padding: 2rem; background: #f8f9fa; border-radius: 10px; margin: 2rem 0;">
  <h3>🙏 致谢</h3>
  <p>感谢所有为多智能体系统研究做出贡献的学者们！</p>
  <p>本项目基于 <a href="https://github.com/Vincentqyw/cv-arxiv-daily">cv-arxiv-daily</a> 改进而来</p>
</div>
