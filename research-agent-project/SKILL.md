---
name: research-agent-project
description: Manage continuity, requirements, architecture and evidence for multi-session research projects worked on by Codex or other agents. Use when coordinating a research project, recovering context, tracking changing requirements, experiments, handoffs or validating a research deliverable across stages. Do not impose a project management process on an isolated question or small edit.
---

# Research Agent Project

Keep the research objective, decisions, implementation, experiments and evidence connected across sessions. Adapt the amount of management to the task; deliver the user's requested work, not just a plan or documents. Obey the user's scope and the host's tool, delegation and approval rules.

## Establish current truth

1. Identify the immediate outcome, scope, constraints, acceptance criteria and available project root. Inspect the existing instructions, project records, code, configurations and relevant results before proposing changes. Reuse the project's existing record locations and conventions; do not create a parallel source of truth. Current user corrections take precedence over stale notes; investigate conflicts with actual artifacts.
2. For sustained work, maintain a concise project record in an existing suitable location or a task-owned `research-project/` folder. Use [project-record.md](references/project-record.md) for a scalable structure. Record only what is needed to resume and verify: objective, requirements, decisions, architecture boundaries, active work, evidence, unresolved issues and next action. A small task may need no new file.
3. Record material requirement changes and their affected design, implementation, tests and conclusions. Give significant requirements stable identifiers when tracing prevents omissions. An unverified document is a claim, not proof of code behavior. Do not invent decisions or fill scientific gaps as facts.

## Execute and verify

- For a change with material cross-module effects, map responsibilities, interfaces, data flow, invariants and affected downstream artifacts before implementation. Keep design proportional and revise it as evidence changes. Use [research-evidence.md](references/research-evidence.md) when planning or interpreting experiments.
- Break work into coherent outcomes with dependencies and observable acceptance checks. Proceed with authorized independent work while a real blocker is unresolved. Do not pause after every step or ask about routine implementation choices.
- Match verification to the risk: inspect actual outputs, run meaningful targeted checks, and trace important requirements through implementation and evidence. Record what ran, result, artifact/version and limitations. Failed or unrun checks stay visible; a successful command alone does not establish scientific validity.
- Update the canonical record when a decision changes, a result is obtained, a handoff is needed or the task ends. Do not create a diary entry for every action. If documentation and implementation disagree, investigate and fix the appropriate one; don't automatically overwrite either.
- Use independent review or another agent only when it adds value and is available and authorized. Give a reviewer the task, evidence and constraints without supplying a desired verdict. Integrate findings and resolve material issues. No model choice, arbitrary context percentage or universal peer-review gate guarantees correctness.

## Resume and hand off

Before a long session ends, context is compacted, or work changes hands, update the project record with the objective, active constraints, artifact paths and versions, completed and pending work, validation results, unresolved risks and exact next action. On resumption, inspect the record and affected artifacts; reconcile changed state before rerunning experiments or side effects. Do not assume compaction preserves every requirement or that a handoff record reflects current reality.

Report the requested result first, then material evidence, limitations and next action. Separate proposed work, completed work and verified results; never imply an experiment ran or a scientific claim was established without evidence.

