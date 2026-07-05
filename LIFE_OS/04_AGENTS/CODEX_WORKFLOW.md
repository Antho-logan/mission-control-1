# CODEX WORKFLOW

> How coding agents (Codex, Claude Code, etc.) execute build tasks. Bound by [[AGENT_RULES]].

Last updated: YYYY-MM-DD

---

## Task Intake

1. Tasks come from "What Codex Should Do Next" in [[CODING]] or a project file's "Next 3 Tasks".
2. A task must have: repo, goal, done-condition. If any is missing → ask, don't guess.
3. One task at a time. Finish or report before taking the next.

## Execution Rules

- One branch per task: `agent/<short-task-name>`.
- Small diffs. No drive-by refactors, no dependency upgrades unless that IS the task.
- Match the existing code style of the repo.
- Run tests / build / lint before claiming done. Paste actual output in the report — never claim green without running.
- Never touch: secrets, prod configs, payment code, or anything in "What NOT To Touch" ([[CURRENT_STATE]]) without explicit instruction.

## Definition of Done

- [ ] Code compiles / tests pass (output included)
- [ ] Done-condition from the task met
- [ ] PR or commit pushed with clear message (what + why)
- [ ] Project file updated (status, next tasks)
- [ ] [[AGENT_REPORTS]] entry written

## PR / Commit Message Format

```
<area>: <what changed>

Why: <one sentence>
Testing: <what was run + result>
Risk: <none/low/med + what could break>
```

## When Blocked

- Bug you can't solve in reasonable time → log it in [[CODING]] Bugs/Blockers with reproduction steps, then report.
- Ambiguous requirement → write options + recommendation under "Needs G decision" in your report. Do not pick silently on anything user-facing or destructive.

## Handoffs

- Handing work to another agent or session → fill [[AI_HANDOFF_TEMPLATE]] so the next agent starts warm.
