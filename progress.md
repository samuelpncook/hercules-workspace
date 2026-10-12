# Progress — Hercules workspace

_Mirror file for samuelpncook/hercules-workspace. Sam's thinking lives in files he owns._

## 2026-10-10 — Operating order adopted (Claude via Sam)
- Lane split: Hercules = COCKPIT (phone/WhatsApp surface: calendar, reminders, approvals capture, watchers, daily briefs, inbox/Signal/WhatsApp capture, travel/fares, card checks). Claude (Cowork + Claude Code) = ENGINE (thinking, building, verification, voice editors, 20:30 Kyiv nightly plan, hardening, all code). Two peers, Sam above both.
- Single record of truth: StoryOS board + LifeOS database. No second task list / memory / company graph only in this VM.
- LifeOS database access: gateway ONLY — https://mdpekpilhtnskpbbtkbc.supabase.co/functions/v1/muse-gateway (Bearer MUSE_API_TOKEN via secure store). Never Supabase dashboard, never service_role key.
- Every scheduled task heartbeats as `muse:<slug>` at end of run.
- GitHub: only samuelpncook/hercules-workspace (never life-os). Daily mirror of SOUL.md, MEMORY.md, company.md, progress.md, AGENTS.md, os/*.
- Delegation Hub: rebuilt as the Oct 4 hub — delegation-first hero view, Top priorities lane, urgency at a glance. Must remain a view over the LifeOS record, not a second task list.
- company.md: draft at ~/workspace/os/company.md; engine merges into canonical life-os company graph after Sam's approval.
