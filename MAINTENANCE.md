# Maintenance Policy

This skill is only useful if its information is current. Stale information — wrong contact emails, dead URLs, outdated regulatory pathways — sends users in distress to dead ends or, worse, to scammers who register expired support addresses.

This document defines how the skill is maintained, how readers can tell whether what they're reading is fresh, and what happens if maintenance lapses.

---

## Freshness markers

Every platform addendum in `platforms/` carries a `last-verified` date in its YAML front-matter:

```yaml
---
last-verified: 2026-05-06
verified-by: <github-handle-or-anonymous>
notes: <what was verified — links, contact addresses, procedures>
---
```

The freshness markers also live in `STATUS.md` at the repo root, which contains a freshness table summarizing every platform's last-verified date and confidence level at a glance. When Claude (using this skill) reads a platform addendum and finds `last-verified` more than 180 days old, the skill instructs Claude to warn the user that information may be stale.

---

## Verification cadence

**Quarterly review (every 90 days):**

For each platform addendum, a maintainer or contributor checks:

1. Every URL in the addendum still resolves and points to the documented page (not a redirect to an unrelated landing page).
2. The legal-notices email address is still listed on the platform's official site.
3. The headquarters address is still current.
4. The state of incorporation and legal entity name are still correct.
5. Any documented procedural details (e.g., "Discord requires email-only contact for compromised accounts") still match the platform's current policy.

If any item is wrong, the addendum is updated and `last-verified` advances. If no items are wrong, `last-verified` advances anyway as a confirmation timestamp.

**Annual deeper review:**

Once per year, beyond the URL/contact check:

1. Stage 3 regulatory pathways are re-validated. State AG portals reorganize. The FTC's primary intake URL has changed before. CFPB scope has changed before. These are checked.
2. Templates are reviewed for language drift. Legal-notice conventions evolve.
3. The `using-ai-to-build-your-case.md` privacy guidance is checked against current AI provider data-retention policies.

---

## Stale-warning behavior

**`> 180 days since last-verified`:** the platform addendum should be flagged in `STATUS.md` and the skill (`SKILL.md`) instructs Claude to warn users that information may be stale. Recommended banner text in addendum or SKILL guidance:

> ⚠ This addendum hasn't been verified in over 6 months. Information may be stale. Verify any URLs, email addresses, or procedures against the platform's current website before relying on them.

**`> 365 days since last-verified`:** treat as red severity in `STATUS.md`. Skill should give a stronger warning:

> ⚠ This addendum hasn't been verified in over a year. Treat all platform-specific details as potentially incorrect. Cross-check everything against the platform's current site before sending anything.

**`> 540 days since last-verified` AND no maintainer activity:** the addendum is moved to `platforms/_archived/` and removed from the active set referenced by `SKILL.md`. The repo continues to host the framework, but stops claiming the addendum is usable.

---

## Sunset clause

This is an open-source project maintained on a best-effort basis. If maintenance lapses, the skill should sunset gracefully rather than mislead users.

**If no commits to the main branch occur for 12 months:** the next contributor or fork-maintainer should add a deprecation notice to the top of the README:

```
> ⚠ This skill has not been actively maintained since [DATE]. The framework remains broadly correct, but platform-specific details are likely stale. Use the framework as a guide; verify all platform contacts, URLs, and procedures against current sources before relying on them.
```

**If no commits for 24 months:** the project should be archived on GitHub. The README should redirect users to active forks (if any).

The framework itself ages well. The platform-specific details and regulatory URLs do not.

---

## Contributor responsibilities

If you submit a PR for a platform addendum:

1. Update the `last-verified` field to today's date.
2. List in the PR description what you actually verified (URLs clicked, email tested, addresses checked).
3. If you couldn't verify a particular detail, leave it as-is and note that in the PR.

If you submit a PR for templates, the framework, or `SKILL.md`:

1. Note in the PR whether your change affects platform-specific details. If yes, the affected addendums need fresh verification.
2. If your change affects the AI-prompt instructions in `SKILL.md` or the standalone `using-ai-to-build-your-case.md` guide, note whether you tested the new instructions against an actual Claude session for hallucination behavior, particularly around the never-name-legal-theories and never-invent-facts rules.

---

## For forkers

If you fork this repo to your own GitHub username or organization, one place needs a username swap:

**README.md** — the `[your-username]` placeholder near the top, used in references to the forked repo URL.

Find it quickly:

```
grep -rn "chrispirillo\|your-username" .
```

Replace with your handle, commit, push.

---

## Known maintenance debt

Maintainers should record outstanding items here as they're identified:

- *(none recorded yet)*

---

## Reporting stale information

If you find a stale URL, dead contact, or outdated procedure: open an issue tagged `freshness`. If it's urgent (a contact email now goes to a squatter, for example), tag the issue `urgent` and the maintainers will treat it as a priority fix.
