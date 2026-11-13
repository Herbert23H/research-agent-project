# Project record and traceability

Reuse the project's existing files. If no suitable record exists and continuity warrants one, a short `research-project/PROJECT.md` can hold the following; split only when size or ownership makes it useful. Do not overwrite existing user material. Relative links should resolve from the record.

- **Goal and scope:** research question, desired output, exclusions, constraints and acceptance criteria.
- **Requirements:** stable ID, source/decision, current statement, acceptance check and status for important requirements. Link affected design, code and evidence. Mark unknown, proposed, implemented and verified distinctly.
- **Architecture:** modules and responsibilities, interfaces and data contracts (units, shapes, coordinate frames and semantics when relevant), dependencies, invariants and prohibited coupling. Link to owning files rather than copying large inventories.
- **Decisions and changes:** date, decision, rationale, affected artifacts and superseded assumptions. Record consequential changes; keep one current statement alongside history.
- **Work and evidence:** stage, owner, actual paths or version identifiers, results, checks, failures and outstanding dependencies. Link logs and outputs; avoid embedding private credentials or copying data unnecessarily.
- **Handoff:** current state, open questions, blockers, exact next action, and what must be rechecked on resume.

For requirement changes, identify affected code, configurations, datasets, experiments, documents and claims. Update the canonical requirement and relevant artifacts within the authorized task; mark anything not yet updated. Preserve unrelated user changes. For a long or risky project, trace a small set of high-impact requirements end to end and record the evidence of each check.

