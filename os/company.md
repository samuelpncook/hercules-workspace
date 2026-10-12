# company.md — Sam Cook / LifeOS company graph

Draft v1 — 2026-10-10. Built from the one-person company prompt (`one-person-company-prompt.md`).
Status: **draft, awaiting founder approval** before it becomes the operating graph.

## Inputs

- **Company:** Samuel P. N. Cook — sole founder/operator. Entities: James Cook Holdings (mothership), James Cook Media, StoryPages / Digital Purse Technologies, Borderlands Group (VA S-corp), Borderlands Foundation (501c3 + UK + UA), UMHI.
- **Product and customer:** Defense BD + strategic advisory (BG), SaaS (StoryPages), media (JCM), veterans support (Foundation).
- **Weekly goals:** the StoryOS board + goal workspaces under `~/workspace/goals/`. Source of truth, never touched without founder approval.
- **Tools and accounts:** Muse (Hercules, operator), Claude Personal Max (deep work), Claude JCM Team workspace (overflow), ChatGPT Pro (fast questions), Codex (coding), Hermes self-hosted (private/local, iMac). Gmail + Google Calendar connected. Cronometer, Oura API, Apple HealthKit.
- **Spend limit:** founder approves every money movement — "Send it", literal words, no exceptions.
- **Run limit:** weekly review each Sunday; evening planning review 21:00 Kiev daily.

## Nodes (function → owner → output → check)

| Node | Owner (engine/agent) | Output | Check |
|---|---|---|---|
| finance-ar | Invoicing + Contracts + Claude | Invoices, registers (`ar-aging.md`) | Numbering verified vs 48h Gmail SENT sweep; register is single authority |
| finance-tax | CFO + Jeremy + Akash | Filings, 990, schedules | Submitted + counterparty confirmed |
| money-watch | code node (cron) | money-release-queue.md | One card per new staged send; never sends |
| bd-sales | Forge + Ira (BG) | Proposals, intros, LOIs | Logged; founder approved before send |
| content-media | Signal + Ievgen (JCM) | Posts, assets, campaigns | Marketing honesty; founder "Send it" |
| research | Claude / ChatGPT | Briefs, audits | Sourced; evidence linked |
| build | Codex + Tyron/Jake | Shipped code, skills | Code-reviewed by operator; verified vs claimed |
| health | VITALS loop | Daily brief (health side chat) | Numbers from primary sources only |
| ops-admin | Adjutant + Anastasiia | Calendar, inbox, travel | Confirmed external commitments on calendar immediately |
| legal | Shield + Randy + Anu | Contracts, filings | Counsel reviewed |

## Edges (a node consumes another's output)

- research → content-media, research → bd-sales
- bd-sales → legal → finance-ar (proposal → contract → invoice)
- finance-ar → finance-tax (registers feed filings)
- build → content-media (StoryPages tools feed Foundation/JCM)
- ops-admin → all (calendar/inbox routing)

Parallel (no edges): health, money-watch vs the rest.

## Code nodes (deterministic — never a model call)

- Invoice numbering + 48h Gmail SENT sweep
- Money-release queue watcher (hourly)
- Flight status watch (per-leg cadence)
- iMac heartbeat watch (15 min)
- Cronometer judge-and-refine math
- Dedupe/count/sort jobs

Bookkeeping never routes through a subagent.

## Permissions (enforced, not prose)

- Founder approval ("Send it", literal) before spending, publishing, emailing, or sending any external message.
- One writer per file/account: the invoice register, money queue, and memory files have a single owning node.
- Recoverable version before any bulk change (backups, git).
- Credentials task-scoped and transient; never stored in memory.

## Gates

Every node output passes a gate before it reaches the founder: deterministic checks first, the node's report second, model confidence last. Verdicts: pass / fail / unresolved — evidence linked, missing evidence left visible. A gate is never weakened to obtain a pass.

## Return paths

- **Correction edge:** failed gate → back to the node with reason + evidence + scope "fix this node only". Max 3 attempts, then it surfaces to the founder.
- **Learning edge:** every accepted correction becomes a rule in `~/AGENTS.md` or memory, so next week starts from it.

## Weekly review (Sundays) + daily (21:00 Kiev)

Each goal becomes a checklist item pointing to observable evidence: output exists and opens, gate ran against the saved version, spend inside limits, company.md matches the nodes that actually ran. Partial status names the exact nodes left when a blocker stops the run.

## Founder queue

Board cards — one at a time, never a list. Recommendation first. On Delegate, the founder names the owner; never pre-assigned.
