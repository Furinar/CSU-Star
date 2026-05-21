<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=1E90FF&height=80&section=header" />

# 🌟 已关服的南极星 (CSU Star) 

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=1E90FF&center=true&vCenter=true&width=435&lines=Welcome+to+CSU+Star;中南大学学习资源共享与评教平台;Make+CSU+Great+Again)](https://git.io/typing-svg)

**CSU Star，中南大学在校生专属的学习资源共享、课程评教与校园生存指南生态**

[![License](https://img.shields.io/badge/License-GPL_v3-blue.svg?style=for-the-badge)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)](http://makeapullrequest.com)

</div>

## 📖 项目简介

**南极星 (CSU Star)** 是一个面向中南大学全体师生的一站式综合性校园知识共享与互助生态平台。旨在打破大学校园内的信息差，帮助同学们获取更真实、有用的课程评价、优质学习资料以及生存指南。

我们的口号是：**Make CSU Great Again!**

## 🧩 核心子模块介绍

本项目采用前后端分离的现代化生态架构，由以下四个核心子模块构成集群：

### 1. 🖥️ 前端 (CSU Star Frontend)
- **路径**：[`/csu-star-frontend`](./csu-star-frontend)
- **简介**：面向学生用户的核心大前端，提供课程评价、资料下载、社交互动、排行榜等丰富功能。采用极具现代感的响应式设计。
- **技术栈**：Next.js 15+ (App Router), Tailwind CSS, Zustand, TypeScript

### 2. ⚙️ 后端 (CSU Star Backend)
- **路径**：[`/csu-star-backend`](./csu-star-backend)
- **简介**：坚如磐石的业务支撑中心。处理用户认证（OAuth/邮箱）、资源上下架审核、评分计算等复杂的后台逻辑。
- **技术栈**：Go 1.26, Gin, PostgreSQL + GORM, Redis

### 3. 🛠️ 管理后台 (CSU Star Admin)
- **路径**：[`/csu-star-admin`](./csu-star-admin)
- **简介**：基于 Lithe Admin 深度定制的现代化后台管理系统，用于用户管理、举报处理、资源审核和数据统计等运营操作。轻巧而优雅。
- **技术栈**：Vue 3, Naive UI, Vite, Tailwind CSS, Pinia

### 4. 📚 维基指南 (CSU Star Wiki)
- **路径**：[`/csu-star-wiki`](./csu-star-wiki)
- **简介**：全校开源共建的“生存指南”。收录了入学须知、选课避坑、近百个专业详细介绍、科研竞赛等海量图文科普内容。
- **技术栈**：VitePress

## 🚀 本地开发指南

由于本项目包含多个服务模块，推荐分别进入对应的子目录进行依赖安装和开发调试：

### 启动各模块
请参考各子模块下的 `README.md` 文件了解详细的启动步骤：
- [📖 前端模块运行指南](./csu-star-frontend/README.md)
- [📖 后端模块运行指南](./csu-star-backend/README.md)
- [📖 管理后台运行指南](./csu-star-admin/README.md)
- [📖 维基文档运行指南](./csu-star-wiki/README.md)

## 🤝 参与贡献

我们非常欢迎且需要各位 CSUer 的贡献！无论是提交 Issue 报告 Bug，还是提交 Pull Request 添加新特性，或是补充 Wiki 内容，我们都非常感激！

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 将您的更改推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 📄 开源协议

本项目采用 **[GPL-3.0 协议](./LICENSE)** 进行开源。
这意味着你可以自由地使用、修改和分发本项目的源代码，但要求所有基于修改的衍生作品也必须开源并采用相同的 GPL-3.0 协议。详细信息请参阅项目根目录下的 `LICENSE` 文件。

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=1E90FF&height=80&section=footer" />

<sub>Made with ❤️ for all CSUers</sub>

</div>
