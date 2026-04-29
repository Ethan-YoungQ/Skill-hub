# 按技术栈 / 平台索引

按“用什么技术”聚合检索。同一技能可能出现在多个相关章节（交叉引用），因此本索引的总行数会高于技能总数。

## 目录

- [Python 生态](#python-生态)
- [Swift / Apple 生态](#swift--apple-生态)
- [前端 / Web](#前端--web)
- [飞书（Lark）生态](#飞书（lark）生态)
- [浏览器自动化](#浏览器自动化)
- [视频 / 影像生成](#视频--影像生成)
- [文档处理](#文档处理)
- [数据与研究](#数据与研究)
- [测试与质量](#测试与质量)
- [AI API / LLM 平台](#ai-api--llm-平台)
- [Agent 工程与自治编排](#agent-工程与自治编排)
- [行业与业务](#行业与业务)
- [办公自动化 / 协作](#办公自动化--协作)
- [Project AI Seed Project](#project-ai-seed-project)
- [Project AI Seed Project Phase One 飞书](#project-ai-seed-project-phase-one-飞书)
- [Project ALK Plus Tracker](#project-alk-plus-tracker)
- [Project Codex Invoice](#project-codex-invoice)
- [Project Content Assets](#project-content-assets)


## Python 生态

Python 语言、测试、PyTorch、数据处理与 Python 驱动的内容生成工具。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **docx** | [skills/07-media-content/docx/](../skills/07-media-content/docx/) | 全面处理 .docx：创建、编辑、修订跟踪、评论、格式保留与文本提取。 |
| **pptx** | [skills/07-media-content/pptx/](../skills/07-media-content/pptx/) | 演示文稿 .pptx 的创建、编辑、布局、评论与演讲者备注。 |
| **xlsx** | [skills/07-media-content/xlsx/](../skills/07-media-content/xlsx/) | 电子表格 .xlsx/.csv 等创建、编辑、公式、格式、数据分析与可视化。 |
| **data-scraper-agent** | [skills/06-data-search/data-scraper-agent/](../skills/06-data-search/data-scraper-agent/) | 构建全自动 AI 数据采集 Agent：按计划抓取公开源并用 LLM 富化入库。 |

## Swift / Apple 生态

Swift 语言与 Apple 平台（SwiftUI、端侧 FoundationModels、iOS 26 Liquid Glass）。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **foundation-models-on-device** | [skills/02-coding-languages/swift/foundation-models-on-device/](../skills/02-coding-languages/swift/foundation-models-on-device/) | Apple FoundationModels 端侧 LLM：文本生成、@Generable、工具调用、快照流。 |
| **liquid-glass-design** | [skills/02-coding-languages/swift/liquid-glass-design/](../skills/02-coding-languages/swift/liquid-glass-design/) | iOS 26 Liquid Glass 设计系统：SwiftUI/UIKit/WidgetKit 的玻璃材质与交互。 |
| **swift-concurrency-6-2** | [skills/02-coding-languages/swift/swift-concurrency-6-2/](../skills/02-coding-languages/swift/swift-concurrency-6-2/) | Swift 6.2 Approachable Concurrency：默认单线程、@concurrent 显式后台。 |
| **swiftui-patterns** | [skills/02-coding-languages/swift/swiftui-patterns/](../skills/02-coding-languages/swift/swiftui-patterns/) | SwiftUI 架构、@Observable 状态、视图组合、导航、性能优化、现代 UI 实践。 |

## 前端 / Web

React、Next.js、React Native 等前端框架与设计实践。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **vercel-react-best-practices** | [skills/03-frameworks/nextjs/vercel-react-best-practices/](../skills/03-frameworks/nextjs/vercel-react-best-practices/) | Vercel 工程出品的 React/Next.js 性能优化指引，含组件、数据获取、打包。 |

## 飞书（Lark）生态

飞书全系列 API 封装：即时通讯、云文档、审批、日历、多维表格、知识库等。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **lark-approval** | [skills/09-ops-productivity/lark/lark-approval/](../skills/09-ops-productivity/lark/lark-approval/) | 飞书审批 API：审批实例与审批任务的全量管理。 |
| **lark-base** | [skills/09-ops-productivity/lark/lark-base/](../skills/09-ops-productivity/lark/lark-base/) | lark-cli 操作飞书多维表格（Base）：建表、字段、记录、视图、工作流、分析。 |
| **lark-calendar** | [skills/09-ops-productivity/lark/lark-calendar/](../skills/09-ops-productivity/lark/lark-calendar/) | 飞书日历：日程与会议管理、忙闲查询、会议室预定等。 |
| **lark-contact** | [skills/09-ops-productivity/lark/lark-contact/](../skills/09-ops-productivity/lark/lark-contact/) | 飞书通讯录：查询组织架构、人员信息、按关键词搜索员工。 |
| **lark-doc** | [skills/09-ops-productivity/lark/lark-doc/](../skills/09-ops-productivity/lark/lark-doc/) | 飞书云文档：创建与编辑文档，从 Markdown 生成，文档搜索与资源定位。 |
| **lark-drive** | [skills/09-ops-productivity/lark/lark-drive/](../skills/09-ops-productivity/lark/lark-drive/) | 飞书云空间：文件与文件夹管理、评论、权限、本地文件导入为在线云文档。 |
| **lark-event** | [skills/09-ops-productivity/lark/lark-event/](../skills/09-ops-productivity/lark/lark-event/) | 飞书事件订阅：通过 WebSocket 长连接实时监听事件并输出 NDJSON。 |
| **lark-im** | [skills/09-ops-productivity/lark/lark-im/](../skills/09-ops-productivity/lark/lark-im/) | 飞书即时通讯：收发消息、搜聊天记录、管理群聊、上传下载图片文件。 |
| **lark-mail** | [skills/09-ops-productivity/lark/lark-mail/](../skills/09-ops-productivity/lark/lark-mail/) | 飞书邮箱：草稿、编辑、发送、回复、转发、搜索、附件、文件夹、规则。 |
| **lark-minutes** | [skills/09-ops-productivity/lark/lark-minutes/](../skills/09-ops-productivity/lark/lark-minutes/) | 飞书妙记：查询与获取妙记信息、下载音视频、获取 AI 总结/待办/章节。 |
| **lark-openapi-explorer** | [skills/09-ops-productivity/lark/lark-openapi-explorer/](../skills/09-ops-productivity/lark/lark-openapi-explorer/) | 飞书原生 OpenAPI 探索：当 lark-* skill 未覆盖时查询原生接口。 |
| **lark-shared** | [skills/09-ops-productivity/lark/lark-shared/](../skills/09-ops-productivity/lark/lark-shared/) | lark-cli 共享基础：配置、登录、身份切换、scope 与权限错误处理。 |
| **lark-sheets** | [skills/09-ops-productivity/lark/lark-sheets/](../skills/09-ops-productivity/lark/lark-sheets/) | 飞书电子表格：创建、读写、追加、查找、导出，与 docs 搜索分工。 |
| **lark-skill-maker** | [skills/09-ops-productivity/lark/lark-skill-maker/](../skills/09-ops-productivity/lark/lark-skill-maker/) | 创建 lark-cli 自定义 Skill：包装原子 API 或编排多步 API 流程。 |
| **lark-slides** | [skills/09-ops-productivity/lark/lark-slides/](../skills/09-ops-productivity/lark/lark-slides/) | 飞书幻灯片：用 XML 读取与管理 PPT 页面，创建演示优先用 +create。 |
| **lark-task** | [skills/09-ops-productivity/lark/lark-task/](../skills/09-ops-productivity/lark/lark-task/) | 飞书任务：创建待办、管理任务状态与子任务、组织任务清单、分配协作。 |
| **lark-vc** | [skills/09-ops-productivity/lark/lark-vc/](../skills/09-ops-productivity/lark/lark-vc/) | 飞书视频会议：查询会议记录与纪要（总结、待办、章节、逐字稿）。 |
| **lark-whiteboard** | [skills/09-ops-productivity/lark/lark-whiteboard/](../skills/09-ops-productivity/lark/lark-whiteboard/) | 飞书画板：导出预览、节点结构，用 PlantUML/Mermaid 或 OpenAPI 编辑画板。 |
| **lark-whiteboard-cli** | [skills/09-ops-productivity/lark/lark-whiteboard-cli/](../skills/09-ops-productivity/lark/lark-whiteboard-cli/) | 用 whiteboard-cli 在飞书画板绘制架构图、流程图、思维导图等的布局指南。 |
| **lark-wiki** | [skills/09-ops-productivity/lark/lark-wiki/](../skills/09-ops-productivity/lark/lark-wiki/) | 飞书知识库：管理知识空间与节点层级、组织文档与快捷方式。 |
| **lark-workflow-meeting-summary** | [skills/09-ops-productivity/lark/lark-workflow-meeting-summary/](../skills/09-ops-productivity/lark/lark-workflow-meeting-summary/) | 会议纪要整理工作流：汇总指定时间范围内的会议纪要并生成结构化报告。 |
| **lark-workflow-standup-report** | [skills/09-ops-productivity/lark/lark-workflow-standup-report/](../skills/09-ops-productivity/lark/lark-workflow-standup-report/) | 日程待办摘要：编排 calendar 与 task，生成指定日期的日程与未完成任务摘要。 |

## 浏览器自动化

浏览器控制、E2E 测试、远程浏览器与 Electron 自动化。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **agent-browser** | [skills/01-agent-engineering/agent-browser/](../skills/01-agent-engineering/agent-browser/) | AI Agent 的浏览器自动化 CLI，用于网页导航、表单填写、截图、数据抓取。 |
| **browser-use** | [skills/01-agent-engineering/browser-use/](../skills/01-agent-engineering/browser-use/) | 浏览器交互自动化，用于网页测试、表单填写、截图、数据提取。 |
| **remote-browser** | [skills/01-agent-engineering/remote-browser/](../skills/01-agent-engineering/remote-browser/) | 在沙箱远端机器上控制本地浏览器，用于无 GUI 沙箱场景。 |
| **electron** | [skills/01-agent-engineering/electron/](../skills/01-agent-engineering/electron/) | 通过 CDP 用 agent-browser 自动化 Electron 桌面应用（VS Code、Slack 等）。 |
| **vercel-sandbox** | [skills/01-agent-engineering/vercel-sandbox/](../skills/01-agent-engineering/vercel-sandbox/) | 在 Vercel Sandbox 微型 VM 中运行 agent-browser + Chrome 做浏览器自动化。 |
| **ck** | [skills/01-agent-engineering/ck/](../skills/01-agent-engineering/ck/) | 项目级持久记忆，自动加载项目上下文、追踪 git 会话、写入原生内存。 |

## 视频 / 影像生成

剪映 API、Remotion 视频创作与 HTML 幻灯片。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **jianying-editor** | [skills/07-media-content/jianying-editor/](../skills/07-media-content/jianying-editor/) | 剪映 AI 自动剪辑高级封装 API（JyWrapper）：录屏、素材、字幕、Web 动效。 |
| **remotion-video-creation** | [skills/07-media-content/remotion-video-creation/](../skills/07-media-content/remotion-video-creation/) | Remotion 在 React 中做视频创作的 29 条领域规则（3D、动画、字幕、过渡）。 |

## 文档处理

Word、PDF、PPT、Excel 的创建、编辑与转换。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **docx** | [skills/07-media-content/docx/](../skills/07-media-content/docx/) | 全面处理 .docx：创建、编辑、修订跟踪、评论、格式保留与文本提取。 |
| **pptx** | [skills/07-media-content/pptx/](../skills/07-media-content/pptx/) | 演示文稿 .pptx 的创建、编辑、布局、评论与演讲者备注。 |
| **xlsx** | [skills/07-media-content/xlsx/](../skills/07-media-content/xlsx/) | 电子表格 .xlsx/.csv 等创建、编辑、公式、格式、数据分析与可视化。 |
| **visa-doc-translate** | [skills/07-media-content/visa-doc-translate/](../skills/07-media-content/visa-doc-translate/) | 签证申请文件图片翻译并生成中英双语 PDF。 |

## 数据与研究

数据抓取、医学文献检索与研究摘要生成。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **data-scraper-agent** | [skills/06-data-search/data-scraper-agent/](../skills/06-data-search/data-scraper-agent/) | 构建全自动 AI 数据采集 Agent：按计划抓取公开源并用 LLM 富化入库。 |
| **medical-research** | [skills/06-data-search/medical-research/](../skills/06-data-search/medical-research/) | 从 PubMed 获取论文并生成通俗易懂的研究摘要，覆盖医学/临床/科研主题。 |
| **pubmed-search** | [skills/06-data-search/pubmed-search/](../skills/06-data-search/pubmed-search/) | 通过 Valyu 语义搜索以自然语言检索 PubMed 生物医学文献，支持全文。 |

## 测试与质量

E2E 测试、TDD、代码审查与质量门禁。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **click-path-audit** | [skills/04-testing-quality/click-path-audit/](../skills/04-testing-quality/click-path-audit/) | 追踪每个用户按钮的完整状态变更序列，发现功能各自正确但相互抵消的 bug。 |

## AI API / LLM 平台

LLM 管线、Token 预算、端侧模型。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **token-budget-advisor** | [skills/12-ai-api/token-budget-advisor/](../skills/12-ai-api/token-budget-advisor/) | 在回答前给用户选择响应深度与 Token 预算的顾问式工作流。 |
| **foundation-models-on-device** | [skills/02-coding-languages/swift/foundation-models-on-device/](../skills/02-coding-languages/swift/foundation-models-on-device/) | Apple FoundationModels 端侧 LLM：文本生成、@Generable、工具调用、快照流。 |

## Agent 工程与自治编排

Agent 构建、调试、自治循环、验证与编排。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **agent-browser** | [skills/01-agent-engineering/agent-browser/](../skills/01-agent-engineering/agent-browser/) | AI Agent 的浏览器自动化 CLI，用于网页导航、表单填写、截图、数据抓取。 |
| **agent-payment-x402** | [skills/01-agent-engineering/agent-payment-x402/](../skills/01-agent-engineering/agent-payment-x402/) | 为 Agent 接入 x402 支付执行能力，含任务预算、支出控制、非托管钱包。 |
| **agentcore** | [skills/01-agent-engineering/agentcore/](../skills/01-agent-engineering/agentcore/) | 在 AWS Bedrock AgentCore 云端浏览器上运行 agent-browser。 |
| **blueprint** | [skills/01-agent-engineering/blueprint/](../skills/01-agent-engineering/blueprint/) | 把一句话目标转为多会话多 Agent 的分步构建计划，每步自带冷启动上下文。 |
| **browser-use** | [skills/01-agent-engineering/browser-use/](../skills/01-agent-engineering/browser-use/) | 浏览器交互自动化，用于网页测试、表单填写、截图、数据提取。 |
| **ck** | [skills/01-agent-engineering/ck/](../skills/01-agent-engineering/ck/) | 项目级持久记忆，自动加载项目上下文、追踪 git 会话、写入原生内存。 |
| **claude-devfleet** | [skills/01-agent-engineering/claude-devfleet/](../skills/01-agent-engineering/claude-devfleet/) | 通过 Claude DevFleet 编排多 Agent 编码任务，并行 worktree 派发与监控。 |
| **cloud** | [skills/01-agent-engineering/cloud/](../skills/01-agent-engineering/cloud/) | Browser Use Cloud 托管 API 与 SDK 的文档参考。 |
| **dogfood** | [skills/01-agent-engineering/dogfood/](../skills/01-agent-engineering/dogfood/) | 系统化测试 Web 应用以发现 Bug、UX 问题，输出带截图和复现步骤的报告。 |
| **electron** | [skills/01-agent-engineering/electron/](../skills/01-agent-engineering/electron/) | 通过 CDP 用 agent-browser 自动化 Electron 桌面应用（VS Code、Slack 等）。 |
| **find-skill** | [skills/01-agent-engineering/find-skill/](../skills/01-agent-engineering/find-skill/) | 技能发现入口（文件体为空，疑似占位）。 |
| **find-skills** | [skills/01-agent-engineering/find-skills/](../skills/01-agent-engineering/find-skills/) | 自动发现与推荐可用 Agent 技能，回答"有没有能做 X 的技能"。 |
| **hookify-rules** | [skills/01-agent-engineering/hookify-rules/](../skills/01-agent-engineering/hookify-rules/) | 创建 hookify 规则的语法与模式指南。 |
| **open-source** | [skills/01-agent-engineering/open-source/](../skills/01-agent-engineering/open-source/) | browser-use 开源 Python 库的文档参考（Agent/Browser/Tools 配置）。 |
| **openclaw-persona-forge** | [skills/01-agent-engineering/openclaw-persona-forge/](../skills/01-agent-engineering/openclaw-persona-forge/) | 为 OpenClaw AI Agent 锻造龙虾灵魂方案：身份、角色底线、头像提示词。 |
| **plankton-code-quality** | [skills/01-agent-engineering/plankton-code-quality/](../skills/01-agent-engineering/plankton-code-quality/) | 基于 Plankton 的写入期代码质量把关——保存时自动格式化、lint、Claude 修复。 |
| **proactive-agent** | [skills/01-agent-engineering/proactive-agent/](../skills/01-agent-engineering/proactive-agent/) | 把 Agent 从被动执行者转为主动伙伴，跨会话记忆、主动建议下一步。 |
| **prompt-optimizer** | [skills/01-agent-engineering/prompt-optimizer/](../skills/01-agent-engineering/prompt-optimizer/) | 分析原始 prompt，匹配 ECC 组件并输出可粘贴的优化版，仅作顾问不执行。 |
| **remote-browser** | [skills/01-agent-engineering/remote-browser/](../skills/01-agent-engineering/remote-browser/) | 在沙箱远端机器上控制本地浏览器，用于无 GUI 沙箱场景。 |
| **repo-scan** | [skills/01-agent-engineering/repo-scan/](../skills/01-agent-engineering/repo-scan/) | 跨栈源码资产审计，分类文件、识别嵌入第三方库，输出四级判定 HTML 报告。 |
| **santa-method** | [skills/01-agent-engineering/santa-method/](../skills/01-agent-engineering/santa-method/) | 多 Agent 对抗验证收敛循环，两个独立审查都通过后才出交付。 |
| **skill-creator** | [skills/01-agent-engineering/skill-creator/](../skills/01-agent-engineering/skill-creator/) | 创建、修改和优化 skill，并可跑 eval 衡量触发准确率与性能。 |
| **team-builder** | [skills/01-agent-engineering/team-builder/](../skills/01-agent-engineering/team-builder/) | 交互式 Agent 选择器，用于组合并派发并行团队。 |
| **vercel-sandbox** | [skills/01-agent-engineering/vercel-sandbox/](../skills/01-agent-engineering/vercel-sandbox/) | 在 Vercel Sandbox 微型 VM 中运行 agent-browser + Chrome 做浏览器自动化。 |

## 行业与业务

医疗、法律等垂直行业场景。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **contract-review** | [skills/10-business-industry/contract-review/](../skills/10-business-industry/contract-review/) | 合同审核：三层审查（基础/业务/法律）、结构化注释、摘要与 Mermaid 流程图。 |
| **healthcare-cdss-patterns** | [skills/10-business-industry/healthcare-cdss-patterns/](../skills/10-business-industry/healthcare-cdss-patterns/) | 临床决策支持系统开发：药物互作、剂量校验、临床评分、告警分级与 EMR 集成。 |
| **healthcare-emr-patterns** | [skills/10-business-industry/healthcare-emr-patterns/](../skills/10-business-industry/healthcare-emr-patterns/) | 医疗 EMR/EHR 开发模式：临床安全、就诊流程、处方生成、CDSS 集成、无障碍 UI。 |
| **healthcare-eval-harness** | [skills/10-business-industry/healthcare-eval-harness/](../skills/10-business-industry/healthcare-eval-harness/) | 医疗发布的病人安全评测 harness：CDSS、PHI、临床流程与集成合规，失败阻断上线。 |
| **healthcare-phi-compliance** | [skills/10-business-industry/healthcare-phi-compliance/](../skills/10-business-industry/healthcare-phi-compliance/) | 医疗应用 PHI/PII 合规：数据分级、访问控制、审计、加密、常见泄漏路径。 |

## 办公自动化 / 协作

GitHub 运维、邮件、消息、项目管理等通用办公工具。

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **slack** | [skills/09-ops-productivity/general/slack/](../skills/09-ops-productivity/general/slack/) | 通过浏览器自动化在 Slack 中检查未读、导航、发消息、搜对话、抓取信息。 |

## Project AI Seed Project

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **aliyun-openapi-mcp-ops** | [projects/ai-seed-project/aliyun-openapi-mcp-ops/](../projects/ai-seed-project/aliyun-openapi-mcp-ops/) | 通过自建 OpenAPI MCP 运维阿里云，聚焦 SWAS 部署：OAuth、选择器更新、诊断、预发验证。 |
| **feishu-automation** | [projects/ai-seed-project/feishu-automation/](../projects/ai-seed-project/feishu-automation/) | 飞书自动化能力，优先用官方 OpenAPI MCP/CLI，不把后台配置动作误判为 MCP 能力。 |

## Project AI Seed Project Phase One 飞书

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **aliyun-swas-manage** | [projects/ai-seed-project-phase-one-feishu/aliyun-swas-manage/](../projects/ai-seed-project-phase-one-feishu/aliyun-swas-manage/) | 端到端管理阿里云 SWAS：实例、命令、磁盘快照、防火墙、监控与轻量数据库。 |
| **feishu-card-ws** | [projects/ai-seed-project-phase-one-feishu/feishu-card-ws/](../projects/ai-seed-project-phase-one-feishu/feishu-card-ws/) | 飞书交互式卡片在 WebSocket 长连接模式下的配置指南与回调处理。 |

## Project ALK Plus Tracker

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **hui-rui-lan** | [projects/alk-plus-tracker/hui-rui-lan/](../projects/alk-plus-tracker/hui-rui-lan/) | 重建或扩展 ALK+ Tracker UI 时保留原始品牌蓝视觉体系、区块顺序、玻璃卡片布局。 |

## Project Codex Invoice

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **163-email-ground-truth** | [projects/codex-invoice/163-email-ground-truth/](../projects/codex-invoice/163-email-ground-truth/) | 163/网易邮箱真值集构建、审计与跑批，含 IMAP ID 命令等特殊处理。 |
| **controlled-lockcheck-autofix** | [projects/codex-invoice/controlled-lockcheck-autofix/](../projects/codex-invoice/controlled-lockcheck-autofix/) | QQ 受控前端 lockcheck 自动化：失败分类、受限自动修复、打包门的证据留存。 |
| **email-batch-test** | [projects/codex-invoice/email-batch-test/](../projects/codex-invoice/email-batch-test/) | 跑批测试标准与双邮箱回归门禁：P0/P1/P2 标准与保护区改动的双邮箱验证。 |
| **qq-email-ground-truth** | [projects/codex-invoice/qq-email-ground-truth/](../projects/codex-invoice/qq-email-ground-truth/) | 构建/重建/审计/比对 QQ 邮箱发票真值集，验证跑批输出。 |

## Project Content Assets

| 技能名 | 路径 | 中文简介 |
|---|---|---|
| **ai-music-generation** | [projects/content-assets/ai-music-generation/](../projects/content-assets/ai-music-generation/) | 通过 inference.sh 生成 AI 音乐/歌曲，支持 ElevenLabs、Diffrythm、腾讯歌曲生成。 |
| **create-promo-video** | [projects/content-assets/create-promo-video/](../projects/content-assets/create-promo-video/) | 为项目生成 TikTok 风格短宣传片，分析代码库后用 Remotion 输出竖版/横版。 |
| **video-producer** | [projects/content-assets/video-producer/](../projects/content-assets/video-producer/) | 端到端 Remotion 视频制作：叙事、场景动画、视觉风格、渲染全链路编排。 |

