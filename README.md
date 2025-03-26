# AI 电商内容生成系统（MVP）

## 🧠 项目目标（一句话）

打造一个电商场景下的 AI 内容生成工具，用户输入商品信息或链接，系统自动生成高质量的小红书文案 + 视频脚本结构，作为可交付的内容方案，最终发展为 SaaS 工具。

---

## 🎯 核心功能模块（当前聚焦）

### A. 批量电商文案生成
- 输入：商品标题、卖点或链接
- 输出：多风格小红书种草文案（如情绪化、种草款、专业分析）

### B. 视频拍摄脚本生成
- 输入：商品定位、人设、风格
- 输出：镜头结构 + 拍摄台词 + 节奏建议（可扩展为图文/分镜图）

---

## ⚙️ 当前使用工具 & 技术基础（MVP阶段）

- **飞书多维表格**：作为结构化数据中台，记录输入 & 生成输出
- **DeepSeek R1**：作为文案生成 & 脚本生成的大模型
- **Cursor**：前端可视化生成，快速搭建原型页面（由我完成）
- **（可选）Coze**：用于对话式输入/体验演示（后续可替代为前端表单）

---

## 📦 当前已具备内容（已在 repo 中）

- `prompts.txt`：当前使用的 R1 Prompt 模板（文案 + 脚本）
- `output-example.md`：样例输出文案（展示最终结构）
- `README.md`：本文件，用于项目沟通

---

## 🧩 希望你（CTO）协作的部分

> 🚧 目标是将目前跑通的流程，包装成可演示的产品原型（前后端联调）

### 技术协作需求：

- 构建输入界面（商品名 / 链接输入 → 调用生成）
- 对接飞书表格 / DeepSeek API（或模拟 API，先结构通）
- 输出页面结构化展示（文案块 + 镜头卡 + 可下载）
- 生成过程中的任务流 / 状态记录（如果能连接飞书任务更好）

---

## 🚀 升级路径（我们之后可以继续做的）

- 接入图像生成（如 Midjourney / Runway）
- 图生视频 or 拍摄任务拆解系统
- 内容模板库 + 用户偏好推荐
- 提供 SaaS 账号系统 / 数据管理后台

---

## 📬 联系 & 协作方式

- GitHub Repo：你在看这个
- 可以拉你为协作者，一起迭代（已设置为私有仓库）
- 飞书文档、表格、API Token 可私聊提供

---

> 本项目由我（产品 Owner / 系统架构设计者）主导结构设计，当前已完成前期思维路径 + 工具整合 + 内容生成逻辑，等你一起把它变成真正能跑起来的 AI 核弹级批量内容生成器
