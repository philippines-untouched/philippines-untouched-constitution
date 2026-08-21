# Session Context

**Version:** 20 — Handoff record
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
- `authoring/03-glossary.md` — **working draft v0.1** (local only, deliberately NOT committed until all chapters reach v1 — new terms may emerge during editing and ratification).
- `README.md` — **approved by owner, committed** (commit `ef6ab14`).
- `LICENSE.md` — **CC BY-ND 4.0** (ratified). Recorded as Decision Log Entry 002.
- `constitution/00-front-matter.md` — **migrated from private farm repo** (Entry 006). Contains 0.1 Cover Page, 0.2 Document Control, 0.3 Revision History. Copyright updated to CC BY-ND 4.0. Sections 0.4–0.6 not yet drafted.
- `constitution/01-purpose.md` — **Chapter 1 — Purpose, RATIFIED** (Entry 007). The first substantive chapter; establishes the Company's reason for existing beyond financial success.
- `constitution/02-vision.md` — **Chapter 2 — Vision, RATIFIED** (Entry 008). Describes what the Company ultimately seeks to become.
- `constitution/03-mission.md` — **Chapter 3 — Mission, RATIFIED** (Entry 009). Defines what the Company does every day to achieve its Vision.
- `constitution/04-core-values.md` — **Chapter 4 — Core Values, RATIFIED** (Entry 010). Integrity, Quality, Stewardship, Trust, Excellence — the standard of conduct for every person acting on behalf of the Company.
- `constitution/05-founding-principles.md` — **Chapter 5 — Founding Principles, RATIFIED** (Entry 011). The thirteen non-negotiable principles from which every corporate decision shall flow.
- `constitution/07-stewardship.md` — **Chapter 7 — Stewardship, RATIFIED** (Entry 012). The Company as steward — of land, people, the Company and knowledge. First chapter of Part II (Philosophy).
- `constitution/08-quality-before-profit.md` — **Chapter 8 — Quality Before Profit, RATIFIED** (Entry 013). Quality shall ALWAYS be considered ahead of profit.
- `constitution/09-trust-through-evidence.md` — **Chapter 9 — Trust Through Evidence, RATIFIED** (Entry 014). Accurate information, traceability and evidence-based decision making as foundations of trust.
- `constitution/10-people-grow-prosperity.md` — **Chapter 10 — People Grow Prosperity, RATIFIED** (Entry 015). Investing in people creates enduring business success.
- `constitution/11-community-prosperity.md` — **Chapter 11 — Community Prosperity, RATIFIED** (Entry 016). Shared prosperity, not charity; capability, not dependency.
- `constitution/12-environmental-responsibility.md` — **Chapter 12 — Environmental Responsibility, RATIFIED** (Entry 017). Protection of biodiversity, natural resources and ecological health.
- `constitution/13-knowledge-education.md` — **Chapter 13 — Knowledge & Education, RATIFIED** (Entry 018). Continual learning, agricultural education and knowledge sharing. **Part II (Philosophy) complete.**
- `constitution/14-governance-framework.md` — **Chapter 14 — Governance Framework, RATIFIED** (Entry 019). Authority, accountability and responsibility. First chapter of Part III (Governance).
- `constitution/15-ethical-leadership.md` — **Chapter 15 — Ethical Leadership, RATIFIED** (Entry 020). The standards of integrity expected from all leaders.
- `constitution/06-company-identity.md` — **Chapter 6 — Company Identity: LOCAL DRAFT, not committed.** Awaiting TIN, registration numbers and corporate address (all currently unknown).

---

## 4. Private Authoring Context (where the reasoning lives)

The authoring brief, planning notes and private deliberations live in the **farm repository (private)** at:

