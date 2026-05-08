# Contributing

This skill gets better with every recovered account whose owner contributes back. The framework was built from real case patterns; the platform addendums need real-world updates as policies change.

If this skill helped you recover an account, the most useful thing you can do is contribute back to make it work for the next person.

---

## Quick links

- [Adding a new platform](#adding-a-new-platform) — the highest-impact contribution
- [Updating an existing platform](#updating-an-existing-platform)
- [Documenting a success story](#documenting-a-success-story)
- [Construction-brief improvements](#construction-brief-improvements)
- [Translations and non-US adaptations](#translations-and-non-us-adaptations)
- [Reporting a problem](#reporting-a-problem)

---

## Adding a new platform

The platform addendum is the single most useful contribution. Each platform has its own organizational gaps, escalation paths, and known patterns — and those are what make the difference between framework and actionable skill for that platform.

To add a new platform:

1. Copy `platforms/_template.md` to `platforms/[platform-name].md` (lowercase, hyphens, no spaces)
2. Fill in every section (see the template for what's required)
3. Verify every URL and email address is current at time of contribution (include the date you verified)
4. Cite sources for any claim about the platform's policies, organizational structure, or known patterns
5. Add the platform to the README's supported-platforms list
6. Add the platform to `STATUS.md` with appropriate confidence level (`draft` for new contributions, `verified` only after independent peer review)
7. Submit a PR

**What makes a good platform addendum:**

- **Verified, dated information.** Every URL and address should have a "verified [date]" note. Platform support URLs change frequently.
- **Specific organizational gaps.** Generic "support is bad" is unhelpful. "The Trust & Safety team handles bans, the Account team handles logins, neither handles cases stuck between the two" is the kind of insight that makes the skill work.
- **Documented patterns.** If there's a known pattern of failure (a class of account being targeted, a specific type of ToS misapplication, a recurring billing issue), cite public sources documenting the pattern.
- **Cited precedents.** If a regulatory action has been taken against the platform (state AG suit, FTC consent decree, class action settlement), cite it.
- **Realistic expectations.** Don't oversell what works. If a particular tactic has a low success rate, say so.

**What makes a bad platform addendum:**

- Speculation presented as fact
- Tips for circumventing legitimate platform decisions
- Identifying information about specific employees by name
- Personal grievances dressed up as policy descriptions

---

## Updating an existing platform

Platforms change their policies, support URLs, and organizational structure regularly. If you discover that something in an existing addendum is out of date:

1. Open a PR with the correction
2. Include a citation for the new information (link to the platform's current page, or a dated screenshot if the page changed in a way that wasn't captured publicly)
3. Update the "last verified" date in the addendum

**Common things that go stale:**
- Support ticket form URLs
- Legal-notices email addresses
- Special-status escalation channels (when programs are renamed or restructured)
- Server transfer / asset preservation criteria
- Restoration windows (often unofficial, may shift)

---

## Documenting a success story

If the skill worked for you, please consider contributing an anonymized success story. These build social proof for future readers and help refine the framework.

Add to `precedents.md` in this format:

```markdown
### [Platform], [Year], [Brief scenario type]

- Initial issue: [1 sentence]
- Time stuck in standard support: [duration]
- Stages used: [which of 0-5 you ran]
- What worked: [the specific channel that produced the resolution]
- Time from that channel to resolution: [duration]
- Final outcome: [what you got back]
```

**What we don't include:**
- Your name, location, or any identifying details
- The platform's specific employees by name
- Anyone else's identifying information
- Details specific enough to identify you to the platform

**What we do include:**
- Anonymized facts that help future readers calibrate expectations
- The pattern of which channel produced the result
- The time-to-resolution at each stage

---

## Construction-brief improvements

The construction briefs in `/templates/` are not fill-in-the-blank templates. They are briefs that tell Claude (or any reader) what each document needs to do, what always goes in, what varies by case scenario, what good looks like with worked examples, and what to avoid. If you've used one and found it could be sharper, more comprehensive, or more accurate, PRs welcome.

**Construction-brief improvement principles:**

- **Stay platform-agnostic in the brief itself.** Platform-specific details (legal entity names, mailing addresses, support URLs) belong in `platforms/{platform}.md` addendums, not in the briefs. Briefs should be written so that any platform addendum can be plugged in.
- **Add scenario-specific guidance** if you've recovered from a less-common case shape (impersonation, billing dispute, lockout-without-explanation) and have insight into what works.
- **Add or improve the "what good looks like" examples.** Worked examples are the most valuable part of a brief — they show what variance looks like in practice. New examples that demonstrate genuinely different cases (different industries, different scenarios, different harm types) make the brief usable across more situations.
- **Note character limits where applicable.** Some intake forms have caps (state AG forms typically cap narratives at 3,500–5,000 characters). Briefs should call out where the constructed document needs to fit a specific limit.
- **Don't smuggle in legal advice.** Briefs guide the construction of factual documents. They never name legal theories, statutes, or causes of action — those are the attorney's domain. If you're tempted to add a "this is a [legal theory] case" framing, don't.

---

## Translations and non-US adaptations

The framework's Stage 3 (regulatory pressure) is US-specific. The other stages translate to other jurisdictions, but the regulatory mechanisms differ.

If you're adapting this for another country:

1. Create a `regions/[country-code].md` file with your country's equivalents
2. Document the consumer protection regulator, data protection authority, telecommunications ombudsman, or other equivalent
3. Note any platform-specific local addresses (e.g., Discord Netherlands B.V. for EU/EEA users)
4. Translate the README and FRAMEWORK if you're contributing in a non-English language — keep filenames in English (`README.es.md` for Spanish, `FRAMEWORK.de.md` for German, etc.)

Submit as a PR with the country/language clearly marked.

---

## Reporting a problem

If something in the skill is wrong, harmful, or missing in a way that hurt your case:

1. **Open an issue** with the title `[problem]: brief description`
2. Include: which file, what's wrong, what should be there instead, what the impact was
3. Be specific. "The Discord addendum is wrong" is unhelpful. "The Discord addendum lists `legal@discord.com` but the correct address per Discord's MSA is `legal.notices@discord.com`, and a letter sent to the wrong address bounced and lost me 5 days" is actionable.

---

## What we don't accept

- **Tactics for circumventing legitimate platform decisions.** This isn't a how-to-evade-bans guide.
- **Tools or services that cost money.** No paid-service recommendations beyond attorneys, who must be vetted neutrally.
- **Identifying information about platform employees, regulators, or individual case participants.** Anonymize everything.
- **Promotional content for any business or service.** This includes attorneys — listing law firms is allowed, but only as "documented examples that take this kind of case" with no editorial endorsement.
- **Platform-bashing or political commentary.** The skill is about practical recovery, not opinions on Big Tech.
- **Legal advice.** Templates are starting points. Anything claiming to be definitive legal guidance gets rejected — we link to attorneys instead.

---

## Code of conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). The short version: this is a guide for people in vulnerable situations. Treat contributors and users with respect.

---

## Maintainers

This is a community-maintained project. PRs reviewed on best-effort basis. Substantial changes (new platforms, framework changes) reviewed within ~7 days; small fixes (link updates, typo corrections) usually within 2–3 days.

If you submit a PR and don't hear back within 14 days, ping in a comment. Sometimes notifications get missed.
