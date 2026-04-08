# 南极星（中南指北 / CSU Star）

中南大学在校生专属的学习资源共享与课程/教师评教参考平台。

## 核心功能

- **学习资源共享**：上传/下载课件、真题、笔记等（PDF/Word/PPT/图片），积分驱动，机器+人工双重审核
- **教师评价**：3 维度评分（教学质量、给分宽松度、考勤要求），教师排行榜
- **课程评价**：3 维度评分（作业量、收获感、考试难度），课程排行榜
- **积分体系**：签到/上传/邀请获取积分，下载消耗积分，完整流水记录
- **社交互动**：点赞、收藏、评论（二级回复）、举报、纠错
- **个人中心**：上传记录、下载历史、评价记录、积分明细、收藏列表
- **通知中心**：审核结果、被点赞/评论等站内通知
- **后台管理**：资源/评价审核、举报/纠错/反馈处理、用户管理、公告管理
- **身份认证**：微信/QQ OAuth 登录，双 Token 机制，未登录仅可浏览

## 技术栈

| 层级 | 选型 |
|------|------|
| 前端 | Next.js · Ant Design Mobile · Zustand · TypeScript |
| 后端 | Go · Gin · GORM · Zap |
| 数据库 | PostgreSQL · Redis |
| 存储/CDN | 腾讯云 COS · 腾讯云 CDN |
| 部署 | Docker Compose · Nginx · Certbot |
| CI/CD | GitHub Actions · Husky + lint-staged |
| 监控 | Loki · Grafana |
| 安全 | 腾讯云 WAF · 内容安全 API · ClamAV |

## 快速启动（本地）

```bash
cp .env.example .env
docker compose up -d --build
```

- 前端：http://localhost:3000
- 后端：http://localhost:8080
- API 文档：http://localhost:8080/swagger/index.html

## 文档

见 [docs/](docs/) 目录（所有文档以数据库设计 V1.6 为唯一事实来源对齐）：

- [产品需求文档](docs/产品需求文档.md) — PRD V1.2
- [功能清单](docs/功能清单.md) — 用户故事与验收标准 V1.1
- [架构设计](docs/架构设计.md) — 系统架构与数据流 V1.1
- [数据库设计](docs/数据库设计.md) — 23 张表 DDL + Redis 键设计 V1.6
- [接口规范](docs/接口规范.md) — REST API 规范 V1.2
- [OpenAPI](docs/openapi.yaml) — OpenAPI 3.0.3 机器可读规范
- [项目计划](docs/项目计划.md) — Sprint 划分与上线检查清单 V1.2

## License

MIT
