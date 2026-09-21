# Baoerger

研究工程与 AI 应用开发

我关注把复杂任务整理成**可复现、可审计、可维护**的工程流程：让模型负责高频整理和候选生成，让人工负责问题定义、技术边界、证据核对和最终交付。

## Selected work

### [Tunnel Fire Research](https://github.com/baoerger/tunnel-fire-research)

面向无风隧道顶棚纵向温度研究的 FDS 6.10.1 代码库。包含输入生成、版本与日志审计、HRR 和设备 CSV 检查、准稳态识别、统计分析、协议和测试。仓库公开研究代码与阶段性证据，不把未完成外算包装成最终结论。

### [Novel2Script](https://github.com/baoerger/novel-to-script)

全栈 LLM 应用：将中文小说转换为结构化、可编辑的剧本。七阶段流水线覆盖文本分片、逐章分析、跨章角色去重、关系图谱、场景生成、组装和质量报告；后端使用 FastAPI，前端使用 React/TypeScript，并提供 Docker Compose 启动方式。

### [Editable PPT Rebuilder](https://github.com/baoerger/editable-ppt-rebuilder)

把图片化的幻灯片重建为可编辑 PowerPoint。工作流将可读文字转为文本框、简单结构转为原生形状、复杂视觉保留为独立资产，并通过 OCR、ImageGen 视觉核心、裁剪审核和 PowerPoint 渲染验证形成交付闭环。

## Working principles

- 先定义每页或每个实验真正要回答的问题，再选择表达方式。
- 把自动生成当作候选和加速工具，不把未经核对的输出当作证据。
- 保留中间结果、来源、审计记录和失败状态，让结果可以复查。
- 对示意数据、研究阶段性结果和最终结论明确区分。

## Technical focus

`Python` · `FDS` · `FastAPI` · `React` · `TypeScript` · `LLM applications` · `PowerPoint automation` · `OCR` · `scientific computing`

## Repository curation

主页优先展示当前仍在维护、能够体现完整工程能力的项目。早期练习、实验仓库和第三方 fork 已从主要展示路径中移除或归档。

