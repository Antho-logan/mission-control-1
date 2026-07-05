# AGENT RULES

> Binding for every AI agent operating in this vault or its repos: Codex, ChatGPT, Claude, Hermes, and any future agent.
> Violating these rules = the work is invalid, regardless of quality.

---

## Startup Sequence (Mandatory)

1. Read [[LIFE_OS]] — mission, principles, hard limits.
2. Read [[CURRENT_STATE]] — current truth, blockers, "what not to touch".
3. Read the file(s) relevant to your task (project file, TRADING, CODING, etc.).
4. Only then start working.

## File Rules

- **Never overwrite important files without a report.** Before modifying [[LIFE_OS]], [[CURRENT_STATE]], [[DECISION_LOG]], or any dashboard: write an entry in [[AGENT_REPORTS]] stating what you're about to change and why.
- **Write changes clearly.** State what changed in the file's log/notes section or the report. No silent edits.
- **Use small diffs.** Touch the minimum lines needed. Never reformat or reorganize a file as a side effect.
- **Append-only files stay append-only:** [[DECISION_LOG]], [[AGENT_REPORTS]], [[HEALTH_LOG]], daily logs. Add, never edit or delete.
- **Never create giant catch-all files.** Use the existing modular structure. New file creation needs a reason written in your report.
- **Deletions:** never delete — move to `99_ARCHIVE/` and note it in your report.

## Reporting (Mandatory)

- After ANY work session, append an entry to [[AGENT_REPORTS]] using its template.
- The report must **list risks** created or discovered.
- The report must **list decisions needed from G** — anything you weren't sure about goes here, not into a guess.

## Honesty Rules

- **Do not invent progress.** "I attempted X and it failed" is a valid report. "Done" when it isn't is not.
- **Do not hide uncertainty.** Mark confidence explicitly: certain / likely / guessing.
- **Do not fabricate data, metrics, or sources.** No source = say "no source".
- If you cannot complete a task, say exactly where you stopped and why.

## Hard Limits (Human Confirmation Required)

These ALWAYS require G's explicit confirmation — an agent may prepare, research, and draft, but never execute:

| Domain | Agent may | Agent may NOT |
|---|---|---|
| Health | research, organize, flag risks, draft doctor questions | approve/start/dose any peptide, prescription, injection, or intervention → tag `⚠️ REQUIRES MEDICAL REVIEW` |
| Trading | review journals, flag rule breaks, analyze stats | signal entries, size positions, change rules |
| Money | analyze burn/revenue, flag waste | move, spend, or commit money |
| Publishing | draft content | publish anything externally |
| Vault | edit per file rules above | delete files, rewrite control files |

## Escalation

When blocked or uncertain:
1. Write the question under "Needs G decision" in your [[AGENT_REPORTS]] entry.
2. If urgent, also add it to "Decisions Needed From G" in [[CURRENT_STATE]].
3. Stop rather than guess on anything touching the hard limits.
