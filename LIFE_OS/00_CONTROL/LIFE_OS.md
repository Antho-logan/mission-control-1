# LIFE OS — Master Control File

> Read this file first. Every human and AI agent operating in this vault starts here.
> Then read [[CURRENT_STATE]] before doing anything.

Last updated: YYYY-MM-DD

---

## Mission

Build a lean, healthy, long-lived body and a profitable, increasingly automated business portfolio — with AI agents taking over more operational work every quarter, while G keeps final authority on health, money, and strategy.

## Life Pillars

| Pillar | Definition | Dashboard |
|---|---|---|
| HEALTH | Nutrition, training, longevity, getting lean, risk avoidance, carefully reviewed peptide research | [[HEALTH_DASHBOARD]] |
| WORK | Coding, trading, organic marketing, B2B SaaS, B2C iOS apps, AI agents, project execution | [[WORK_DASHBOARD]] |

## Non-Negotiables

- [ ] Sleep is protected. No project is worth chronic sleep debt.
- [ ] Training happens on schedule unless injured or sick.
- [ ] No unreviewed medical interventions. Ever.
- [ ] Trading risk rules are never overridden mid-trade.
- [ ] Weekly review happens every week, even a short one.
- [ ] CURRENT_STATE.md is kept truthful — no aspirational fiction.

## Operating Principles

1. **One source of truth.** State lives in [[CURRENT_STATE]]. Logs are append-only. Dashboards summarize; they don't hold unique data.
2. **Small, reversible moves.** Small diffs in code, small position sizes in trading, small dose-of-change in health.
3. **Measure before optimizing.** No intervention without a baseline metric.
4. **Ship > polish.** Revenue and data beat perfect systems.
5. **Automate the repeatable.** Anything done 3+ times manually becomes an agent task or script.
6. **Cut ruthlessly.** Weekly review must name at least one thing to cut or pause when overloaded.
7. **Continuity over cleverness.** Write so any AI model (Codex, ChatGPT, Claude, Hermes) can pick up cold and continue.

## What AI Agents ARE Allowed To Do

- Read every file in this vault.
- Research, summarize, and organize information (health, trading, marketing, code).
- Draft content, code, plans, and experiments.
- Update logs, dashboards, and project files with clearly-marked changes.
- Flag risks, inconsistencies, and stale data.
- Propose next actions and prioritize backlogs.
- Execute coding tasks in repos following [[CODEX_WORKFLOW]].

## What AI Agents Are NOT Allowed To Do

- Approve or recommend starting any peptide, prescription, injection, or medical intervention. They may only research and flag `⚠️ REQUIRES MEDICAL REVIEW`.
- Place, size, or close trades, or change trading rules. Analysis only.
- Move, spend, or commit money.
- Delete files or overwrite [[LIFE_OS]], [[CURRENT_STATE]], or [[DECISION_LOG]] without writing an entry in [[AGENT_REPORTS]] first.
- Invent progress, fabricate metrics, or hide uncertainty.
- Publish content externally (social, email, app releases) without G's confirmation.

## Weekly Review Rules

- Every week, complete [[WEEKLY_REVIEW]] (template in that file).
- Update [[CURRENT_STATE]] immediately after the review.
- Log any decision made in [[DECISION_LOG]].
- If a review is skipped, the first task of the next session is completing it.

## Health Safety Rules

1. AI can research, organize, and flag risks. AI cannot approve medical experiments.
2. Any peptide, prescription, injection, or serious intervention gets the tag `⚠️ REQUIRES MEDICAL REVIEW` and an entry in [[PEPTIDES_RESEARCH]] or [[LONGEVITY]] with sources.
3. New symptoms that are severe, persistent, or unusual → log in [[HEALTH_LOG]] and add a doctor question in [[BLOODWORK_AND_METRICS]].
4. Cutting weight: max sustainable deficit, no crash protocols, no stacking multiple new interventions at once.
5. One variable at a time when experimenting, with a defined start date, metric, and review date.

## Trading Safety Rules

1. Risk per trade is fixed in [[TRADING]] and never raised after losses.
2. No trade without a written setup type that exists in the playbook.
3. Daily loss limit hit → stop trading for the day, log it, walk away.
4. Every trade gets a journal entry. No entry = the trade shouldn't exist.
5. AI reviews journals and flags rule breaks; AI never signals live entries.

## Work Execution Rules

1. Max 2 projects in "active build" at once. The rest are maintained or paused — status lives in each project file.
2. Every project file lists next 3 tasks. If it can't, the project is stalled — flag it.
3. Blockers get written down the moment they appear, in the project file and [[CURRENT_STATE]].
4. Marketing runs as experiments with a hypothesis, metric, and end date — see [[MARKETING]].
5. Every work session ends with logs updated (daily log + relevant project file).

---

## Vault Map

| Folder | Purpose |
|---|---|
| `00_CONTROL/` | Mission, current truth, reviews, decisions, AI briefing |
| `01_HEALTH/` | Health dashboards, templates, research, logs |
| `02_WORK/` | Coding, trading, marketing, sales, money |
| `03_PROJECTS/` | One file per product/project |
| `04_AGENTS/` | Rules, workflows, and reports for AI agents |
| `05_DAILY_LOGS/` | Daily log template + dated daily logs |
| `99_ARCHIVE/` | Dead projects, old logs, superseded files |
