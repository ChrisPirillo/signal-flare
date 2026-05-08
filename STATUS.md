# Status

This page summarizes the freshness and verification confidence of every platform addendum and major component in the skill. See `MAINTENANCE.md` for what these markers mean and how the project is maintained.

**Project version:** v0.1 (experimental — see notice in `README.md`)

**Last freshness review:** 2026-05-06

---

## Platform addendums

| Platform | Last verified | Confidence | Notes |
|---|---|---|---|
| Discord | 2026-05-06 | Verified | Most thoroughly researched addendum. Includes Yellow Fellows precedent and Zendesk breach context. |
| Meta (Facebook / Instagram / Threads) | 2026-05-06 | Verified | Second most thorough. Covers all three Meta-owned platforms. |
| PayPal | 2026-05-06 | Verified | Includes CFPB pathway as a financial-services platform. |
| Google / YouTube | 2026-05-06 | Draft | Initial research; not independently verified. |
| X (Twitter) | 2026-05-06 | Draft | Recovery procedures evolve frequently on X. Verify before relying on details. |
| TikTok | 2026-05-06 | Draft | Initial research; not independently verified. |
| Twitch | 2026-05-06 | Draft | Initial research; not independently verified. |
| LinkedIn | 2026-05-06 | Draft | Initial research; not independently verified. |
| Snapchat | 2026-05-06 | Draft | Initial research; not independently verified. |
| Reddit | 2026-05-06 | Draft | Initial research; not independently verified. |
| Roblox | 2026-05-06 | Draft | Initial research; not independently verified. |
| Steam | 2026-05-06 | Draft | Excludes scenarios B and E by design. |

**Confidence definitions:**
- **Verified** — actively researched and reviewed by a maintainer with experience using the recovery channels for this platform.
- **Draft** — initial research only. Core framework should still apply; platform-specific details (URLs, contact emails, procedural quirks) need independent verification before users rely on them.

---

## Framework components

| Component | Last reviewed | Notes |
|---|---|---|
| `FRAMEWORK.md` (5-stage escalation framework) | 2026-05-06 | Core framework. Aging behavior: slow — the regulatory mechanisms (state AGs, FTC, congressional offices) are stable. Update on annual review. |
| `decision-tree.md` | 2026-05-06 | Routes 5 scenarios to tactics. Stable. |
| `templates/*.md` (8 templates) | 2026-05-06 | Verified language and structure. Subject to legal-conventions drift over years. |
| `using-ai-to-build-your-case.md` | 2026-05-06 | AI provider data-retention policies change. Re-validate annually. |
| `regions/README.md` | 2026-05-06 | Placeholder. No regional adaptations contributed yet. |
| `precedents.md` | 2026-05-06 | Empty schema awaiting community contributions. |

---

## Outstanding maintenance items

- Deepen the 9 draft-confidence platform addendums with maintainers who have current recovery experience on each platform.
- Add at least one regional adaptation (EU/UK most useful first).
- Add real anonymized precedents from successful community recoveries.
- Wire the link-check workflow's output to issue creation.
- Add example user-Claude conversations to the README showing the skill in action.

If you want to claim an item, open an issue or PR.
