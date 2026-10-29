# GitHub 涨星项目周报

创建日期：2026-10-29（北京时间，Asia/Shanghai）  
更新安排：每周四 20:00（北京时间），按日期追加一期，保留历史记录。  
每期数量：8 个项目；首期前 5 个保留自最初的项目总结，另补充第 6—8 名。

## 统计与记录规则

- “涨星最高”按新增 Star 的绝对数量降序排列，不按累计 Star 或增长百分比排列。
- 默认采用发布当日之前近 7 天的窗口，不等同于本周一至今。每期明确数据日期、实际窗口、来源和覆盖范围。
- 同一期优先使用同一来源、同一采样时点的数据。GitHub Trending 的展示顺序不能直接当作新增 Star 排名。
- 第三方数据只代表其追踪范围。快照不足完整 7 天时必须注明，不据此宣称 GitHub 全站完整排名。
- 数据保留来源的精度：“约”与 K 单位转写不代表获得了精确数值。仓库当前总 Star 可能与榜单历史快照不同。
- 每期包含排名、仓库链接、周新增 Star、累计 Star、用途、技术或语言、许可证、适用人群、使用条件和资料来源。
- 不猜测未经验证的增长原因；来源无法访问或不足 8 个可核验项目时，如实记录缺失，不编造补齐。
- 新一期追加到文件末尾。同日已有完整一期时跳过重复写入；若作更正，标明更正日期与原因，保留可追溯记录。

## 2026-10-29｜第 1 期

### 数据口径

