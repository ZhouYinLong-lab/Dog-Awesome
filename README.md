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
- **[Public APIs](https://github.com/public-apis/public-apis)** — GitHub 330K+ Stars，收录 1500+ 个免费公开 API 的集体索引清单，覆盖天气、金融、AI、游戏、健康、新闻、交通等 50+ 类别。每个 API 标注了认证方式（apiKey / OAuth / 无需认证）、CORS 支持、HTTPS 支持等关键信息。开发者做项目时为后端找数据源的首选参考，跟程序员接私活一起养活了一整个生态。
- **[freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp)** — GitHub 420K+ Stars，全球最大的开源编程学习社区。全免费、自定进度的交互式课程，含 2000+ 小时的项目驱动练习，覆盖 HTML/CSS/JavaScript/Python/数据科学/机器学习/关系型数据库等。社区论坛 + 技术文章 + YouTube 频道全生态覆盖，已帮助数万人从零成为专业开发者并找到第一份技术工作。真正的「免费」编程教育。
- **[SimUtil](https://github.com/dungngminh/simutil)** — 终端 TUI 移动端模拟器管理工具，Dart + Nocterm 构建。并列列出本机所有 iOS Simulators 和 Android AVD，回车一键启动（安卓支持冷启动、禁音频等参数），也可关闭设备、看 logcat。内置无线 ADB 连接、6 位码配对及二维码配对。macOS / Linux / Windows 全平台，Homebrew 和 PowerShell 一键安装。终端党无需再为开个模拟器而启动 Android Studio / Xcode。

## 效率工具

> 让日常工作更高效、更专注。

- **[Meetily](https://github.com/Zackriya-Solutions/meetily)** — 隐私优先的本地会议助手，GitHub 12K+ Stars。录音、转写、总结全部跑在本地，不上传任何服务器。Whisper + NVIDIA Parakeet 实时转写，macOS / Windows / Linux 三端 GPU 加速，总结环节可接 Ollama 本地模型或 Claude、Groq 等云端 API。涉及客户、合同、薪资等敏感会议的首选。
- **[MarkerOn](https://github.com/ifer47/markeron)** — 轻量级屏幕标注工具，仅 1.5 MB。基于 Tauri v2 + Vue 3 构建，非 Electron 套壳，原生性能。热键一键进入标注模式，支持画笔、荧光笔、激光笔、箭头、矩形、椭圆、线条、橡皮擦、文字等全套工具，可在桌面任意内容上标注同时穿透点击底层应用。含白板模式、纯键盘操控、跨会话保存标注。演示、教学、录屏、会议场景的利器。
- **[Superdoc](https://github.com/superdoc-dev/superdoc)** — 开源实时协作文档编辑器，Notion 与 OnlyOffice 的轻量融合体。块级编辑、实时光标同步、评论、历史版本，整个编辑器核心开源。可嵌入 SaaS 产品、知识库系统或团队管理后台，数据完全私有化部署。适合需要在线文档功能又不想被大厂绑定的场景：企业 SOP 文档库、在线教育讲义协作、小型团队 Wiki、低代码平台富文本模块。

## 前端开发

*等待收录...*

## 后端开发

> 后端框架、基础设施、中间件等。

- **[SafeLine](https://github.com/chaitin/SafeLine)** — 长亭科技出品的自建 WAF（Web 应用防火墙），GitHub 15K+ Stars。基于语义分析引擎检测 SQL 注入、XSS、命令注入等攻击，社区版免费。反向代理部署，支持 Docker 一键安装，自带 Web 管理面板，实时攻击日志与告警。

## 设计 & 创意

- **[Kami](https://github.com/tw93/Kami)** — 轻量约束语言 + 十套模板，让 AI 生成「拿得出手」的 PDF。暖色调羊皮纸底、墨水蓝单色强调、统一衬线排版，解决 AI 生成文档版式漂移、千篇一律灰扑扑的问题。含一页简报、长文、信件、简历、幻灯片、股权报告、变更日志、落地页等中英双语模板。支持品牌配置文件（`~/.config/kami/brand.md`）持久化名字、色调、语言偏好；Claude Code 插件市场直接装 Skill ZIP 即可让 Agent 自动触发。适合常让 AI 写研报、提案、技术分享并想要认真排版的人。

## 其他

> 跨领域、跨品类的实用工具。

- **[Spotube](https://github.com/KRTirtho/spotube)** — 开源跨平台音乐播放器，GitHub 46K+ Stars。基于 Flutter 构建，非 Electron 套壳，原生性能。使用 YouTube / Piped / Invidious 等公开音源，不依赖 Spotify API，无需账号即可免费串流。隐私优先（零遥测）、时间同步歌词、局域网远程控制、Discord Rich Presence、Last.fm / ListenBrainz 记录。macOS / Windows / Linux / Android / iOS 全平台可跑。
- **[Streambert](https://github.com/truelockmc/streambert)** — Electron 跨平台影视流媒体桌面应用，口号「能看和下载全球几乎任何电影、剧集或番剧」。零广告、零追踪，从 VidSrc 拉取视频流，信息走 TMDB，动漫自动切 AniList + AllManga.to。支持边看边下（多线程下载，速度比浏览器快）、库管理、字幕下载、流行趋势推荐。首次启动需免费申请 TMDB API 读取令牌。

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
