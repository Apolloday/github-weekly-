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

生成时间：2026-10-29T20:57:23+08:00（北京时间）  
榜单抓取时间：2026-10-29T20:57:25+08:00  
模式：DeepSeek / deepseek-flash 中文总结（根据官方简介及 README 节选）  
候选范围：本次 GitHub Trending / This week 页面解析到的 11 个项目。

按页面标注的周新增 Star 降序取前 8；来源：[GitHub 官方周榜](https://github.com/trending?since=weekly)。
This week 使用来源站点自己的滚动周口径，页面未提供精确起止时刻；不自行假定为周一至今。
本期是周榜候选范围内排名，不是 GitHub 全站全部仓库的增长排名。
周增量来自榜单；累计 Star、语言和许可证等来自随后读取的仓库 API，采样时点不同。
许可证为 GitHub 自动识别结果，多组件或模型的许可应另查原文件。

| 排名 | 项目 | 周新增 Star | 当前累计 Star | 主要语言 | 许可证 |
| --- | --- | ---: | ---: | --- | --- |
| 1 | [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | 16,002 | 52,321 | JavaScript | MIT |
| 2 | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 7,283 | 94,290 | Rust | Apache-2.0 |
| 3 | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | 5,322 | 118,140 | Python | Apache-2.0 |
| 4 | [obra/superpowers](https://github.com/obra/superpowers) | 4,655 | 307,969 | Shell | MIT |
| 5 | [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) | 4,293 | 226,223 | 未标注 | 未确认（需阅读 LICENSE） |
| 6 | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 3,940 | 105,095 | JavaScript | MIT |
| 7 | [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) | 3,516 | 23,730 | Python | MIT |
| 8 | [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins) | 2,612 | 33,762 | Python | Apache-2.0 |

### 1. cloudflare/security-audit-skill

- 维护方：cloudflare
- 官方简介：A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings
- 主要语言 / 许可：JavaScript / MIT
- 周新增 Star：16,002；当前累计 Star：52,321
- Fork：3,347；最近推送时间（UTC）：2026-09-14T19:29:02Z
- 官方资料：[cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)（含 README）
- 中文用途与功能（AI）：面向编码代理的安全审计技能，分六阶段编排侦察、覆盖驱动的漏洞狩猎、候选验证、结构化输出、独立记录核验与报告生成，产出可机读的findings.json及配套校验脚本。
- 适用人群（AI）：使用编码代理开展代码安全审计的安全工程师与开发者
- 使用条件或局限（AI）：需通过Skills CLI安装；效果取决于代理与目标代码，资料未提供性能保证。

### 2. pbakaus/impeccable

- 维护方：pbakaus
- 官方简介：The design vocabulary for your coding agent. Steer with polish and bolder, review with critique and audit, catch AI slop before it ships.
- 主要语言 / 许可：Rust / Apache-2.0
- 周新增 Star：7,283；当前累计 Star：94,290
- Fork：5,570；最近推送时间（UTC）：2026-10-29T04:51:37Z
- 官方资料：[pbakaus/impeccable](https://github.com/pbakaus/impeccable)（含 README）
- 中文用途与功能（AI）：为编码代理提供设计词汇与命令集，可用polish、bolder等指令调整界面，用critique和audit做评审，并以确定性规则检测常见AI生成设计套路。
- 适用人群（AI）：希望提升网页与组件设计质量的开发者和设计师
- 使用条件或局限（AI）：需在项目根目录安装并初始化生成PRODUCT.md；主要面向已有界面迭代。

### 3. TauricResearch/TradingAgents

- 维护方：TauricResearch
- 官方简介：TradingAgents: Multi-Agents LLM Financial Trading Framework
- 主要语言 / 许可：Python / Apache-2.0
- 周新增 Star：5,322；当前累计 Star：118,140
- Fork：22,592；最近推送时间（UTC）：2026-10-27T08:43:04Z
- 官方资料：[TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents)（含 README）
- 中文用途与功能（AI）：多智能体LLM金融交易研究框架，由分析师、研究员、交易员等角色协作完成行情分析、决策与回测，支持多种模型供应商与数据源，并注重时点数据完整性。
- 适用人群（AI）：研究LLM金融分析与多智能体协作的研究者和开发者
- 使用条件或局限（AI）：需配置模型与数据供应商密钥；资料未说明投资表现或收益保证。

### 4. obra/superpowers

- 维护方：obra
- 官方简介：An agentic skills framework &amp; software development methodology that works.
- 主要语言 / 许可：Shell / MIT
- 周新增 Star：4,655；当前累计 Star：307,969
- Fork：27,390；最近推送时间（UTC）：2026-10-23T03:48:57Z
- 官方资料：[obra/superpowers](https://github.com/obra/superpowers)（含 README）
- 中文用途与功能（AI）：基于可组合技能的软件开发方法论框架，引导代理先澄清需求、形成设计与实施计划，再以子代理驱动开发并强调TDD、YAGNI与DRY，可自动触发技能。
- 适用人群（AI）：使用Claude Code、Codex、Cursor等编码代理的开发者
- 使用条件或局限（AI）：不同代理需分别安装；涉及商业支持需联系其销售渠道。

### 5. multica-ai/andrej-karpathy-skills

- 维护方：multica-ai
- 官方简介：A single CLAUDE.md file to improve Claude Code behavior, derived from Andrej Karpathy's observations on LLM coding pitfalls.
- 主要语言 / 许可：未标注 / 未确认（需阅读 LICENSE）
- 周新增 Star：4,293；当前累计 Star：226,223
- Fork：22,591；最近推送时间（UTC）：2026-04-20T10:05:04Z
- 官方资料：[multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills)（含 README）
- 中文用途与功能（AI）：一份CLAUDE.md指南，基于Karpathy对LLM编码问题的观察，提出先思考后编码、简洁优先、外科式修改和目标驱动执行四条原则，约束Claude Code行为。
- 适用人群（AI）：使用Claude Code或Cursor并希望规范代理行为的开发者
- 使用条件或局限（AI）：为提示词指南而非代码工具；实际效果取决于模型对指令的遵循程度。

### 6. Leonxlnx/taste-skill

- 维护方：Leonxlnx
- 官方简介：Agent skills that give coding agents taste: art direction, reference images and a browser check instead of generic AI pages
- 主要语言 / 许可：JavaScript / MIT
- 周新增 Star：3,940；当前累计 Star：105,095
- Fork：7,107；最近推送时间（UTC）：2026-10-29T08:49:32Z
- 官方资料：[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)（含 README）
- 中文用途与功能（AI）：让编码代理具备设计品味的技能，为生成网页和应用界面提供艺术指导、真实图片来源，并可在真实浏览器中检查自身产出，避免通用化AI页面。
- 适用人群（AI）：希望代理产出更有设计感界面的前端开发者与设计工程师
- 使用条件或局限（AI）：需Node 22+及已安装Chrome、Edge或Chromium；找图需联网。

### 7. AgriciDaniel/claude-seo

- 维护方：AgriciDaniel
- 官方简介：Universal SEO skill for Claude Code. 26 sub-skills + 19 sub-agents covering technical SEO, E-E-A-T, schema, GEO/AEO, agent readiness (Lighthouse Agentic Browsing, WebMCP, llms.txt), backlinks, local SEO, e-commerce, international SEO, Google APIs, and PDF/Excel reporting. 9 optional extensions for live SEO data.
- 主要语言 / 许可：Python / MIT
- 周新增 Star：3,516；当前累计 Star：23,730
- Fork：3,186；最近推送时间（UTC）：2026-10-22T16:47:40Z
- 官方资料：[AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo)（含 README）
- 中文用途与功能（AI）：Claude Code的免费开源SEO审计插件，由26个子技能和19个专业代理覆盖技术SEO、E-E-A-T、结构化数据、AI搜索可见性、本地与电商SEO等，并输出优先行动方案。
- 适用人群（AI）：需要网站SEO审计与优化建议的营销和开发人员
- 使用条件或局限（AI）：主要用于Claude Code环境；部分在线SEO数据能力属可选扩展，资料未细述。

### 8. anthropics/knowledge-work-plugins

- 维护方：anthropics
- 官方简介：Open source repository of plugins primarily intended for knowledge workers to use in Claude Cowork
- 主要语言 / 许可：Python / Apache-2.0
- 周新增 Star：2,612；当前累计 Star：33,762
- Fork：3,713；最近推送时间（UTC）：2026-10-29T07:28:50Z
- 官方资料：[anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)（含 README）
- 中文用途与功能（AI）：面向知识工作者的开源插件集，为Claude Cowork及Claude Code提供销售、法务、财务、市场、产品管理等11个职能插件，打包技能、斜杠命令、连接器与子代理。
- 适用人群（AI）：希望让Claude按岗位流程协作的企业知识工作者与团队
- 使用条件或局限（AI）：连接器依赖外部SaaS工具与MCP配置；可按组织需求自行定制。

AI 分析仅整理已提供的项目资料，未经实际安装与功能测试。

<!-- weekly-report:2026-10-29:end -->


<!-- weekly-report:2026-11-06:start -->
## 2026-11-06｜云端周报 Top 8

生成时间：2026-11-06T03:47:48+08:00（北京时间）  
榜单抓取时间：2026-11-06T03:47:50+08:00  
模式：DeepSeek / deepseek-flash 中文总结（根据官方简介及 README 节选）  
候选范围：本次 GitHub Trending / This week 页面解析到的 16 个项目。

按页面标注的周新增 Star 降序取前 8；来源：[GitHub 官方周榜](https://github.com/trending?since=weekly)。
This week 使用来源站点自己的滚动周口径，页面未提供精确起止时刻；不自行假定为周一至今。
本期是周榜候选范围内排名，不是 GitHub 全站全部仓库的增长排名。
周增量来自榜单；累计 Star、语言和许可证等来自随后读取的仓库 API，采样时点不同。
许可证为 GitHub 自动识别结果，多组件或模型的许可应另查原文件。

| 排名 | 项目 | 周新增 Star | 当前累计 Star | 主要语言 | 许可证 |
| --- | --- | ---: | ---: | --- | --- |
| 1 | [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | 14,580 | 48,051 | TypeScript | MIT |
| 2 | [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | 10,921 | 103,762 | Rust | Apache-2.0 |
| 3 | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | 8,822 | 113,460 | TypeScript | Apache-2.0 |
| 4 | [Nutlope/hallmark](https://github.com/Nutlope/hallmark) | 7,622 | 48,632 | CSS | MIT |
| 5 | [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor) | 7,512 | 55,392 | Python | Apache-2.0 |
| 6 | [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | 5,935 | 110,548 | JavaScript | MIT |
| 7 | [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot) | 5,847 | 13,134 | TypeScript | Apache-2.0 |
| 8 | [obra/superpowers](https://github.com/obra/superpowers) | 5,565 | 312,926 | Shell | MIT |

### 1. pingdotgg/t3code

- 维护方：pingdotgg
- 官方简介：官方未填写简介
- 主要语言 / 许可：TypeScript / MIT
- 周新增 Star：14,580；当前累计 Star：48,051
- Fork：9,588；最近推送时间（UTC）：2026-11-05T19:46:45Z
- 官方资料：[pingdotgg/t3code](https://github.com/pingdotgg/t3code)（含 README）
- 中文用途与功能（AI）：面向编码智能体的控制面板，可通过iOS、Android、Web和桌面端远程控制本机的Claude Code、Codex、Cursor等智能体，支持命令行启动与后台服务。
- 适用人群（AI）：需要远程操控本地AI编码智能体的开发者
- 使用条件或局限（AI）：项目自述处于早期阶段，可能有缺陷，且暂不接受大型功能贡献；使用前需先安装并登录至少一个支持的提供方。

### 2. pbakaus/impeccable

- 维护方：pbakaus
- 官方简介：The design vocabulary for your coding agent. Steer with polish and bolder, review with critique and audit, catch AI slop before it ships.
- 主要语言 / 许可：Rust / Apache-2.0
- 周新增 Star：10,921；当前累计 Star：103,762
- Fork：6,145；最近推送时间（UTC）：2026-11-05T19:43:28Z
- 官方资料：[pbakaus/impeccable](https://github.com/pbakaus/impeccable)（含 README）
- 中文用途与功能（AI）：为编码智能体提供设计词汇的Agent Skill，通过polish、bolder等命令调整设计，用critique和audit审查界面，并用规则检测识别AI生成式套路。
- 适用人群（AI）：希望提升AI生成界面设计质量的开发者与设计工程师
- 使用条件或局限（AI）：需用npx安装并在所支持的工具中初始化；效果依赖已有界面，官方称在现有页面上迭代最强。

### 3. thedotmack/claude-mem

- 维护方：thedotmack
- 官方简介：Persistent Context Across Sessions for Every Agent –  Captures everything your agent does during sessions, compresses it with AI, and injects relevant context back into future sessions. Works with Claude Code, OpenClaw, Codex, Gemini, Hermes, Copilot, OpenCode + More
- 主要语言 / 许可：TypeScript / Apache-2.0
- 周新增 Star：8,822；当前累计 Star：113,460
- Fork：9,847；最近推送时间（UTC）：2026-11-05T19:34:43Z
- 官方资料：[thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)（含 README）
- 中文用途与功能（AI）：为编码智能体提供持久记忆的压缩系统，捕获会话中智能体的操作内容，用AI压缩后把相关上下文注入后续会话，支持Claude Code、Codex、Gemini等多种工具。
- 适用人群（AI）：希望跨会话保留上下文的编码智能体用户
- 使用条件或局限（AI）：README主要展示项目介绍与徽章，具体使用条件和局限未完整呈现；需Node 20以上版本。

### 4. Nutlope/hallmark

- 维护方：Nutlope
- 官方简介：Anti-AI-slop design skill for Claude Code, Cursor, and Codex.
- 主要语言 / 许可：CSS / MIT
- 周新增 Star：7,622；当前累计 Star：48,632
- Fork：2,579；最近推送时间（UTC）：2026-11-05T13:16:31Z
- 官方资料：[Nutlope/hallmark](https://github.com/Nutlope/hallmark)（含 README）
- 中文用途与功能（AI）：防止页面看起来像AI生成的设计技能，为Claude Code、Codex、Cursor等提供五十种主题，围绕用户目标构建页面，并在真实浏览器中按规则检查生成结果。
- 适用人群（AI）：需要生成非模板化网页设计的开发者与设计者
- 使用条件或局限（AI）：资料为README节选，安装与完整用法未完整展示；具体适用条件和限制未确认。

### 5. HKUDS/DeepTutor

- 维护方：HKUDS
- 官方简介：DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/.
- 主要语言 / 许可：Python / Apache-2.0
- 周新增 Star：7,512；当前累计 Star：55,392
- Fork：6,790；最近推送时间（UTC）：2026-11-05T19:03:44Z
- 官方资料：[HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor)（含 README）
- 中文用途与功能（AI）：名为DeepTutor的终身个性化辅导项目，提供文档站点与CLI等接口，使用Python 3.11+与Next.js构建，README包含功能介绍和社区链接。
- 适用人群（AI）：关注AI个性化教育辅导的研究者与开发者
- 使用条件或局限（AI）：README为节选，核心功能细节、具体使用条件和性能表现未被完整提供，需要进一步确认。

### 6. Leonxlnx/taste-skill

- 维护方：Leonxlnx
- 官方简介：Agent skills that give coding agents taste: art direction, reference images and a browser check instead of generic AI pages
- 主要语言 / 许可：JavaScript / MIT
- 周新增 Star：5,935；当前累计 Star：110,548
- Fork：7,428；最近推送时间（UTC）：2026-11-05T01:12:12Z
- 官方资料：[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)（含 README）
- 中文用途与功能（AI）：让编码智能体具备设计品味的Agent Skill，通过艺术指导、参考图片和真实浏览器检查，生成接近专业公司网站水平的页面，并遵循统一设计与真实素材规则。
- 适用人群（AI）：希望智能体产出高质量商业网站页面的开发者
- 使用条件或局限（AI）：需Node 22以上及已安装Chrome、Edge或Chromium；可选ffmpeg用于WebP输出，安装不引入API密钥。

### 7. milind-soni/OpenMausBot

- 维护方：milind-soni
- 官方简介：Open-source Grok Bot alternative with a virtual machine that bots can use
- 主要语言 / 许可：TypeScript / Apache-2.0
- 周新增 Star：5,847；当前累计 Star：13,134
- Fork：1,818；最近推送时间（UTC）：2026-11-05T19:42:28Z
- 官方资料：[milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot)（含 README）
- 中文用途与功能（AI）：开源的Grok Bot替代方案，以聊天应用形式提供多个AI智能体，每个机器人有独立人格、模型和云电脑，底层可运行本地的Claude或Codex，支持审批操作。
- 适用人群（AI）：希望本地自建多智能体聊天体验的用户
- 使用条件或局限（AI）：项目自称独立开源、与xAI等无关联；README强调无代币关联。系统要求与完整限制未详尽说明。

### 8. obra/superpowers

- 维护方：obra
- 官方简介：An agentic skills framework &amp; software development methodology that works.
- 主要语言 / 许可：Shell / MIT
- 周新增 Star：5,565；当前累计 Star：312,926
- Fork：27,842；最近推送时间（UTC）：2026-11-03T23:24:58Z
- 官方资料：[obra/superpowers](https://github.com/obra/superpowers)（含 README）
- 中文用途与功能（AI）：为编码智能体提供完整软件开发方法论的技能框架，先梳理需求与设计，再生成实现计划，并以子智能体驱动开发逐项完成任务，强调TDD、YAGNI与DRY。
- 适用人群（AI）：希望规范AI辅助开发流程的工程团队与开发者
- 使用条件或局限（AI）：需按不同工具分别安装，资料仅展示部分安装方式；系统实际效果与限制未完整提供。

AI 分析仅整理已提供的项目资料，未经实际安装与功能测试。

<!-- weekly-report:2026-11-06:end -->


<!-- weekly-report:2026-11-13:start -->
## 2026-11-13｜云端周报 Top 8

生成时间：2026-11-13T03:47:19+08:00（北京时间）  
榜单抓取时间：2026-11-13T03:47:21+08:00  
模式：DeepSeek / deepseek-flash 中文总结（根据官方简介及 README 节选）  
候选范围：本次 GitHub Trending / This week 页面解析到的 11 个项目。

按页面标注的周新增 Star 降序取前 8；来源：[GitHub 官方周榜](https://github.com/trending?since=weekly)。
This week 使用来源站点自己的滚动周口径，页面未提供精确起止时刻；不自行假定为周一至今。
本期是周榜候选范围内排名，不是 GitHub 全站全部仓库的增长排名。
周增量来自榜单；累计 Star、语言和许可证等来自随后读取的仓库 API，采样时点不同。
许可证为 GitHub 自动识别结果，多组件或模型的许可应另查原文件。

| 排名 | 项目 | 周新增 Star | 当前累计 Star | 主要语言 | 许可证 |
| --- | --- | ---: | ---: | --- | --- |
| 1 | [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) | 11,507 | 71,054 | JavaScript | MIT |
| 2 | [mattpocock/skills](https://github.com/mattpocock/skills) | 9,575 | 322,890 | Shell | MIT |
| 3 | [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot) | 9,257 | 21,661 | TypeScript | Apache-2.0 |
| 4 | [NVIDIA/auto-ontology](https://github.com/NVIDIA/auto-ontology) | 7,947 | 12,185 | Python | Apache-2.0 |
| 5 | [vercel-labs/agent-desktop](https://github.com/vercel-labs/agent-desktop) | 7,772 | 22,635 | Rust | Apache-2.0 |
| 6 | [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) | 5,814 | 102,060 | Python | BSD-3-Clause |
| 7 | [anthropics/skills](https://github.com/anthropics/skills) | 5,738 | 193,631 | Python | 未确认（需阅读 LICENSE） |
| 8 | [vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser) | 4,183 | 50,274 | Rust | Apache-2.0 |

### 1. cloudflare/security-audit-skill

- 维护方：cloudflare
- 官方简介：A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings
- 主要语言 / 许可：JavaScript / MIT
- 周新增 Star：11,507；当前累计 Star：71,054
- Fork：4,722；最近推送时间（UTC）：2026-09-14T19:29:02Z
- 官方资料：[cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill)（含 README）
- 中文用途与功能（AI）：面向编码代理的安全审计技能，按侦察、覆盖驱动查找、候选验证、结构化输出、独立记录校验与报告中立六阶段执行，产出可机读的确认、待验证与驳回记录。
- 适用人群（AI）：使用编码代理对代码库做安全审计的安全与开发人员
- 使用条件或局限（AI）：依赖技能安装方式与代理环境；实际效果与配置未经提供资料确认

### 2. mattpocock/skills

- 维护方：mattpocock
- 官方简介：Skills for Real Engineers. Straight from my .agents directory.
- 主要语言 / 许可：Shell / MIT
- 周新增 Star：9,575；当前累计 Star：322,890
- Fork：27,076；最近推送时间（UTC）：2026-11-12T12:11:43Z
- 官方资料：[mattpocock/skills](https://github.com/mattpocock/skills)（含 README）
- 中文用途与功能（AI）：作者日常使用的编码代理技能集合，强调小型、可修改、可组合，用于需求对齐、减少冗余输出等真实工程流程，支持多种代理安装。
- 适用人群（AI）：使用Claude Code、Codex等代理的软件工程师
- 使用条件或局限（AI）：部分技能需先运行设置流程；具体技能清单与效果资料节选未完整覆盖

### 3. milind-soni/OpenMausBot

- 维护方：milind-soni
- 官方简介：Open-source Grok Bot alternative with a virtual machine that bots can use
- 主要语言 / 许可：TypeScript / Apache-2.0
- 周新增 Star：9,257；当前累计 Star：21,661
- Fork：3,016；最近推送时间（UTC）：2026-11-12T19:36:03Z
- 官方资料：[milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot)（含 README）
- 中文用途与功能（AI）：开源桌面聊天应用，侧栏每个机器人都是本地运行的Claude或Codex代理，各有性格、模型、云端计算机与连接应用，可对话、观察工作并审批操作。
- 适用人群（AI）：希望在聊天界面管理本地AI代理团队的用户
- 使用条件或局限（AI）：支持macOS、Windows、Ubuntu；需自备模型与代理；与xAI等无关联

### 4. NVIDIA/auto-ontology

- 维护方：NVIDIA
- 官方简介：Auto Ontology is a Python framework for building semantic, graph-based reasoning layers over data. It enables deterministic query generation, better context retrieval, and more explainable AI for LLM and agent workflows.
- 主要语言 / 许可：Python / Apache-2.0
- 周新增 Star：7,947；当前累计 Star：12,185
- Fork：1,005；最近推送时间（UTC）：2026-11-12T13:38:54Z
- 官方资料：[NVIDIA/auto-ontology](https://github.com/NVIDIA/auto-ontology)（含 README）
- 中文用途与功能（AI）：Python框架，从企业元数据构建语义本体与知识图谱，协调跨系统定义，为代理提供可信业务含义，并通过MCP、CLI与API暴露上下文，支持查询校验与溯源。
- 适用人群（AI）：构建代理分析、自然语言查询结构化数据的数据与AI开发者
- 使用条件或局限（AI）：需NVIDIA NIM推理端点与API密钥、Postgres等组件；当前不接受外部贡献

### 5. vercel-labs/agent-desktop

- 维护方：vercel-labs
- 官方简介：Computer use CLI for AI agents
- 主要语言 / 许可：Rust / Apache-2.0
- 周新增 Star：7,772；当前累计 Star：22,635
- Fork：1,678；最近推送时间（UTC）：2026-11-11T06:09:45Z
- 官方资料：[vercel-labs/agent-desktop](https://github.com/vercel-labs/agent-desktop)（含 README）
- 中文用途与功能（AI）：让AI代理通过操作系统无障碍树查看并操作macOS、Windows、Linux桌面应用，快照返回带引用的JSON，代理按引用点击或输入后重新观察，无内置模型。
- 适用人群（AI）：需要桌面应用计算机使用能力的代理开发者
- 使用条件或局限（AI）：macOS需授予辅助功能权限；快照等可能含隐私内容，勿公开上传

### 6. D4Vinci/Scrapling

- 维护方：D4Vinci
- 官方简介：🕷️ The BEST Web Scraping framework that handles everything from a single request to a full-scale crawl! Don't be shy, join here: https://discord.gg/EMgGbDceNQ and follow here for daily tips and tricks: https://x.com/Scrapling_dev
- 主要语言 / 许可：Python / BSD-3-Clause
- 周新增 Star：5,814；当前累计 Star：102,060
- Fork：10,622；最近推送时间（UTC）：2026-11-11T19:16:10Z
- 官方资料：[D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling)（含 README）
- 中文用途与功能（AI）：Web抓取框架，覆盖从单次请求到大规模爬取的场景，提供选择器、多种抓取器与爬虫架构，并附代理与反封锁相关文档及多语言说明。
- 适用人群（AI）：需要抓取现代网页与构建爬虫的Python开发者
- 使用条件或局限（AI）：部分站点抓取涉及代理、合规与反封锁配置；具体能力需查阅文档确认

### 7. anthropics/skills

- 维护方：anthropics
- 官方简介：Public repository for Agent Skills
- 主要语言 / 许可：Python / 未确认（需阅读 LICENSE）
- 周新增 Star：5,738；当前累计 Star：193,631
- Fork：22,777；最近推送时间（UTC）：2026-11-06T22:32:32Z
- 官方资料：[anthropics/skills](https://github.com/anthropics/skills)（含 README）
- 中文用途与功能（AI）：Anthropic的Claude代理技能示例仓库，技能为含SKILL.md的文件夹，涵盖创意设计、技术任务、企业流程与文档处理，并提供规范与模板供参考。
- 适用人群（AI）：希望了解或创建Claude代理技能的开发者
- 使用条件或局限（AI）：仓库注明仅供演示与教育；实际Claude行为可能不同，关键任务需自行测试

### 8. vercel-labs/agent-browser

- 维护方：vercel-labs
- 官方简介：Browser automation CLI for AI agents
- 主要语言 / 许可：Rust / Apache-2.0
- 周新增 Star：4,183；当前累计 Star：50,274
- Fork：3,501；最近推送时间（UTC）：2026-11-12T18:59:27Z
- 官方资料：[vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser)（含 README）
- 中文用途与功能（AI）：原生Rust浏览器自动化CLI，代理可通过快照读取页面并获取元素引用，逐条命令点击、输入并复查结果，浏览器在命令间保持运行，支持多种引擎与云端浏览器。
- 适用人群（AI）：需要从命令行驱动浏览器的AI代理开发者
- 使用条件或局限（AI）：首次需下载Chrome for Testing；引用随页面变化失效；部分引擎与提供商需额外配置

AI 分析仅整理已提供的项目资料，未经实际安装与功能测试。

<!-- weekly-report:2026-11-13:end -->
