# Dog-Awesome 🐶

> 个人精选开源项目收藏夹 —— 分类收录有趣、有用、有创意的开源项目。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

---

## 📋 目录

- [AI Agent 工具](#ai-agent-工具)
- [AI & 机器学习](#ai--机器学习)
- [开发工具](#开发工具)
- [效率工具](#效率工具)
- [前端开发](#前端开发)
- [后端开发](#后端开发)
- [设计 & 创意](#设计--创意)
- [其他](#其他)

---

## AI Agent 工具

> 让 AI Agent 更强大、更高效的工具与框架。

- **[Agent Reach](https://github.com/Panniantong/Agent-Reach)** — 统一 Agent 网络访问层。把网页、YouTube、RSS、GitHub、Twitter/X、B站、Reddit、小红书、LinkedIn、V2EX 等渠道整合为一套 Agent 可调用的工具，自动选择当前最稳的接入方式。一键安装，告别「我无法访问」。
- **[Loop Engineering](https://github.com/cobusgreyling/loop-engineering)** — AI Agent 运行循环的系统化设计方法论与工具集。将零散的 prompt 工程升级为可复用的系统：automations 定时触发、worktrees 并行隔离、skills 存项目知识、plugins 接外部系统、sub-agents 做 checker 拆分、STATE 文件跨 session 记忆。含 7 个生产级 pattern + 3 个 CLI 工具（loop-audit / loop-init / loop-cost）。
- **[Obsidian CC](https://github.com/looping-engineering/obsidian-cc)** — Loop Engineering 生态的 Obsidian 插件，将 Agent 运行循环的设计模式集成到笔记工作流中。
- **[Agency Agents](https://github.com/msitarzewski/agency-agents)** — GitHub 116K+ Stars 的 AI 专家角色库。140+ 个结构化 Agent 角色（不仅是 prompt 模板，每个角色有独立人设、专业流程和可交付成果），覆盖工程、设计、产品、营销、销售、安全等 20 个部门。自带中国市场专家（小红书/抖音/微信/B站/飞书等）。一键安装到 Claude Code / Cursor / Copilot / Windsurf 等 18+ 工具，让 AI 编程助手变身为专业团队协作。

## AI & 机器学习

- **[Supervision](https://github.com/roboflow/supervision)** — 计算机视觉通用工具集。封装检测、追踪、标注、可视化等一整套 CV 常用功能，省去重复造轮子。做 CV 项目的基础设施级工具库。

## 开发工具

> 提升开发效率、改善代码质量的开源工具。

- **[Codebase-Memory-MCP](https://github.com/DeusData/codebase-memory-mcp)** — 将整个代码库索引为持久化知识图谱的 MCP 工具。亚毫秒级查询，号称比传统方式省 99% token。多仓库切换时不再需要反复喂代码上下文，对做 RAG 和代码智能的工具开发者尤为值得关注。
- **[lat.md](https://github.com/1st1/lat.md)** — 为代码库建立 Markdown 知识图谱。通过 `lat.md/` 文件夹存放架构、业务逻辑、测试规范等互链的 markdown 文件，配合 CLI（`init` / `check` / `locate` / `search`）让 Agent 用语义搜索替代无穷尽的 grep。项目大到 Agent 经常找不到关键约束时，最值得一试的方案。
- **[OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — AI 原生 Office 文档命令行工具，GitHub 8K+ Stars。零依赖单二进制文件，直接操作 Word/Excel/PPT，无需安装 Office 或 .NET 运行时。内置 MCP Server，一条命令 `officecli mcp claude` 即可注册到 Claude Code，让 AI Agent 直接创建、读取、修改 Office 文档。三层架构（JSON 读取 → DOM 路径寻址 → 原始 XML/XPath 回退），支持模板变量 `{{placeholder}}`、批量生成、实时预览（`officecli watch` 启动本地 Web 服务）。macOS / Windows / Linux 全平台可用。

## 效率工具

> 让日常工作更高效、更专注。

- **[Meetily](https://github.com/Zackriya-Solutions/meetily)** — 隐私优先的本地会议助手，GitHub 12K+ Stars。录音、转写、总结全部跑在本地，不上传任何服务器。Whisper + NVIDIA Parakeet 实时转写，macOS / Windows / Linux 三端 GPU 加速，总结环节可接 Ollama 本地模型或 Claude、Groq 等云端 API。涉及客户、合同、薪资等敏感会议的首选。

## 前端开发

*等待收录...*

## 后端开发

*等待收录...*

## 设计 & 创意

*等待收录...*

## 其他

> 跨领域、跨品类的实用工具。

- **[Spotube](https://github.com/KRTirtho/spotube)** — 开源跨平台音乐播放器，GitHub 46K+ Stars。基于 Flutter 构建，非 Electron 套壳，原生性能。使用 YouTube / Piped / Invidious 等公开音源，不依赖 Spotify API，无需账号即可免费串流。隐私优先（零遥测）、时间同步歌词、局域网远程控制、Discord Rich Presence、Last.fm / ListenBrainz 记录。macOS / Windows / Linux / Android / iOS 全平台可跑。

---

## 📝 收录标准

- 项目必须**开源**，有明确的开源协议
- 有一定的社区活跃度（Stars、最近更新等）
- 对开发者或创作者有实际价值
- 文档清晰，上手友好

## 🤝 贡献方式

欢迎通过 Issue 或 PR 推荐你觉得值得收录的开源项目！

---

> 🔗 GitHub: [ZhouYinLong-lab/Dog-Awesome](https://github.com/ZhouYinLong-lab/Dog-Awesome)