- `~/projects/farm/documents/Corporate Governance & Strategy Manual Brief.md` — the 46-section authoring brief; the complete reasoning foundation. **Private**: contains personal and strategic material (ownership structure, family considerations, unratified working phrases). Do not copy into this public repo.
- `~/projects/farm/documents/Corporate-Governance-&-Strategy Manual-TOC.md` — the refined Table of Contents (11 parts, 50 chapters, 4 appendices; supersedes the brief's 51-chapter proposal; author's note names Chapter 41 — Organisational Memory — as the keystone chapter).
- `~/projects/farm/Corporate Governance & Strategy Manual.md` — original Part 0 draft, now **migrated** to `constitution/00-front-matter.md` in this public repo (Entry 006).

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
9. **Front Matter migration** — Part 0 draft moved from private farm repo to `constitution/00-front-matter.md` with CC BY-ND 4.0 copyright. Recorded as Decision Log Entry 006.
10. **README** — approved by the owner; describes purpose, structure, license, status and institutional authorship.
11. **Chapter 1 — Purpose** — ratified as the first substantive chapter. Recorded as Decision Log Entry 007.
12. **Chapter 2 — Vision** — ratified. Recorded as Decision Log Entry 008.
13. **Chapter 3 — Mission** — ratified. Recorded as Decision Log Entry 009.
14. **Chapter 4 — Core Values** — ratified. Recorded as Decision Log Entry 010.
15. **Chapter 5 — Founding Principles** — the thirteen proposed principles ratified as drafted. Recorded as Decision Log Entry 011. (Resolves the earlier open question: ratify now, amend later via formal process.)
16. **Chapter 7 — Stewardship** — ratified, first chapter of Part II. Recorded as Decision Log Entry 012.
17. **Chapter 8 — Quality Before Profit** — ratified. Recorded as Decision Log Entry 013.
18. **Chapter 9 — Trust Through Evidence** — ratified. Recorded as Decision Log Entry 014.
19. **Chapter 10 — People Grow Prosperity** — ratified. Recorded as Decision Log Entry 015.
20. **Chapter 11 — Community Prosperity** — ratified. Recorded as Decision Log Entry 016.
21. **Chapter 12 — Environmental Responsibility** — ratified. Recorded as Decision Log Entry 017.
22. **Chapter 13 — Knowledge & Education** — ratified, completing Part II. Recorded as Decision Log Entry 018.
23. **Chapter 14 — Governance Framework** — ratified, first chapter of Part III. Recorded as Decision Log Entry 019.
24. **Chapter 15 — Ethical Leadership** — ratified. Recorded as Decision Log Entry 020.

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
   — **RESOLVED**: Ratified now as Chapter 5 (Entry 011). Future changes go through the formal amendment process.
3. **Authoring principles: ratifiable or advisory?** — *ratifiable*; the constitution's rulebook binds as strongly as the constitution. Ratified via Entry 003.
   — **RESOLVED**
4. **Table of Contents** — agree the refined 50-chapter TOC from the farm repo and install it as `authoring/01-table-of-contents.md`.
   — **RESOLVED**: Ratified as v1.0 (Entry 004).
5. **Style guide** (`02`) — language, register ("shall" constitutional voice), heading conventions, quoting rules.
   — **RESOLVED**: Ratified as v1.0 (Entry 005).
6. **Glossary** (`03`) — **working draft v0.1 created locally; intentionally uncommitted.** Will accumulate terms during chapter drafting and be ratified after all chapters reach v1.
7. **README** — content to be agreed.
   — **RESOLVED**: Approved and committed (`ef6ab14`).
8. **Migrate the Part 0 draft** from the farm repo into `constitution/` once the foundation is agreed.
   — **RESOLVED**: Migrated as `constitution/00-front-matter.md` (Entry 006).
9. **Then chapters** — beginning with Chapter 1 — Purpose, working through the agreed TOC.
   — **IN PROGRESS**: Chapters 1–5, 7–15 ratified (Entries 007–020). **Part II (Philosophy) complete.** Chapter 6 — Company Identity drafted but **held as local draft**: needs TIN, registration numbers and corporate address (all currently unknown) from the owner before ratification. Next after Chapter 6: Chapter 16 — Decision Framework (Part III).

---

## 8. How to Resume

1. Read this file (done).
2. Read `authoring/00-authoring-principles.md` (ratified v1.0) — the binding authoring framework.
3. Read `authoring/01-table-of-contents.md` (ratified v1.0) — the definitive chapter structure.
4. Read `authoring/02-style-guide.md` (ratified v1.0) — the binding style conventions.
5. Read `authoring/04-decision-log.md` (entries 001–020) — the recorded decisions and their reasons.
6. For any chapter work: consult the private brief in the farm repo (paths in §4) — it is the reasoning authority.
7. Refer to the open items in §7 and proceed in order.
---

*This note is a working record, not a constitutional document. It may be updated by future sessions as the authoring progresses.*
