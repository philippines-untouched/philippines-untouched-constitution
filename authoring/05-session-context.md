# Session Context

**Version:** 49 — Handoff record
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
- `constitution/16-decision-framework.md` — **Chapter 16 — Decision Framework, RATIFIED** (Entry 021). The structured process for evaluating significant business decisions.
- `constitution/17-organisational-design.md` — **Chapter 17 — Organisational Design, RATIFIED** (Entry 022). The Company as an integrated system rather than independent departments.
- `constitution/18-information-integrity.md` — **Chapter 18 — Information Integrity, RATIFIED** (Entry 023). Information as a strategic asset requiring accuracy, security and permanence.
- `constitution/19-risk-governance.md` — **Chapter 19 — Risk Governance, RATIFIED** (Entry 024). Risk understood, managed and balanced against opportunity. **Part III (Governance) complete.**
- `constitution/20-long-term-strategy.md` — **Chapter 20 — Long-Term Strategy, RATIFIED** (Entry 025). Direction measured in decades rather than years. First chapter of Part IV (Strategy).
- `constitution/21-market-strategy.md` — **Chapter 21 — Market Strategy, RATIFIED** (Entry 026). Competing through quality, trust and authenticity in the premium segment.
- `constitution/22-growth-strategy.md` — **Chapter 22 — Growth Strategy, RATIFIED** (Entry 027). Sustainable expansion without compromising the Company's principles.
- `constitution/23-innovation-strategy.md` — **Chapter 23 — Innovation Strategy, RATIFIED** (Entry 028). Innovation solves meaningful problems rather than creating unnecessary complexity.
- `constitution/24-international-strategy.md` — **Chapter 24 — International Strategy, RATIFIED** (Entry 029). Export aspirations and commitment to international standards. **Part IV (Strategy) complete.**
- `constitution/25-operational-excellence.md` — **Chapter 25 — Operational Excellence, RATIFIED** (Entry 030). Efficient, consistent and scalable operations. First chapter of Part V (Operations).
- `constitution/26-agricultural-philosophy.md` — **Chapter 26 — Agricultural Philosophy, RATIFIED** (Entry 031). Farming decisions supporting quality, sustainability and long-term land stewardship.
- `constitution/27-manufacturing-philosophy.md` — **Chapter 27 — Manufacturing Philosophy, RATIFIED** (Entry 032). Principles governing food production and value-added manufacturing.
- `constitution/28-supply-chain-philosophy.md` — **Chapter 28 — Supply Chain Philosophy, RATIFIED** (Entry 033). Suppliers and logistics partners as extensions of the Company's values.
- `constitution/29-continuous-improvement.md` — **Chapter 29 — Continuous Improvement, RATIFIED** (Entry 034). Incremental improvement throughout the organisation. **Part V (Operations) complete.**
- `constitution/30-quality-management.md` — **Chapter 30 — Quality Management, RATIFIED** (Entry 035). Quality as the Company's primary competitive advantage. First chapter of Part VI (Quality).
- `constitution/31-food-safety.md` — **Chapter 31 — Food Safety, RATIFIED** (Entry 036). Food safety as a non-negotiable responsibility.
- `constitution/32-global-gap.md` — **Chapter 32 — GLOBAL G.A.P. IFA Smart V6, RATIFIED** (Entry 037). Internationally recognised certification as part of the Company's strategic direction.
- `constitution/33-traceability.md` — **Chapter 33 — Traceability, RATIFIED** (Entry 038). Complete product traceability from origin to customer as a core organisational capability.
- `constitution/34-assurance-audit.md` — **Chapter 34 — Assurance & Audit, RATIFIED** (Entry 039). Verification, auditing and continual assessment strengthen trust. **Part VI (Quality) complete.**
- `constitution/35-corporate-reputation.md` — **Chapter 35 — Corporate Reputation, RATIFIED** (Entry 040). Reputation as one of the Company's most valuable long-term assets. First chapter of Part VII (Brand).
- `constitution/36-brand-architecture.md` — **Chapter 36 — Brand Architecture, RATIFIED** (Entry 041). Every brand relates to the Company directly; no brand is subordinate to another.
- `constitution/37-customer-trust.md` — **Chapter 37 — Customer Trust, RATIFIED** (Entry 042). How trust is earned, maintained and protected. **Part VII (Brand) complete.**
- `constitution/38-technology-philosophy.md` — **Chapter 38 — Technology Philosophy, RATIFIED** (Entry 043). Technology as an enabler of quality, efficiency and organisational learning. First chapter of Part VIII (Technology).
- `constitution/39-digital-transformation.md` — **Chapter 39 — Digital Transformation, RATIFIED** (Entry 044). Digital systems support decision making without replacing human judgement.
- `constitution/40-automation.md` — **Chapter 40 — Automation, RATIFIED** (Entry 045). When automation is embraced and when human expertise remains essential.
- `constitution/41-organisational-memory.md` — **Chapter 41 — Organisational Memory, RATIFIED** (Entry 046). The keystone chapter — how the Company captures and preserves knowledge for future generations. **Part VIII (Technology) complete.**
- `constitution/42-sustainable-development.md` — **Chapter 42 — Sustainable Development, RATIFIED** (Entry 047). Balancing environmental, social and economic outcomes. First chapter of Part IX (Sustainability).
- `constitution/43-climate-resilience.md` — **Chapter 43 — Climate Resilience, RATIFIED** (Entry 048). Preparing for environmental change while protecting long-term productivity.
- `constitution/44-resource-stewardship.md` — **Chapter 44 — Resource Stewardship, RATIFIED** (Entry 049). Responsible management of land, water, energy and materials. **Part IX (Sustainability) complete.**
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
25. **Chapter 16 — Decision Framework** — ratified. Recorded as Decision Log Entry 021.
26. **Chapter 17 — Organisational Design** — ratified. Recorded as Decision Log Entry 022.
27. **Chapter 18 — Information Integrity** — ratified. Recorded as Decision Log Entry 023.
28. **Chapter 19 — Risk Governance** — ratified, completing Part III. Recorded as Decision Log Entry 024.
29. **Chapter 20 — Long-Term Strategy** — ratified, first chapter of Part IV. Recorded as Decision Log Entry 025.
30. **Chapter 21 — Market Strategy** — ratified. Recorded as Decision Log Entry 026.
31. **Chapter 22 — Growth Strategy** — ratified. Recorded as Decision Log Entry 027.
32. **Chapter 23 — Innovation Strategy** — ratified. Recorded as Decision Log Entry 028.
33. **Chapter 24 — International Strategy** — ratified, completing Part IV. Recorded as Decision Log Entry 029.
34. **Chapter 25 — Operational Excellence** — ratified, first chapter of Part V. Recorded as Decision Log Entry 030.
35. **Chapter 26 — Agricultural Philosophy** — ratified. Recorded as Decision Log Entry 031.
36. **Chapter 27 — Manufacturing Philosophy** — ratified. Recorded as Decision Log Entry 032.
37. **Chapter 28 — Supply Chain Philosophy** — ratified. Recorded as Decision Log Entry 033.
38. **Chapter 29 — Continuous Improvement** — ratified, completing Part V. Recorded as Decision Log Entry 034.
39. **Chapter 30 — Quality Management** — ratified, first chapter of Part VI. Recorded as Decision Log Entry 035.
40. **Chapter 31 — Food Safety** — ratified. Recorded as Decision Log Entry 036.
41. **Chapter 32 — GLOBAL G.A.P. IFA Smart V6** — ratified. Recorded as Decision Log Entry 037.
42. **Chapter 33 — Traceability** — ratified. Recorded as Decision Log Entry 038.
43. **Chapter 34 — Assurance & Audit** — ratified, completing Part VI. Recorded as Decision Log Entry 039.
44. **Chapter 35 — Corporate Reputation** — ratified, first chapter of Part VII. Recorded as Decision Log Entry 040.
45. **Chapter 36 — Brand Architecture** — ratified. Recorded as Decision Log Entry 041. (Refined during drafting: no brand is a reference point for another; all relate to the Company.)
46. **Chapter 37 — Customer Trust** — ratified, completing Part VII. Recorded as Decision Log Entry 042.
47. **Chapter 38 — Technology Philosophy** — ratified, first chapter of Part VIII. Recorded as Decision Log Entry 043.
48. **Chapter 39 — Digital Transformation** — ratified. Recorded as Decision Log Entry 044.
49. **Chapter 40 — Automation** — ratified. Recorded as Decision Log Entry 045.
50. **Chapter 41 — Organisational Memory** — ratified, the keystone chapter, completing Part VIII. Recorded as Decision Log Entry 046.
51. **Chapter 42 — Sustainable Development** — ratified, first chapter of Part IX. Recorded as Decision Log Entry 047.
52. **Chapter 43 — Climate Resilience** — ratified. Recorded as Decision Log Entry 048.
53. **Chapter 44 — Resource Stewardship** — ratified, completing Part IX. Recorded as Decision Log Entry 049.

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
   — **IN PROGRESS**: Chapters 1–5, 7–44 ratified (Entries 007–049). **Parts II–IX complete.** Chapter 6 — Company Identity drafted but **held as local draft**: needs TIN, registration numbers and corporate address (all currently unknown) from the owner before ratification. Next after Chapter 6: Chapter 45 — Financial Philosophy (Part X).

---

## 8. How to Resume

1. Read this file (done).
2. Read `authoring/00-authoring-principles.md` (ratified v1.0) — the binding authoring framework.
3. Read `authoring/01-table-of-contents.md` (ratified v1.0) — the definitive chapter structure.
4. Read `authoring/02-style-guide.md` (ratified v1.0) — the binding style conventions.
5. Read `authoring/04-decision-log.md` (entries 001–049) — the recorded decisions and their reasons.
6. For any chapter work: consult the private brief in the farm repo (paths in §4) — it is the reasoning authority.
7. Refer to the open items in §7 and proceed in order.
---

*This note is a working record, not a constitutional document. It may be updated by future sessions as the authoring progresses.*
