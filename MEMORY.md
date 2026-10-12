# MEMORY.md

<!-- Your curated long-term memory: durable facts, preferences, and commitments. Keep it tight: promote what lasts here, and leave raw day-to-day detail in your daily notes. Detail by LifeOS category lives in ~/memory/categories/; one page per client in ~/memory/clients/. -->

## Facts
- Signature image on file: `~/workspace/user/assets/signature-samuel-cook.png` (imported 2026-09-29; sha256 ff5aea9c…) — stamp it on letters he asks to sign, not typed-only.
- Sam — full legal name Samuel Patrick Newton Cook (DOB 1 Feb 1978; one export lists Aug 30, 1978 — treat Feb 1 as the formal-memo figure, verify if it matters).
- Belfast-born; dual British/American national; holds a UK passport; 13 years in the U.S. Army — West Point graduate, taught Russian History there; combat tours in Iraq — adjutant to H.R. McMaster at Tal Afar, troop commander in the surge under Petraeus; wrote the 3rd Cavalry Regiment unit history and an Armor Magazine article ("The German Breakthrough at Sedan") as Captain.
- Lives in Kyiv, Ukraine (~8 years, as of an unknown date); wife is Kateryna (Ukrainian); young daughter (~born Oct 2025). U.S. ties: Austin TX, Washington DC, Houston TX.
- He organizes his businesses in Story OS (workspace "Borderlands Group").
- Entities: The Borderlands Group, Inc. (Virginia S-corp — defense BD and strategic advisory), The Borderlands Foundation (U.S. 501(c)(3), EIN 88-1118730 — Ukraine veterans support, plus a Ukrainian charitable foundation Фундація «Бордерлендс» Україна; Borderlands Foundation UK Ltd in progress), James Cook Media (Founder), Digital Purse Technologies/StoryPages (SaaS, Delaware File No. 7224306), James Cook Holdings (Houston S-corp, EIN 92-3809494), Ukraine Military History Institute (Founder & Executive Director). Ex-HE360 Ukraine Country Director (still doing contractor BD work for them).
- StoryFunnels co-founded with Tyron Dizon (CPO, 10+ years together) and Jake Alim (CTO — one 2025 pitch deck renders the surname "Marvin"; verify); prior startup SanityDesk ($1.6M ARR via LA Tech Stars, lost 2022, Chapter 11→7).
- Hermes is another AI he uses (self-hosted; iMac primary / MacBook Air mobile / EC2 orchestrator; Slack @hermes runs on the iMac (single instance); WhatsApp via Baileys).
- Air Littoral: $20,000 landed 2026-09-28; $7,500 deferred balance due 25 Oct still open.
- His Gmail and Google Calendar are connected to Muse.
- Cronometer is the single nutrition/activity log — Sam logs meals himself; Muse runs the judge-and-refine pass for his one-tap confirm; fixes applied via browser on his go-ahead. Meal-photo-logger cron disabled. (Playbook: Nutrition QA Claude project.)
- Emails in use: samuel.cook@jamescookmedia.com, PPC@jamescookmedia.com, samuel.cook@theborderlandsgroup.com, sa*****@borderlands.com.ua, samuelpncook@gmail.com, samuel.cook@charityspurse.net, sam@jamescookmedia.com. US WhatsApp on his email signature: +1 929 231 9954.
- AI accounts: OpenAI/Codex + Claude Personal Max under samuel.cook@jamescookmedia.com; ChatGPT Pro under sam@jamescookmedia.com; charityspurse.net workspace on Free. **Muse app/desktop agent account: samuel.cook@theborderlandsgroup.com** (confirmed 2026-10-07).
- Assistant: Anastasiia Loktionova ("Anastasiia"; Sam says "Anastasia"), +380 95 795 7515, anastasiia.loktionova@jamescookmedia.com — tasks via WhatsApp. Signs as herself on his behalf; prefers plain numbered task lists; her private Claude project "Anastasiia - DON'T TOUCH" is walled off — don't dig there.
- Ievgeniy Krasovytskiy (also rendered Ievgen Krasovytskyi), +380503444559, ievgen.krasovytskyi@jamescookmedia.com — runs the media agency; every task delegated to him must also be entered in StoryOS assigned to him.
- Vova Kuzyara, mobile +380 93 188 4578 — runs operations for the Borderlands Group.
- Tyron Dizon, mobile +63 917 110 0338 — StoryFunnels CPO/co-founder.
- Anupreet "Anu" Amole — partner at Eversheds Sutherland (UK); pro bono counsel on the Neil Drysdale fraud case; handles finance/tax (UK VAT refund, holding-structure advice).
- LifeOS named sub-agents: the finance trio (CFO, Contracts, Invoicing); agent soul + memory files (Adjutant, Claude, Architect, Shield) live in `~/workspace/lifeos-agents/`.

