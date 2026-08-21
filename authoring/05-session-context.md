# Session Context

**Version:** 4 — Handoff record
**Purpose:** Restore full authoring context for any session that picks up this project after the founding session. Read this file, then the documents it references, to resume work.

---

## 1. The Project

Philippines Untouched OPC is being established as a long-term agricultural and food manufacturing enterprise in the Philippines. Its principal consumer brand is **PUM**. This repository produces its **Corporate Governance & Strategy Manual** — a constitutional document, deliberately more substantial than a business plan, from which all other corporate documents derive authority.

**North star:** *What kind of organisation should Philippines Untouched be if it is still operating successfully after the founder is gone?*

---

## 2. Repositories

| Repository | Visibility | Role |
|---|---|---|
| `philippines-untouched/philippines-untouched-constitution` (this repo) | Public | The Manual and its authoring framework. Public because the Company is accountable to the principles it publishes. |
| `philippines-untouched/farm` | Private | The Company's software platform repo (GAP/presence/store services). Also holds the **private authoring context** (see §4). |
| slnk (planned) | Private | Link infrastructure platform; to be created under `philippines-untouched` when work begins. |

**Git identity for this repo:** `Philippines Untouched OPC <319225737+philippines-untouched@users.noreply.github.com>` (institutional — the Company, not any individual, is the author of record).

---

## 3. Current State

- Repository created (public), initial skeleton committed (`6749d3c`, branch `main`).
- `authoring/00-authoring-principles.md` — **v1.0 RATIFIED** (Entry 003). The authoring foundation is formally established.
- `authoring/04-decision-log.md` — seeded with **Entry 001** (provenance of authoring context). The log's format is established; subsequent decisions are appended.
- `authoring/01-table-of-contents.md` — **v1.0 RATIFIED** (Entry 004). 50 chapters across 11 Parts, 4 Appendices, 6 Front Matter sections.
- `authoring/02-style-guide.md` — **v1.0 RATIFIED** (Entry 005). Constitutional register, voice, "shall" usage, capitalisation, International English, and conventions.
- `authoring/03-glossary.md` — still a stub; content to be agreed.
- `README.md` — still a stub; content to be agreed.
- `LICENSE.md` — **CC BY-ND 4.0** (ratified). Recorded as Decision Log Entry 002.
- `constitution/` — empty, awaiting migration of the Manual content.

---

## 4. Private Authoring Context (where the reasoning lives)

The authoring brief, planning notes and private deliberations live in the **farm repository (private)** at:

- `~/projects/farm/documents/Corporate Governance & Strategy Manual Brief.md` — the 46-section authoring brief; the complete reasoning foundation. **Private**: contains personal and strategic material (ownership structure, family considerations, unratified working phrases). Do not copy into this public repo.
- `~/projects/farm/documents/Corporate-Governance-&-Strategy Manual-TOC.md` — the refined Table of Contents (11 parts, 50 chapters, 4 appendices; supersedes the brief's 51-chapter proposal; author's note names Chapter 41 — Organisational Memory — as the keystone chapter).
- `~/projects/farm/Corporate Governance & Strategy Manual.md` — existing Part 0 draft (0.1 Cover, 0.2 Document Control, 0.3 Revision History), written in the constitutional voice; to be migrated into `constitution/` when the foundation is agreed.

The public repo points to the fact that private context exists; the private repo holds the substance.

---

## 5. Decisions Already Made

1. **Public constitution repo** — the document is never intended to be secret; the Company should be accountable to its published principles.
2. **Institutional authorship** — commits carry the Company's name, not an individual's.
3. **Provenance split** — reasoning stays private (farm repo); the Manual and authoring framework are public (this repo). Recorded as Decision Log Entry 001.
4. **Foundation before chapters** — no substantive chapters until the authoring foundation is agreed (per the brief's working method).
5. **One bite at a time** — the authoring proceeds chapter by chapter, deliberately.
6. **CC BY-ND 4.0 license** — the Constitution is freely shareable with attribution but may not be altered by third parties. Recorded as Decision Log Entry 002.
7. **Table of Contents** — 50 chapters across 11 Parts, adopted from the refined farm TOC. Recorded as Decision Log Entry 004.
8. **Style Guide** — constitutional register, positive voice, "shall" usage, International English. Recorded as Decision Log Entry 005.

---

## 6. Authoring Discipline (summary of `00-authoring-principles.md`)

- The **Company** is always the subject — never the founder, family, or any individual.
- **Timeless, principle-based, strategic** — not procedural, not a brochure, not a biography.
- **No comparisons** with other organisations; **positive voice**; no marketing exaggeration; no clichés.
- **Evidence over assertion** — certification/achievements are strategic objectives until formally obtained.
- **The future leader test** — a future CEO who never met the founder must understand the document unaided.
- **Definition of Done** — eleven acceptance criteria per chapter (see §8 of the principles).
- **Formal amendment only** — no silent change; no version destroyed or concealed.

---

## 7. Open Items and Pending Decisions

1. **Review of `00-authoring-principles.md`** — the owner's reaction may adjust structure, wording, or voice before ratification. This is the immediate next step.
   — **RESOLVED**: Ratified as v1.0 (Entry 003).
2. **Ratify the 13 proposed Founding Principles now, or after chapters?** — lean: *after* — let the principles emerge from the chapters and be ratified against them, so the final list is earned rather than imposed. (Owner's call.)
3. **Authoring principles: ratifiable or advisory?** — *ratifiable*; the constitution's rulebook binds as strongly as the constitution. Ratified via Entry 003.
   — **RESOLVED**
4. **Table of Contents** — agree the refined 50-chapter TOC from the farm repo and install it as `authoring/01-table-of-contents.md`.
   — **RESOLVED**: Ratified as v1.0 (Entry 004).
5. **Style guide** (`02`) — language, register ("shall" constitutional voice), heading conventions, quoting rules.
   — **RESOLVED**: Ratified as v1.0 (Entry 005).
6. **Glossary** (`03`) — key terms: Constitution, Company, PUM, GLOBAL G.A.P., stewardship, etc.
7. **README** — content to be agreed.
8. **Migrate the Part 0 draft** from the farm repo into `constitution/` once the foundation is agreed.
9. **Then chapters** — beginning with Chapter 1 — Purpose, working through the agreed TOC.

---

## 8. How to Resume

1. Read this file (done).
2. Read `authoring/00-authoring-principles.md` (ratified v1.0) — the binding authoring framework.
3. Read `authoring/01-table-of-contents.md` (ratified v1.0) — the definitive chapter structure.
4. Read `authoring/02-style-guide.md` (ratified v1.0) — the binding style conventions.
5. Read `authoring/04-decision-log.md` (entries 001–005) — the recorded decisions and their reasons.
6. For any chapter work: consult the private brief in the farm repo (paths in §4) — it is the reasoning authority.
7. Refer to the open items in §7 and proceed in order.

---

*This note is a working record, not a constitutional document. It may be updated by future sessions as the authoring progresses.*