采用 [GitHub Hot Board 周榜历史快照](https://github-hot-board.vercel.app/en/history/weekly)，页面标注日期为 2026-10-29、快照时间为 05:43（页面未明确时区，保留原值）。该站在近 7 天窗口内，用每个仓库最早与最新的已采集快照计算增长；各仓库实际观测跨度可能不足完整 7 天。

本期是该站追踪范围内的前 8 名，不能据此认定为 GitHub 全站完整前 8 名。该来源与其他站点、GitHub Trending 的计数可能不同，未混用其增量数据。

### 排名总览

| 排名 | 项目 | 窗口内新增 Star | 累计 Star（同份快照） | 用途 |
| --- | --- | ---: | ---: | --- |
| 1 | [morluto/rea](https://github.com/morluto/rea) | 约 30,700 | 约 403,700 | AI 辅助软件分析与逆向工程 |
| 2 | [debpalash/VoiceStudio](https://github.com/debpalash/VoiceStudio) | 约 10,000 | 约 93,300 | 本地 AI 语音工作室 |
| 3 | [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | 9,850 | 约 51,900 | 编程智能体安全审计流程 |
| 4 | [Gathin23/cleanyourtv](https://github.com/Gathin23/cleanyourtv) | 9,834 | 约 37,600 | 精简 Android TV / Google TV 服务与桌面 |
| 5 | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 7,782 | 约 93,300 | AI 生成界面的设计指导与审查 |
| 6 | [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) | 5,688 | 约 265,100 | 以插件扩展的 AI 智能体运行框架 |
| 7 | [Zagitta/gpu-unlock](https://github.com/Zagitta/gpu-unlock) | 5,618 | 8,486 | 调整受支持 GeForce 显卡的 AI 张量计算限制 |
| 8 | [stablyai/orca](https://github.com/stablyai/orca) | 5,513 | 约 109,300 | 管理多个编程智能体的开发环境 |

排名与全部 Star 数据来源：[2026-10-29 周榜快照](https://github-hot-board.vercel.app/en/history/weekly)。

### 1. REA — morluto/rea

- **维护者**：morluto。
- **技术与许可**：TypeScript；MIT。
- **项目用途**：把 AI 智能体连接到软件分析工具，理解现有应用和程序如何运行。
- **具体能力**：检查原生二进制、JavaScript、Electron 应用、.NET 程序集及网站；可通过 MCP 与命令行使用；本地执行分析，结果附带证据与局限。
- **适合人群**：逆向工程、安全研究、兼容性分析人员，以及需要理解现有软件功能的开发者。
- **使用条件**：按目标配置相应分析引擎；部分能力依赖 Ghidra 等外部工具，安装要求以官方文档为准。
- **本期数据**：新增约 30,700 Star；累计约 403,700 Star。
- **资料来源**：[官方仓库及 README](https://github.com/morluto/rea)、[安装文档](https://github.com/morluto/rea/blob/main/docs/installation.md)。

### 2. VoiceStudio — debpalash/VoiceStudio

- **维护者**：debpalash。
- **技术与许可**：以 Python 为主；仓库标注 AGPL-3.0，使用的模型应另查其各自许可。
- **项目用途**：在自己的设备上完成 AI 语音制作。
- **具体能力**：语音克隆、用文字描述生成声音、视频翻译配音、听写、转录、有声书制作；选择并下载需要的本地模型。
- **运行环境**：提供 Windows、macOS、Linux 及 Docker 方案；CPU 可运行，处理速度通常慢于适配的 GPU。项目还提供移动端方案，成熟度按平台说明查看。
- **适合人群**：视频创作者、播客、有声书制作人员及需要本地处理音频的用户。
- **使用条件**：效果和资源需求随模型、语言、硬件而变化。项目宣称覆盖 646 种语言，不表示每种语言效果一致。
- **本期数据**：新增约 10,000 Star；累计约 93,300 Star。
- **资料来源**：[官方仓库、平台说明与下载入口](https://github.com/debpalash/VoiceStudio)。

### 3. Security Audit Skill — cloudflare/security-audit-skill

- **维护方**：Cloudflare。
- **技术与许可**：JavaScript；MIT。
- **项目用途**：为编程智能体提供结构化、可复核的安全审计工作流。
- **具体能力**：架构与信任边界梳理、覆盖范围驱动的漏洞搜寻、候选问题验证、结构化输出、独立记录复核和报告生成。
- **主要特点**：候选发现交给新的验证智能体尝试推翻，并记录已检查范围与覆盖缺口。
- **适合人群**：安全工程师、代码审计人员及需要在开发流程中加入安全检查的团队。
- **使用条件**：需要可运行该 Skill 的智能体环境；报告是审计辅助证据，具体发现仍需结合代码与运行环境复核。
- **本期数据**：新增 9,850 Star；累计约 51,900 Star。
- **资料来源**：[官方仓库、审计阶段与安装说明](https://github.com/cloudflare/security-audit-skill)。

### 4. CleanYourTV — Gathin23/cleanyourtv

- **维护者**：Gathin23。
- **技术与许可**：通过网络 ADB 调用 Android 工具；含 Python 工具与原生桌面组件；MIT。Outfit 字体另遵循 SIL Open Font License。
- **项目用途**：精简 Android TV / Google TV 的预装服务并更换简洁桌面。
- **具体能力**：备份应用列表与设置，停用部分遥测、广告服务及预装应用，安装原生启动器；提供恢复流程。
- **主要特点**：不要求 root，主要通过停用而非卸载实现变更。
- **适合人群**：希望改善电视桌面与预装软件体验、能够按机型说明操作的用户。
- **使用条件**：电视须支持并授权调试连接；停用清单与设备有关，部分清单涉及系统更新服务，操作完成后按说明关闭调试。
- **本期数据**：新增 9,834 Star；累计约 37,600 Star。
- **资料来源**：[官方仓库](https://github.com/Gathin23/cleanyourtv)、[中文使用说明](https://github.com/Gathin23/cleanyourtv/blob/main/README.zh-CN.md)。

### 5. Impeccable — pbakaus/impeccable

- **作者**：Paul Bakaus。
- **技术与许可**：包含 Rust 引擎及智能体 Skill；Apache-2.0。
- **项目用途**：改善 AI 编程工具生成界面的视觉设计与交互质量。
- **具体能力**：指导字体层级、布局间距、配色、动画和交互反馈；`critique` 用于 UX 评审，`audit` 用于技术质量报告，`polish` 等命令用于定向改进。
- **适配工具**：支持 Claude Code、Cursor、Codex CLI、GitHub Copilot 等多种编程智能体，具体支持范围以当前文档为准。
- **适合人群**：使用 AI 开发网页、前端界面及产品原型的开发者。
- **使用条件**：安装到相应智能体环境并给出具体目标；结果依赖使用的模型、现有代码与上下文。
- **本期数据**：新增 7,782 Star；累计约 93,300 Star。
- **资料来源**：[官方仓库、命令与安装说明](https://github.com/pbakaus/impeccable)。

### 6. DeepSeek Harness — deepseek-ai/deepseek-harness

- **维护方**：deepseek-ai。
- **技术与许可**：TypeScript 为主要技术之一；MIT。
- **项目用途**：以“Everything is a Plugin”为设计方向的 AI 智能体运行框架。
- **具体能力**：通过插件扩展智能体的工具与工作流；项目能够执行模型生成的代码和命令，并加载第三方插件。
- **适合人群**：希望自定义智能体环境、开发插件或研究智能体运行框架的开发者。
- **使用条件**：官方将其标为实验性开发者预览软件；实际插件能力应逐项查证，不将社区插件描述当作框架内置能力。
- **本期数据**：新增 5,688 Star；累计约 265,100 Star。
- **资料来源**：[官方仓库](https://github.com/deepseek-ai/deepseek-harness)、[官方状态与使用说明](https://github.com/deepseek-ai/deepseek-harness/blob/master/SAFETY.md)。

### 7. GPU Unlock — Zagitta/gpu-unlock

- **维护者**：Zagitta。
- **技术与许可**：C / Linux 内核模块及固件相关内容；已查到内核模块声明 GPL，固件等组件有单独许可资料，不能将整个仓库简化为单一许可。
- **项目用途**：项目宣称可在受支持的 GeForce RTX 20/30/40 系列上解除部分张量计算吞吐限制。
- **具体能力**：在 NVIDIA 驱动加载前处理限制；README 声称最高可获得 2 倍 FP16 / BF16 / TF32 张量吞吐。这是项目方声明，不是本周报的独立实测。
- **适合人群**：了解 Linux、GPU 驱动和硬件兼容性的 AI 计算用户及研究人员。
- **使用条件**：支持范围因显卡架构而异；README 将部分系列标为实验性，并注明 RTX 50 系列不支持。性能收益不能直接等同于完整应用速度翻倍。
- **本期数据**：新增 5,618 Star；累计 8,486 Star。这里保留榜单历史快照值，未替换成仓库访问时的实时总数。
- **资料来源**：[官方仓库、支持列表与性能声明](https://github.com/Zagitta/gpu-unlock)、[内核模块许可声明](https://github.com/Zagitta/gpu-unlock/blob/main/kernel/gpu_unlock/main.c)。

### 8. Orca — stablyai/orca

- **维护方**：stablyai。
- **技术与许可**：TypeScript；MIT。
- **项目用途**：在同一个开发环境中管理多个编程智能体。
- **具体能力**：使用自己的订阅运行不同编程智能体，提供桌面、移动端和远程运行方式；仓库涵盖终端、工作树与智能体编排等能力。
- **适合人群**：同时推进多个开发任务，或需要跨设备管理编程智能体的开发者与团队。
- **使用条件**：需要相应智能体账户、订阅或配置；不同运行方式的可用功能按官方文档确认。
- **本期数据**：新增 5,513 Star；累计约 109,300 Star。
- **资料来源**：[官方仓库与 README](https://github.com/stablyai/orca)。

### 本期观察

这 8 个项目中，多项围绕 AI 智能体的分析、审计、设计与开发工作流；另有本地语音制作、电视系统精简和 GPU 计算工具。该分类来自项目功能描述，不代表已验证它们的涨星原因。

<!-- 后续周报按日期追加到此处；保留历史期次。 -->


<!-- weekly-report:2026-10-29:start -->
## 2026-10-29｜云端周报 Top 8

生成时间：2026-10-29T20:38:34+08:00（北京时间）  
榜单抓取时间：2026-10-29T20:38:36+08:00  
模式：基础版（未调用 AI）  
候选范围：本次 GitHub Trending / This week 页面解析到的 11 个项目。

按页面标注的周新增 Star 降序取前 8；来源：[GitHub 官方周榜](https://github.com/trending?since=weekly)。
This week 使用来源站点自己的滚动周口径，页面未提供精确起止时刻；不自行假定为周一至今。
本期是周榜候选范围内排名，不是 GitHub 全站全部仓库的增长排名。
周增量来自榜单；累计 Star、语言和许可证等来自随后读取的仓库 API，采样时点不同。
许可证为 GitHub 自动识别结果，多组件或模型的许可应另查原文件。

| 排名 | 项目 | 周新增 Star | 当前累计 Star | 主要语言 | 许可证 |
| --- | --- | ---: | ---: | --- | --- |
| 1 | [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | 16,002 | 52,301 | JavaScript | MIT |
| 2 | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 7,283 | 94,254 | Rust | Apache-2.0 |
| 3 | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | 5,322 | 118,135 | Python | Apache-2.0 |
| 4 | [obra/superpowers](https://github.com/obra/superpowers) | 4,655 | 307,950 | Shell | MIT |
| 5 | [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) | 4,293 | 226,212 | 未标注 | 未确认（需阅读 LICENSE） |
| 6 | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 3,940 | 105,082 | JavaScript | MIT |
| 7 | [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | 3,516 | 23,722 | Python | MIT |
| 8 | [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | 2,612 | 33,760 | Python | Apache-2.0 |

### 1. cloudflare/security-audit-skill

- 维护方：cloudflare
- 官方简介：A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings
- 主要语言 / 许可：JavaScript / MIT
- 周新增 Star：16,002；当前累计 Star：52,301
- Fork：3,347；最近推送时间（UTC）：2026-09-14T19:29:02Z
- 官方资料：[cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)（含 README）
- 中文分析：本期未启用 AI；以上为官方元数据，具体使用条件请查 README。

### 2. pbakaus/impeccable

- 维护方：pbakaus
- 官方简介：The design vocabulary for your coding agent. Steer with polish and bolder, review with critique and audit, catch AI slop before it ships.
- 主要语言 / 许可：Rust / Apache-2.0
- 周新增 Star：7,283；当前累计 Star：94,254
- Fork：5,567；最近推送时间（UTC）：2026-10-29T04:51:37Z
- 官方资料：[pbakaus/impeccable](https://github.com/pbakaus/impeccable)（含 README）
- 中文分析：本期未启用 AI；以上为官方元数据，具体使用条件请查 README。

### 3. TauricResearch/TradingAgents

- 维护方：TauricResearch
- 官方简介：TradingAgents: Multi-Agents LLM Financial Trading Framework
- 主要语言 / 许可：Python / Apache-2.0
- 周新增 Star：5,322；当前累计 Star：118,135
- Fork：22,593；最近推送时间（UTC）：2026-10-27T08:43:04Z
- 官方资料：[TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)（含 README）
- 中文分析：本期未启用 AI；以上为官方元数据，具体使用条件请查 README。

### 4. obra/superpowers

- 维护方：obra
- 官方简介：An agentic skills framework &amp; software development methodology that works.
- 主要语言 / 许可：Shell / MIT
- 周新增 Star：4,655；当前累计 Star：307,950
- Fork：27,388；最近推送时间（UTC）：2026-10-23T03:48:57Z
- 官方资料：[obra/superpowers](https://github.com/obra/superpowers)（含 README）
- 中文分析：本期未启用 AI；以上为官方元数据，具体使用条件请查 README。

### 5. multica-ai/andrej-karpathy-skills

- 维护方：multica-ai
- 官方简介：A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.
- 主要语言 / 许可：未标注 / 未确认（需阅读 LICENSE）
- 周新增 Star：4,293；当前累计 Star：226,212
- Fork：22,591；最近推送时间（UTC）：2026-04-20T10:05:04Z
- 官方资料：[multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)（含 README）
- 中文分析：本期未启用 AI；以上为官方元数据，具体使用条件请查 README。

### 6. Leonxlnx/taste-skill

- 维护方：Leonxlnx
- 官方简介：Agent skills that give coding agents taste: art direction, reference images and a browser check instead of generic AI pages
- 主要语言 / 许可：JavaScript / MIT
- 周新增 Star：3,940；当前累计 Star：105,082
- Fork：7,107；最近推送时间（UTC）：2026-10-29T08:49:32Z
- 官方资料：[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)（含 README）
- 中文分析：本期未启用 AI；以上为官方元数据，具体使用条件请查 README。

### 7. AgriciDaniel/claude-seo

- 维护方：AgriciDaniel
- 官方简介：Universal SEO skill for Claude Code. 26 sub-skills + 19 sub-agents covering technical SEO, E-E-A-T, schema, GEO/AEO, agent readiness (Lighthouse Agentic Browsing, WebMCP, llms.txt), backlinks, local SEO, e-commerce, international SEO, Google APIs, and PDF/Excel reporting. 9 optional extensions for live SEO data.
- 主要语言 / 许可：Python / MIT
- 周新增 Star：3,516；当前累计 Star：23,722
- Fork：3,186；最近推送时间（UTC）：2026-10-22T16:47:40Z
- 官方资料：[AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo)（含 README）
- 中文分析：本期未启用 AI；以上为官方元数据，具体使用条件请查 README。

### 8. anthropics/knowledge-work-plugins

- 维护方：anthropics
- 官方简介：Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork
- 主要语言 / 许可：Python / Apache-2.0
- 周新增 Star：2,612；当前累计 Star：33,760
- Fork：3,713；最近推送时间（UTC）：2026-10-29T07:28:50Z
- 官方资料：[anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)（含 README）
- 中文分析：本期未启用 AI；以上为官方元数据，具体使用条件请查 README。

本期未调用付费模型接口，也未对项目进行安装或功能测试。

<!-- weekly-report:2026-10-29:end -->
