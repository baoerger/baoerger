# Baoerger

**Agent Developer · AI Applications · Research Engineering**

东南大学硕士（交通运输 · AI 应用与智能决策），做能处理真实文档、调用工具、维护上下文并解释执行结果的 Agent 系统。

## Focus

`Agent orchestration` · `Tool Calling` · `MCP` · `Context Engineering` · `Hybrid Retrieval` · `Long-term Memory` · `Agent Evaluation` · `Observability`

## Selected work

### [Tunnel Fire Research](https://github.com/baoerger/tunnel-fire-research)

基于 FDS 6.10.1 的无风隧道顶棚温度研究代码，与硕士阶段的交通运输方向直接相关。覆盖输入生成、运行结果审计、HRR / CSV 读取、准稳态识别、统计分析和测试，重点是让仿真输入、证据和阶段性结论保持可追溯。

### [Globex](https://github.com/baoerger/globex)

跨境购物 Agent 工程原型，包含商品检索与重排、订单工具、偏好记忆、Redis 队列、FastAPI / WebSocket 事件流和 React 工作台。通过工具调用约束、上下文治理和检索评测，把长链路 Agent 的行为变成可观察、可测试的流程。

### [Novel2Script](https://github.com/baoerger/novel-to-script)

中文小说转剧本的全栈应用，个人独立完成的课程项目。七阶段流水线覆盖长文本分片、逐章分析、跨章角色去重、关系图谱、场景生成、结构化 YAML 输出和质量报告；配套 Docker 全栈启动与 [B 站演示视频](https://www.bilibili.com/video/BV1fqEt6xEbV/)。

### [Editable PPT Rebuilder](https://github.com/baoerger/editable-ppt-rebuilder)

将图片化幻灯片重建为可编辑 PowerPoint：文字转文本框，简单结构转原生形状，复杂视觉转独立资产，并通过 OCR、ImageGen 和渲染验证完成质量检查。

## Experience

### Agent Developer Intern · Momenta

**2026.04 — 至今 · 企业文档问答平台**

- 参与建设「文档解析 → Agent 检测 → 问题治理 → 自动评测」平台，覆盖 200+ 用户、5000+ 检测任务。
- 使用 Docling / LibreOffice 将多格式文档拆成章节、表格和代码等检测单元，按规则路由到语义检测、程序化校验和全局一致性路径；结合 FastAPI、Redis / ARQ 实现并行调度、检查点与分块级恢复，把失败任务的平均重复计算比例从 100% 降至 51%。
- 将多路检测结果统一为带原文证据的问题对象，通过定位校验、相似问题聚合和历史误报过滤，形成可追溯的问题治理链路。
- 搭建自动评测与 Execution Trace，串联任务、模型 / 工具调用、证据和最终问题；Precision 77% → 89%，Recall 68% → 81%，F1 72.2% → 84.8%。

### AI Application Developer Intern · Asiainfo Security

**2025.12 — 2026.04 · LLM 驱动的 CRM 助手**

- 面向销售运营团队构建对话式 CRM Agent，覆盖 2500+ 业务群聊。
- 设计「意图识别 → 动态抽取 → 多路检索 → 多轮确认」链路，将单次商机录入的平均交互时间从 150s+ 降至 42s。
- 落地 SQL、规则和向量三路混合召回，并用 200 条标注数据建立评测集；实体命中率从 43.0% 提升至 92.5%。

## Background

- **东南大学** — 交通运输（AI 应用与智能决策），硕士，2024.09 — 2027.06（预计）
- **天津理工大学** — 物联网工程，学士，2019.09 — 2023.06

## Toolbox

`Python` · `Go` · `FastAPI` · `Redis` · `PostgreSQL` · `LangGraph` · `AgentScope` · `ReAct` · `Plan-and-Execute` · `Tool Calling` · `MCP` · `Qdrant` · `OpenSearch` · `LLM-as-a-Judge` · `LangFuse` · `Codex` · `Claude Code`

## Awards

蓝桥杯国二 / 省一 · 数学竞赛三等奖 · CET-6

早期 Java / 算法练习与 fork 项目已归档在 [Legacy Labs](https://github.com/baoerger/legacy-labs)。