## Memory by category
- [ASU Coursework](~/memory/categories/asu-coursework.md), [Borderlands Group Ops](~/memory/categories/borderlands-group-ops.md), [Borderlands Foundation](~/memory/categories/borderlands-foundation.md), [UMHI Podcast](~/memory/categories/umhi-podcast.md), [Finance & Money](~/memory/categories/finance-money.md), [Tech & Security](~/memory/categories/tech-security.md), [STR Properties](~/memory/categories/str-properties.md), [James Cook Media](~/memory/categories/james-cook-media.md), [Personal & Admin](~/memory/categories/personal-admin.md), [Index](~/memory/categories/INDEX.md)

## Clients
One page per confirmed client: [~/memory/clients/INDEX.md]

## Preferences
- Task boards (standing, 2026-10-10): every board must ship with working categories (add/rename/deactivate) — same for goals; never ship fixture categories.
- Urgent pings / reminders (standing 2026-10-07): ping his Signal Note to Self (`sam-ping` skill), never WhatsApp; `bin/wa-ping` retired for reminders; WhatsApp bridge still banned for anyone else.
- Task presentation: LifeOS review board-card format — one card at a time, never a full list; next card after he decides. On Delegate he names the delegatee — ask "who should own this?", never pick. (Asked 2026-09-27.)
- Delegate flow (standing, 2026-10-10): Sam picks one of his people or enters someone new; when email/WhatsApp are missing, the delegation stays staged and Muse asks him in chat; nothing ever sends from the board itself.
- When presenting a decision, always lead with your own recommendation — never just lay out options without saying which step you'd take. (Asked 2026-09-28.)
- Autonomous execution bias (Claude export 2026-09-28, "Just take over"): when a path exists within the AI's own tools, do the work directly; route only atomic human-only steps (secret pastes, payments, physical actions) back to him.
- He hates being routed to the browser (2026-02-09) — route agentic web work to Claude/subagents instead.
- Calendar: confirmed external commitments go on the calendar immediately, no asking first ("You always need to update my calendar", 2026-09-28). AI-generated filler stays approval-only via the nightly brief.
- Code and infra work goes to Claude Code sessions (terminal/install/test/GitHub/Supabase); the AI then code-reviews with an honest verdict (what shipped, how built, verified vs claimed). (Claude export 2026-09-28.)
- Cost: pay for good work over saving tokens — default to the stronger model for judgment/architecture/security; cheaper only for provably mechanical tasks. Flat-rate runtimes (Codex) preferred where quality is equal. (Claude export 2026-09-28).
- Marketing honesty: never inflate claims — no untrue registration numbers, no unverified video claims, strip claims he can't promise. (Claude export 2026-09-28.)
- Outbound voice (standing, 2026-09-29): every message sent on Sam's behalf (Signal, WhatsApp, SMS, email) follows `~/workspace/skills/sam-voice/SKILL.md`. Email: short, direct, transactional; signs "Sam"; two variants per task (Anastasia / Sam). Memos use his memo writing style, not email voice (Claude export 2026-09-28). Never overrides the "Send it" rule.
- Reply-here flow (standing, 2026-09-29): Sam answers Signal, WhatsApp, and email from the Muse chat when he hasn't answered natively — every reply is teed up here first (channel, recipient, full exact text) for one-tap approval. Signal via `signal-send`, email via the gmail skill, WhatsApp via wa.me links. WhatsApp NEVER sends via the Hermes bridge.
- Email reply pipeline (standing, 2026-10-10): Claude drafts replies from LifeOS memory in Sam's voice (email-voice skill); Sam reviews/edits in the drafting tool. Nothing sends without his literal "Send it".
- LifeOS sync architecture (standing, 2026-10-10): Muse, Claude, and ChatGPT sync via GitHub + Supabase; Muse (Hercules) maintains it (memory → Supabase, code/skills → GitHub); Claude does architecture/implementation. Gateway v2 live.
- Writing rules: no labeled structure ("First/Second", title headers announcing points); open on the substance; Chicago notes-bibliography with real narrow-range footnotes; Strunk & White brevity; never fabricate quotes/details. (Claude export 2026-09-28.)
- Documentation integrity: nothing backdated — documents dated the day the counterparty issued them; reconstructions labeled as reconstructions; no one signs/dates a form for someone else. Anastasiia drafts/researches/preps; Sam alone submits, signs, authorizes bank connections, agrees to terms. (Claude export 2026-09-28.)
- GitHub is the source of truth: every AI-session artifact ends up in GitHub, not local staging (secrets excepted — never pushed). (Claude export 2026-09-28.)
- Scheduled routines auto-approve within remit; genuine judgment calls, anything health/clinical, and scope/cost trade-offs come back to him via push. (Claude export 2026-09-28.)
- Chat routing (standing 2026-10-09): all health items stay in the Daily health side chat, never moved out; health raised in the main chat gets moved there; non-health never lands in the health chat. Whatever Muse handles or finds in another channel, also surface in the main chat. Don't re-post the Vernius/BG-140 finance copy in the health chat.
- AI deep-work routing (Sam delegated to Muse): Claude Personal Max = primary engine; JCM Team workspace = overflow; ChatGPT Pro = fast questions/brainstorming; Codex = coding; Hermes = private/local + always-on iMac jobs.
- Delegation doctrine (standing 2026-10-11): every brief to Claude/ChatGPT is a Borys Harness — destination + acceptance criteria, self-verifying loop, correction edge max 3, Hercules approves only the last step. Karpathy additions: few-shot input→output examples for repeated task types; route by difficulty (ChatGPT fast / Claude deep / Codex code). Templates: `~/workspace/fleet/delegation-harness-doctrine.md`.
- Two-model check (standing 2026-10-11): big problems — anything Sam will see, pay for, send, or decide on — get builder + independent verifier with a pass/fail verdict on independent evidence; disagreement goes back through the correction edge; micro-tasks get harness self-verification only.
- Fleet review runs daily ~08:23.
- Travel flights (standing, 2026-10-11): holds United (MileagePlus) + American programs; buys coach, bids up to business where the airline allows it (United has no bid program — instant cash upgrades or gate buy-ups only); every comparison checks Starlink WiFi; one travel skill covers all flight search/booking.

