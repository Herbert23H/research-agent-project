# Research Agent Project

面向 Codex 等支持 `SKILL.md` 的 Agent 的科研项目管理 Skill。它帮助长期项目追踪需求、架构边界、实验与证据，并在跨会话交接时恢复工作状态。

## 使用

将 `research-agent-project/` 目录复制到支持技能发现的环境中。例如 Codex 用户级技能目录 `~/.codex/skills/`，然后按环境的技能加载方式重新发现技能。也可在对话中明确要求使用 `research-agent-project`。

适合多阶段科研、跨会话交接、需求变更和实验结果追踪。独立小问题不需要建立项目文档；已有项目应复用现有记录。Skill 不执行实验、不保证模型正确，也不绕过宿主的授权规则。

示例：“使用 research-agent-project 检查当前实验项目，梳理需求、代码和结果的对应关系，然后继续完成尚未验证的基线。”

## 设计来源与边界

灵感来自[小红书讨论](https://www.xiaohongshu.com/explore/6ae02948000000001601aa54)和用户提供的评论摘要，重点是持久化需求、模块职责和跨会话交接。原帖评论未被完整核读；不将评论中的固定上下文百分比、模型路由推测或强制每步审批视为事实或通用要求。科研证据和复现记录是针对本 Skill 用途的扩展。参考了本地 `ccf-pipeline-orchestrator` 的证据门槛和连续性思路；本 Skill 可独立使用。

