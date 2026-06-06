# lihouwenbin

I build protocol-first AI workflows for red-team review, recursive
self-improvement governance, and open-source maintenance.

My current focus is making agent-assisted work more auditable: separate the
builder from the reviewer, preserve failed attempts, block unresolved vetoes,
and keep human approval at important boundaries.

## Current Project

[ai-redteam-recursive-self-improvement](https://github.com/lihouwenbin/ai-redteam-recursive-self-improvement)
is a domain-neutral framework for governing recursive self-improvement loops in
AI-assisted projects.

It includes:

- structured improvement rounds
- implementation and research red-team checks
- promotion-gate decision records
- JSON round evaluation through `rsi-evaluate`
- tests and examples for reproducible review

## Open Source Maintenance Style

I like maintenance PRs that are:

- objective and easy to review
- backed by tests or clear validation
- scoped to one concrete issue
- respectful of maintainers' project boundaries
- focused on regression tests, documentation/API consistency, CI, and small bug fixes

## Interests

- AI safety and evaluation
- red-team workflows for agentic systems
- Codex-assisted open-source maintenance
- reproducible decision records
- protocol design for human-in-the-loop automation

## Contact

GitHub is the best place to reach me for open-source work.

## 中文简介

我关注的是把 AI agent 的工作变得更可审计、更可复现，也更不容易自我说服。

现在主要在做：

- AI 红队工作流
- 递归自我改进的治理框架
- Codex 辅助的开源维护
- 人类审批边界下的 agent 自动化
- 可复现的决策记录和失败保留机制

我的核心想法很简单：agent 可以帮助我们更快地实现和审查，但不能让同一个角色同时负责提出方案、实现方案、解释结果并批准升级。好的递归改进流程应该把 builder、reviewer、red-team 和 human approval 分开。

## 开源维护风格

我更喜欢做小到中等规模、客观、可验证的维护 PR：

- 用测试或清晰的验证命令支撑改动
- 围绕一个明确问题收敛
- 尊重项目维护者已有边界
- 不做主观润色或无意义重构
- 优先修复测试、CI、文档/API 一致性和小 bug

当前主项目：

[ai-redteam-recursive-self-improvement](https://github.com/lihouwenbin/ai-redteam-recursive-self-improvement)

这是一个通用的 AI 红队递归自我改进框架，用来记录 improvement round、red-team finding、promotion gate 和 decision record。
