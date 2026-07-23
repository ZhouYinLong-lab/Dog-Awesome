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
- **[Awesome LLM Apps](https://github.com/Shubhamsaboo/awesome-llm-apps)** — GitHub 124K+ Stars，精选 100+ 个可运行的 AI Agent / RAG / LLM 应用模板库。涵盖多智能体协作、语音 Agent、MCP 集成、生成式 UI、游戏 Agent 等场景，clone 即可运行。支持 OpenAI Agents SDK、Google ADK、CrewAI、LangGraph、Claude、Gemini 等主流框架，也提供 Agent Skills 一键安装到编码助手。从原型到可交付应用只需 30 秒，Apache-2.0 协议。

## AI & 机器学习

- **[Supervision](https://github.com/roboflow/supervision)** — 计算机视觉通用工具集。封装检测、追踪、标注、可视化等一整套 CV 常用功能，省去重复造轮子。做 CV 项目的基础设施级工具库。
- **[BiRefNet](https://github.com/ZhengPeng7/BiRefNet)** — 高精度图像抠图深度学习模型。双向参考机制同时利用高层语义和底层细节信息，发丝、半透明物体等复杂边缘处理自然。提供预训练模型和推理代码，支持在 COCO 等公开数据集上微调。适用场景：电商自动去背景、视频会议虚拟背景预处理、影视后期素材提取、证件照自动换底。
- **[Bisheng](https://github.com/dataelement/bisheng)** — GitHub 11.5K+ Stars，企业级 LLM 应用 DevOps 平台，名出毕昇活字印刷。核心三件套：**Lingsight Agent**（AGL 框架将领域知识嵌入 Agent 决策链）、**Bisheng Workflow**（可视化编排，支持循环/并行/批处理/条件逻辑，执行中可人机干预）、**高精度文档解析**（印刷/手写 OCR、表格识别、版式分析、印章检测）。覆盖 RAG → Agent → SFT 全流程，内置 RBAC/SSO/LDAP 企业级管控。Docker 一键部署，已服务多家世界 500 强，Apache-2.0 协议。
- **[Awesome LLM Resources](https://github.com/WangRongsheng/awesome-LLM-resources)** — 大语言模型资源全收录：论文、开源模型、训练框架、推理优化、评估基准、Prompt 工程、RAG、Agent、安全对齐等 20+ 子领域。含中文 LLM 专项（ChatGLM、Qwen、DeepSeek 等国产模型生态）和实践教程，适合 LLM 研究者与工程师的系统性学习地图。

## 开发工具

> 提升开发效率、改善代码质量的开源工具。

- **[Codebase-Memory-MCP](https://github.com/DeusData/codebase-memory-mcp)** — 将整个代码库索引为持久化知识图谱的 MCP 工具。亚毫秒级查询，号称比传统方式省 99% token。多仓库切换时不再需要反复喂代码上下文，对做 RAG 和代码智能的工具开发者尤为值得关注。
- **[lat.md](https://github.com/1st1/lat.md)** — 为代码库建立 Markdown 知识图谱。通过 `lat.md/` 文件夹存放架构、业务逻辑、测试规范等互链的 markdown 文件，配合 CLI（`init` / `check` / `locate` / `search`）让 Agent 用语义搜索替代无穷尽的 grep。项目大到 Agent 经常找不到关键约束时，最值得一试的方案。
- **[OfficeCLI](https://github.com/iOfficeAI/OfficeCLI)** — AI 原生 Office 文档命令行工具，GitHub 8K+ Stars。零依赖单二进制文件，直接操作 Word/Excel/PPT，无需安装 Office 或 .NET 运行时。内置 MCP Server，一条命令 `officecli mcp claude` 即可注册到 Claude Code，让 AI Agent 直接创建、读取、修改 Office 文档。三层架构（JSON 读取 → DOM 路径寻址 → 原始 XML/XPath 回退），支持模板变量 `{{placeholder}}`、批量生成、实时预览（`officecli watch` 启动本地 Web 服务）。macOS / Windows / Linux 全平台可用。
- **[Public APIs](https://github.com/public-apis/public-apis)** — GitHub 330K+ Stars，收录 1500+ 个免费公开 API 的集体索引清单，覆盖天气、金融、AI、游戏、健康、新闻、交通等 50+ 类别。每个 API 标注了认证方式（apiKey / OAuth / 无需认证）、CORS 支持、HTTPS 支持等关键信息。开发者做项目时为后端找数据源的首选参考，跟程序员接私活一起养活了一整个生态。
- **[freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp)** — GitHub 420K+ Stars，全球最大的开源编程学习社区。全免费、自定进度的交互式课程，含 2000+ 小时的项目驱动练习，覆盖 HTML/CSS/JavaScript/Python/数据科学/机器学习/关系型数据库等。社区论坛 + 技术文章 + YouTube 频道全生态覆盖，已帮助数万人从零成为专业开发者并找到第一份技术工作。真正的「免费」编程教育。
- **[SimUtil](https://github.com/dungngminh/simutil)** — 终端 TUI 移动端模拟器管理工具，Dart + Nocterm 构建。并列列出本机所有 iOS Simulators 和 Android AVD，回车一键启动（安卓支持冷启动、禁音频等参数），也可关闭设备、看 logcat。内置无线 ADB 连接、6 位码配对及二维码配对。macOS / Linux / Windows 全平台，Homebrew 和 PowerShell 一键安装。终端党无需再为开个模拟器而启动 Android Studio / Xcode。
- **[Build Your Own X](https://github.com/codecrafters-io/build-your-own-x)** — GitHub 340K+ Stars，手把手教你从零构建 Git、Docker、Redis、数据库、Shell 等经典技术的教程合集。涵盖 3D 渲染器、区块链、编程语言、游戏引擎、操作系统、神经网络等 30+ 领域，每个项目都有清晰的教程链接。最硬核的「造轮子」学习地图，适合想深入理解底层原理的开发者。
- **[Project Based Learning](https://github.com/practical-tutorials/project-based-learning)** — GitHub 275K+ Stars，编程实战教程合集。按语言分类（C/C++/Python/Go/JavaScript/Rust 等），涵盖 Web 应用、游戏、编译器、操作系统、机器学习等领域的从零构建教程。每个教程都带你完整做出一个可运行的项目，与 Build Your Own X 互补：前者偏「造轮子理解原理」，这里偏「做项目积累经验」。
- **[Every Programmer Should Know](https://github.com/mtdvio/every-programmer-should-know)** — GitHub 100K+ Stars，每个软件开发者都该知道的技术知识图谱。涵盖算法、数据结构、安全、分布式系统、系统架构、职业建议、编码练习平台等主题，以书籍/文章/视频/交互工具的形式组织。高度观点化的精选列表，还包含平台工程和心理健康等新兴话题，适合用来检查自己的知识盲区。
- **[Awesome Courses](https://github.com/prakhar1989/awesome-courses)** — GitHub 70K+ Stars，全球顶尖大学计算机科学课程清单。收录 MIT、Stanford、CMU、Berkeley 等名校的公开课程，涵盖算法、操作系统、数据库、网络、编译原理、机器学习、安全等 CS 核心领域。大部分课程有免费视频、讲义和编程作业，适合系统性补强计算机基础。

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
- **[Fastify](https://github.com/fastify/fastify)** — Node.js 高性能 Web 框架，GitHub 33K+ Stars。插件式架构 + JSON Schema 序列化，请求吞吐量远超 Express。内置 Logger、输入校验、Hooks 生命周期，TypeScript 一等支持，生态丰富（官方插件覆盖 Cookie、CORS、JWT、Rate Limiting、WebSocket 等）。适合微服务、高并发 API 网关、实时数据管道等对性能有极致要求的后端场景。

## 设计 & 创意

- **[Kami](https://github.com/tw93/Kami)** — 轻量约束语言 + 十套模板，让 AI 生成「拿得出手」的 PDF。暖色调羊皮纸底、墨水蓝单色强调、统一衬线排版，解决 AI 生成文档版式漂移、千篇一律灰扑扑的问题。含一页简报、长文、信件、简历、幻灯片、股权报告、变更日志、落地页等中英双语模板。支持品牌配置文件（`~/.config/kami/brand.md`）持久化名字、色调、语言偏好；Claude Code 插件市场直接装 Skill ZIP 即可让 Agent 自动触发。适合常让 AI 写研报、提案、技术分享并想要认真排版的人。
- **[Awesome Web Design](https://github.com/nicolesaidy/awesome-web-design)** — 数字设计师资源大全。覆盖博客/资讯、灵感网站、配色工具、字体搭配、图标库、图片素材、设计规范、原型工具、教程书籍、生产力工具和 Slack 社区等分类。从 Sketch/Figma 到 Dribbble/Behance 再到 Google Fonts，设计师常用工具与服务一站导航。

## 其他

> 跨领域、跨品类的实用工具。

- **[Spotube](https://github.com/KRTirtho/spotube)** — 开源跨平台音乐播放器，GitHub 46K+ Stars。基于 Flutter 构建，非 Electron 套壳，原生性能。使用 YouTube / Piped / Invidious 等公开音源，不依赖 Spotify API，无需账号即可免费串流。隐私优先（零遥测）、时间同步歌词、局域网远程控制、Discord Rich Presence、Last.fm / ListenBrainz 记录。macOS / Windows / Linux / Android / iOS 全平台可跑。
- **[Streambert](https://github.com/truelockmc/streambert)** — Electron 跨平台影视流媒体桌面应用，口号「能看和下载全球几乎任何电影、剧集或番剧」。零广告、零追踪，从 VidSrc 拉取视频流，信息走 TMDB，动漫自动切 AniList + AllManga.to。支持边看边下（多线程下载，速度比浏览器快）、库管理、字幕下载、流行趋势推荐。首次启动需免费申请 TMDB API 读取令牌。
- **[Codex Dream Skin](https://github.com/Fei-Away/Codex-Dream-Skin)** — Codex 桌面端换肤工具，GitHub 9.2K Stars。通过 localhost CDP 注入实现主题定制，不改动官方 app.asar 或 WindowsApps。在原生 UI 元素（侧边栏、卡片、输入框）背后渲染真实背景层，支持 16:9 自定义背景图（2560×1440），自动焦点与色彩适配。macOS 菜单栏 / Windows 系统托盘一键切换、保存、恢复主题，内置多套预设皮肤。非 OpenAI 官方产品。

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
