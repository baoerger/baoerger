# Baoerger

**Agent Developer · AI Applications · Research Engineering**

我主要做能处理真实文档、调用工具、维护上下文并解释执行结果的 Agent 系统，关注文档智能、工作流编排、混合检索、长期记忆、评测和运行时可靠性。

## Current focus

- **Agent runtime**：Supervisor–Worker、ReAct、Plan-and-Execute、Tool Calling、MCP、检查点和失败恢复
- **Document intelligence**：Docling / LibreOffice 解析、结构感知切分、局部—跨章节—全文上下文构造
- **Retrieval & memory**：SQL + 规则 + 向量混合召回、Qdrant / OpenSearch、偏好记忆、语义缓存和上下文压缩
- **Evaluation & observability**：LLM-as-a-Judge、Regression Eval、结构化 Execution Trace、LangFuse、指标归因

## Experience

### Agent Developer Intern · Momenta

**2026.04 — present · Enterprise document QA platform**

- 参与建设“文档解析 → Agent 检测 → 问题治理 → 自动评测”平台，覆盖 200+ 用户、5000+ 检测任务。
- 使用 Docling / LibreOffice 将多格式文档拆成章节、表格和代码等检测单元，按规则路由到语义检测、程序化校验和全局一致性路径；结合 FastAPI、Redis / ARQ 实现并行调度、检查点和分块级恢复，将失败任务的平均重复计算比例从 100% 降至 51%。
- 将多路检测结果统一为带原文证据的问题对象，通过定位校验、相似问题聚合和历史误报过滤，形成可追溯的问题治理链路。
- 搭建自动评测与 Execution Trace，串联任务、模型/工具调用、证据和最终问题；Precision **77% → 89%**、Recall **68% → 81%**、F1 **72.2% → 84.8%**。

### AI Application Developer Intern · Asiainfo Security

**2025.12 — 2026.04 · LLM-powered CRM assistant**

- 面向销售运营团队构建对话式 CRM Agent，覆盖 2500+ 业务群聊。
- 设计“意图识别 → 动态抽取 → 多路检索 → 多轮确认”链路，将单次商机录入平均交互时间从 **150s+ 降至 42s**。
- 落地 SQL、规则和向量三路混合召回，并用 200 条标注数据建立评测集；实体命中率从 **43.0% 提升至 92.5%**。
- 引入 LLM-as-a-Judge，对低分数据执行“评分 → 拦截 → 给出建议并重写”，脏数据拦截率达到 **28%**。

## Selected projects

### [Globex](https://github.com/baoerger/globex)

跨境购物 Agent 工程原型。仓库实现商品检索与重排、订单工具、偏好记忆、Redis 队列、FastAPI / WebSocket 事件流和 React 工作台；通过工具调用约束、上下文治理和检索评测把长链路 Agent 的行为变成可观察、可测试的流程。当前公开版本包含 **291 个测试**。

### [Editable PPT Rebuilder](https://github.com/baoerger/editable-ppt-rebuilder)

面向图片化幻灯片的可编辑重建工作流。它把可读文字还原为文本框，把简单结构还原为原生形状，把复杂视觉拆成独立资产，并用 OCR、ImageGen 视觉核心、裁剪审核和 PowerPoint 渲染验证形成交付闭环。

### [Tunnel Fire Research](https://github.com/baoerger/tunnel-fire-research)

基于 FDS 6.10.1 的无风隧道顶棚温度研究代码。包含输入生成、运行结果审计、HRR / CSV 读取、准稳态识别、统计分析和测试，重点是让仿真输入、证据和阶段性结论保持可追溯。

### [Novel2Script](https://github.com/baoerger/novel-to-script)

全栈中文小说转剧本系统。七阶段流水线覆盖长文本分片、逐章分析、跨章角色去重、关系图谱、场景生成、结构化 YAML 输出和质量报告，配套 FastAPI 后端与 React 编辑界面。

## Education

- **东南大学** — 交通运输（AI 应用与智能决策），硕士，2024.09 — present
- **天津理工大学** — 物联网工程，学士，2019.09 — 2023.06

## Toolbox

`Python` · `Go` · `FastAPI` · `PostgreSQL` · `MySQL` · `Redis` · `LangGraph` · `AgentScope` · `ReAct` · `Plan-and-Execute` · `Tool Calling` · `MCP` · `Multi-Agent` · `Qdrant` · `OpenSearch` · `Context Engineering` · `Agent Eval` · `LLM-as-a-Judge` · `LangFuse` · `Codex` · `Claude Code`

## More history

早期学习项目的真实提交历史整理在 [Legacy Labs](https://github.com/baoerger/legacy-labs)，当前仓库精选区只保留能体现 Agent 开发、研究工程和可维护交付能力的项目。

## Awards

蓝桥杯国二 / 省一 · 数学竞赛三等奖 · CET-6