## Health framework (Sam's Claude VITALS chats — read in depth 2026-09-27)
- Calories: cut 2,879 / maintenance 3,379 ± 90 kcal/day; energy balance over complete days only (intake + burn); true burn = Garmin total + SECA adjustment.
- Nutrition score ("7 levers") weights: calories 30%, protein 15%, sodium 15%, saturated fat 15%, added sugar 10%, alcohol 10%, fibre 5%.
- Daily goals: protein ≥180 g; saturated fat ≤10% of kcal (AHA 6–7% given his live cardiovascular risk); added sugar ≤36 g; sodium ≤2,300 mg; fibre ≥30 g. It's the saturated share that carries the LDL signal (swap butter/fatty red meat/cheese for olive oil, oily fish, nuts); added sugar is the cheapest deficit after alcohol.
- Blood pressure is the #1 issue ("unresolved BP gate"); sodium + alcohol are the two fastest levers on BP; flag when there are no recent cuff readings.
- Strength is the top gap after BP: target 3 strength sessions weekly; running doesn't build muscle (SECA shows no growth). Run polarised ~80% easy / 20% hard; perceived effort (legs, niggles in achilles/knee/hip, terrain, heat) is the key input no device captures.
- Sleep: compare Oura vs Garmin across day/7d/30d (hours, score, recovery, deep, REM, efficiency, HRV, resting HR); coach inputs: bedtime, alcohol, caffeine, wake-ups, room temp. ~1h38m/night shortfall vs 8h37m need (largest unaddressed health number). Genetics: caffeine slow-clearance (CYP1A2 AC) + high sensitivity (ADORA2A CT) — keep caffeine ~16 mg, before 10:00 only.
- ApoE E3/E4 (Sam stated 5 Oct 2026) — one E4 allele = elevated Alzheimer's risk; researching obicetrapib (his spelling "Obasetrapid"; CETP inhibitor; Alzheimer's signal is biomarker-stage only).
- Lipids/ApoB (Aug 2026): ApoB 0.64 g/L (from 0.98); LDL back in line; triglycerides halved; soluble fiber protocol (psyllium + beta-glucan).
- Homocysteine is the one blood test his genetics (MTHFR C677T one copy) justify; vitamin D already top-of-range, don't retest.
- Thyroid nodules under ACR observation (<1.0 cm; biopsy over 1.5 cm); calcitonin never measured.
- Track caffeine (flag unverified entries) and alcohol in grams + % of days.
- Supplement stack (started 2026-10-01): Blueprint creatine 5g/day; Blueprint Collagen Peptides 1 scoop/day (20g protein, ~70 kcal); проФЛЕКС (Schonen Fortigel collagen hydrolysate + vitamin C) 1 vial/day ≥3 months (~25–30g collagen/day total).
- Nightscout self-hosted on Fly.io (deployed 2026-10-05): https://sam-nightscout-2.fly.dev (API secret in `~/workspace/goals/daily-health-check-report/hidden_files/nightscout.json`, mode 600). LinX CGM on his arm since Oct 2; his Ukrainian phone stays the only LinX login.

## Standing rules
- Board: source of truth — the StoryOS "Inbox — to approve" view holds proposed tasks awaiting Sam's OK (separate from reviewed open tasks); never touch the board without his approval.
- Task tracking (standing, 2026-09-29): when Sam starts a task with Muse, add it to his tasks and keep it visible in every chat until finished.
- Money: never move money beyond exactly what Sam delegated; every new movement needs his explicit go-ahead; watch for fraud and deadlines — flag, don't freestyle; never resolve a financial-security flag unilaterally.
- Credentials: task-scoped and transient — never reused, repeated back, or stored in memory. Ask before any CAPTCHA/human-verification step. When checking auth, report status/identity/scopes/expiry only — never expose values; never hardcode bearer tokens in committed scripts (env var first, then root-owned mode-600 token file, else exit non-zero).
- Hermes may send email only with per-email approval (Sam authorized 2026-09-02).
- Delegation channels: Anastasia, Tyron — WhatsApp.
- Data-migration consent: never transfer his Signal message history to a relinked or new device without his explicit approval (Sam, 2026-09-29).
- WhatsApp monitoring: never scan his archived chats (Sam, 2026-10-02) — active chats only.
- Key-task reminders (standing, 2026-10-07): the nightly 21:00 planning review reminds him of key outstanding tasks and rolls anything not done into the next day — never dropped silently.
- Food logging routines (standing): every Cronometer food log sends Sam a check-in with that item's calories, macros, saturated fat and sodium, plus running day totals vs targets; the vitals-dashboard is refreshed with the day's deltas and the artifact card is presented; the day's eating is graded on each Roksolana daily report, with AI nutritionist comments + logging corrections; the Roksolana daily PDF carries trailing intake averages (7/14/30/60/90/180d) and per-device burn windows (Oura, Garmin native, SECA-adjusted), kept current by the morning job — Garmin history is thin (feed blocked), so Oura carries the trend; the reusable skill at `~/workspace/skills/food-log-triangulation/` triangulates meal photos + his comments through Claude and ChatGPT (scoring in `leaderboard.json`; triggers: 'triangulate the food log', 'audit my food logging', 'verify my calories'); timestamp-adjacent photos of the same dish are one serving, not separate servings — never double-count.

## Commitments
- Delegation hub sync LIVE (2026-10-10, cron `delegation-hub-sync` every 30m): agent runtime = gateway engine: GET /tasks → hub importtasks; hub outbox → POST /task-status → ack. Truncation guard: skip import if task count < half of last known.
- Daily Forge soul refinement (~08:00 Kiev): propose SOUL.md + MEMORY.md updates from BG ops signals; apply only after his acceptance; runs until he says the soul is right. (cron forge-soul-daily-refinement)
- Oura OAuth2 connected 2026-10-04; tokens in `~/.config/oura/credentials.json`; scopes: daily, heartrate, workout.
- Ongoing ops: manage his to-do list via Story OS + Hermes; stay signed in to TriDot and grade triathlon workouts as logged. iMac (samuels-imac-1) is primary (never sleeps, auto-restarts after power loss); MacBook Air fallback via `~/workspace/bin/hmba`. Open: Chrome View → Developer → 'Allow JavaScript from Apple Events' (GUI-only).
- Robotto: Dmitry Lugovoy (Head of R&D and Integration) starts 12 Oct 2026 — fee €7,000 (€3,500 paid, BG-2026-178 balance due 22 Oct; 90-day replacement guarantee from 12 Oct). Pay $4,500/mo probation → $5,000/mo; partial Oct 12–31 €3,416.69 (BG-2026-180) due 19 Oct. Position #2: €7,000 fee (BG-2026-179) due 14 Oct — SOW No. 2 must be signed in writing before the search begins.
- DeViro: Sam still has no Doodle rep agreement — his hard gate for helping.
- Scholar (ASU): two threads — school (soul+memory at workspace/lifeos-agents/scholar/) vs content drafting (articles/book/podcast). Academic probation Fall 2026; deadlines are Google Calendar markers; study blocks approval-only via nightly brief.
- ASU student-loan push (active 2026-09-28): check each submitted form's status via his email and ASU account; loop 19pine in.
- Foundation 2025 990: Sam's $10k/$12,500 2025 donation ruled out (verified 1 Oct); Schedule B to Jeremy: verifiable data only — Rogge $51k (amounts disputed), Pointer $7.5k; Randy's $5k refund excluded.

- 2FA codes (standing, 2026-10-04): prefer email (Muse pulls from Gmail); fallback SMS to +1 929 231 9954; if only 2229 is offered, call him by voice. Cronometer: email + password only, no 2FA (2026-10-06).
- Credit card statements (standing, 2026-10-04): forward every new statement for each monitored card to Akash (bookkeeper.akash@gmail.com) — standing send authorization.
- Wunder (Dr. Wunder / Mabon) proposed-task cards: suppress from the proposed-task flow unless they explicitly ask Sam to do something; route to Ievgen by default (set 2026-09-29).
- Deadline capture (standing, 2026-10-04): when Muse spots a likely deadline in any task, ask Sam whether to register it in the deadline-driver skill (daily check ~08:00 Kyiv).
- Default shipping address for ALL future shopping (2026-10-04): Samuel Cook, 27 Merry Lane NP001369560, East Hanover, New Jersey 07936, 1 (973) 947-6185. Skill `np-shopping-forwarding` declares warehouse-bound Gmail orders so they forward to Kyiv (login in Secure Vault); new logs get emailed to Anastasia — first draft comes back to Sam for approval.
- EmCell quarterly exams (standing, 2026-10-07): every 3 months after treatment (last: 2026-09-29); cron `emcell-quarterly-exam` (monthly on the 29th) checks the 90-day mark, pings him on Signal to pick a day, then helps book.
- Feed tab = health only (standing 2026-10-09): nothing but health stuff (nutrition, training, sleep, recovery, vitals, supplements); non-health units queued for deletion on his say-so.
- Operating order 2026-10-10 (Claude via Sam) — lane split: Hercules = COCKPIT (calendar, reminders, approvals capture, watchers, daily briefs, inbox/Signal/WhatsApp capture, travel/fares, card checks); Claude (Cowork + Claude Code) = ENGINE (thinking, building, verification, voice editors, 20:30 Kyiv nightly plan, hardening, all code). Two peers, Sam above both.
- LifeOS database access — GATEWAY ONLY: https://mdpekpilhtnskpbbtkbc.supabase.co/functions/v1/muse-gateway (Bearer MUSE_API_TOKEN; Sam pastes into Secure Vault himself, never in chat). NEVER ask for, store, or extract a Supabase service_role key or dashboard login; never attempt the Supabase dashboard. LifeOS memory does NOT live in the VITALS project.
- Every scheduled task POSTs a heartbeat at end of run as "muse:"+kebab-case id. A silent task is a failed task.
- GitHub: NEVER select samuelpncook/life-os in the Meta Muse GitHub app (two agents writing the same files is forbidden). Only samuelpncook/hercules-workspace; mirror SOUL.md, MEMORY.md, company.md, progress.md, AGENTS.md, os/* there daily.
