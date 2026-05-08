# Signal Flare — Account Recovery Skill for Claude

> ℹ **Status: v0.1 (experimental).** This skill is in active early development. The framework is sound; platform-specific details vary in maturity (see [STATUS.md](STATUS.md) for per-platform confidence levels). Verify all platform contacts, URLs, and procedures against current sources before relying on them. Maintenance policy in [MAINTENANCE.md](MAINTENANCE.md).

A Claude skill that helps legitimate account holders recover from a stuck platform support case — through the channels that actually work: internal legal escalation, state Attorneys General, the FTC, congressional constituent services, and (if needed) a private attorney.

This is not a hack. It is not a paid service. It is not a guarantee. It is a documented escalation framework that has worked for people whose accounts were ignored by support tickets for months — sometimes years — and resolved within weeks once the right pressure was applied through the right channels.

---

## Read this first: when this skill is the wrong tool

**This skill only helps if all three of the following are true:**

1. **You are the legitimate owner** of the account you're trying to recover
2. **You can prove you are the legitimate owner** with documentation
3. **The platform's standard support has failed you** despite your legitimate ownership

If any of those is not true, this won't help — and shouldn't. Specifically:

- This will not help you recover an account someone else owned (a former partner, a deceased relative without estate authority, a former employer, an account you bought from a reseller).
- This will not help you reverse a ban for a Terms of Service violation you actually committed.
- This will not help you bypass legitimate platform decisions you simply disagree with.
- This will not help you "social engineer" your way past identity verification.

The framework works because it surfaces legitimate cases that are stuck in organizational gaps. It does not work as a tool for circumventing legitimate enforcement, and the regulators and attorneys you'd be lying to (state Attorneys General, the FTC, congressional staffers, attorneys taking your case on contingency or fee) take being lied to very seriously. **Filing knowingly false statements with state Attorneys General, the FTC, or the courts is a crime.**

If you're a legitimate owner whose case is stuck: you're in the right place. If you're not: there are better resources for grief, breakup recovery, employment disputes, or whatever situation actually applies.

---

## How to use this

This is a Claude skill. The primary way to use it is to install it in Claude and then describe your situation conversationally — Claude will walk you through the framework, construct documents from your specific case facts (using construction briefs that adapt to your scenario rather than static templates that flatten every case into the same shape), stress-test those documents against adversarial perspectives, and prepare you for an attorney conversation if it gets that far.

### Install in Claude

1. Download the latest `.skill` file from the [Releases page](https://github.com/chrispirillo/signal-flare/releases).
2. In Claude, install or upload the skill (the exact mechanism depends on which Claude product you're using — see Anthropic's documentation for skill installation).
3. Start a conversation by describing your situation. For example: *"My Discord account just got hijacked and Discord support keeps closing my tickets. Can you help me get it back?"* Or: *"I filed a state AG complaint three weeks ago and Meta still hasn't responded — what's next?"*

Claude reads `SKILL.md` and decides which framework stage applies, asks clarifying questions, and walks you through it.

### Read the framework directly

If you want to understand what the skill is doing — or you don't have access to Claude — every part of the framework is also a plain Markdown file in this repo. You can read them in order:

1. **[FRAMEWORK.md](FRAMEWORK.md)** — the 5-stage escalation framework
2. **[questions-to-answer-first.md](questions-to-answer-first.md)** — discovery questions to surface case weaknesses early
3. **[decision-tree.md](decision-tree.md)** — which scenarios route to which tactics
4. **[platforms/](platforms/)** — platform-specific contacts and quirks
5. **[templates/](templates/)** — construction briefs for every escalation document (state AG complaint, FTC complaint, attorney prep document, etc.) plus a documentation-package checklist. These are NOT fill-in-the-blank templates — they are briefs telling Claude how to construct each document from your specific case, with guidance on what varies by scenario, what to avoid, and what good looks like. The briefs are useful for non-skill use too: a person reading them learns what an effective version of each document does, even if they're writing it themselves.
6. **[using-ai-to-build-your-case.md](using-ai-to-build-your-case.md)** — for using a non-Claude AI assistant (or Claude without the skill installed) to replicate what the skill does

### Honest expectations

This framework maximizes the chance of resolution. It does not guarantee one. Platforms can refuse. Regulators can decline to forward your complaint. Attorneys can decline to take your case. Some cases — particularly ones with weak documentation, or where the platform has substantive (not pretextual) reasons for the action — are unsalvageable. The framework works when it works because it gets your case in front of someone with authority to fix it. Sometimes that person looks at it and still says no.

You should still try. But go in clear-eyed.

The system also tends to **go silent for 2–4 weeks** before responding. That silence is normal and does not mean your case has failed. Most resolutions arrive quietly — an account silently restored, an email from someone you've never heard of saying the case has been reviewed.

---

## What this is, in 90 seconds

**Signal Flare is a structured set of plays for getting a stuck case in front of someone with authority to fix it** — when a platform's standard support has stopped working and you need someone who can actually act to *see* you.

Major platforms — Meta, Google/YouTube, X, Discord, TikTok, Twitch, LinkedIn, Snap, PayPal, Steam, Roblox, Reddit — operate at a scale where customer support is largely automated. Cases that fall between two internal teams (account vs. trust & safety vs. billing vs. legal) can sit in a queue forever, replied to only by templated bot responses or low-tier reviewers without authority to fix anything.

The way out of that queue is not more support tickets. It is **escalating to channels the platform's legal and compliance teams actually monitor**:

- State Attorney General consumer complaints
- Federal Trade Commission complaints
- Congressional constituent services inquiries
- Better Business Bureau complaints
- Attorney demand letters on letterhead
- Small claims court for damages

These are run **in parallel, not sequentially**, creating compounding pressure that makes it cheaper for the platform to fix your case than to keep ignoring it.

This works because it does not depend on the platform's customer service. It depends on the platform's *legal exposure to regulators*, which is a different department staffed by different people who have authority customer service does not.

A representative pattern: a personal account on a major social platform is disabled after automated enforcement based on third-party claims that are subsequently retracted. Multiple appeals through the platform's standard process produce only automated rejections over more than a year. The account is silently restored approximately three weeks after a state Attorney General complaint is forwarded to the platform's government affairs team. No personal reply from the platform. They just flip the switch.

The framework here is built from that experience and others like it. It is not magic. It is paperwork applied at the right altitude.

---

## The escalation order, in summary

| Stage | What | Why | Time |
|-------|------|-----|------|
| 0 | Stop the bleeding | Secure adjacent accounts, file the official ticket, document evidence, warn your audience | First 24 hours |
| 1 | Internal channels | Exhaust the platform's own escalation paths, build paper trail | 7–14 days |
| 2 | Asset preservation | Parallel track if your account holds value others depend on (community, business, content) | Continuous |
| 3 | Regulatory pressure | State AG + FTC + congressional + BBB, simultaneous | 1 week to file, 21–35 days for response |
| 4 | Attorney demand letter | The close — letterhead correspondence to platform legal | After Stage 3, if needed |
| 5 | Litigation | Small claims for damages; superior court for larger; class exploration if pattern exists | Last resort |

Most cases resolve at Stage 3. Cases that don't, often resolve within 14 days of Stage 4. Stage 5 is rare.

---

## Supported platforms

Each platform has a Markdown addendum in `/platforms/` documenting the specifics. Coverage at launch:

- **Meta** (Facebook, Instagram, Threads) — `platforms/meta.md`
- **Google / YouTube** — `platforms/google.md`
- **X (Twitter)** — `platforms/x.md`
- **TikTok** — `platforms/tiktok.md`
- **Discord** — `platforms/discord.md`
- **Twitch** — `platforms/twitch.md`
- **LinkedIn** — `platforms/linkedin.md`
- **Snapchat** — `platforms/snapchat.md`
- **Reddit** — `platforms/reddit.md`
- **Roblox** — `platforms/roblox.md`
- **Steam** — `platforms/steam.md`
- **PayPal** — `platforms/paypal.md`

Verification confidence varies — see [STATUS.md](STATUS.md) for per-platform freshness. Discord, Meta, and PayPal are verified; the other 9 are initial drafts that need independent verification before relying on the platform-specific contact details.

Don't see your platform? **[Contributing a new platform addendum](CONTRIBUTING.md#adding-a-new-platform)** is the most useful single contribution to this repo. It takes about an hour for someone who's already been through their own recovery on that platform.

---

## What this skill does not do

To be clear about scope:

- **It is not legal advice.** Nothing in this repo, including the templates and the skill's outputs, constitutes legal advice. Templates are starting points. Hire a lawyer for the close.
- **It is not a guarantee.** The framework has worked for some people. It will not work for everyone. Your case may be denied at every stage. The skill gives you the best documented chance, not certainty.
- **It is not abuse of platform support channels.** Filing a single, factual, well-documented escalation through a platform's published legal-notices address — and concurrent complaints with state Attorneys General, the FTC, and your congressional representatives — is not "abuse." It is the use of regulatory and legal channels for their intended purpose. Filing legitimate complaints with state AGs, the FTC, and Congress is constitutionally protected activity. The skill is structured to escalate one well-documented case once, not to spam, harass, or flood any channel. If you would not want a regulator to read your case file, do not file the case.
- **It is not US-only in spirit, but the regulatory pathway is US-specific.** The state AG mechanism, FTC complaint, and congressional constituent services apply only to US residents. International readers can adapt Stages 0, 1, 2, 4, and 5 to their jurisdictions, but Stage 3 will need substitute mechanisms (your country's data protection authority, consumer protection regulator, telecommunications ombudsman, or equivalent). Contributions documenting the equivalents in other countries are welcome.
- **It is not anti-platform.** Most platform support staff are genuinely trying to help, and most platform decisions are correct. This skill exists for the cases that fall through the cracks despite good faith on both sides.
- **It will not name specific legal theories or statutes.** Identifying the legal theory that applies to your case is the attorney's job — not Claude's, not yours. The skill is constrained from naming theories, statutes, or case law because confidently naming the wrong one would damage your credibility with the attorney you eventually engage.

---

## Contributing

This skill gets better with every recovered account whose owner contributes back. See **[CONTRIBUTING.md](CONTRIBUTING.md)** for how to submit:

- A new platform addendum
- Updated platform information when policies change
- A new template variant
- A documented success story (anonymized) to add to the precedents list
- Translations of the framework or templates into other languages
- Documentation of recovery pathways in non-US jurisdictions

The repo is licensed Apache 2.0 — fork it, adapt it, ship it elsewhere, all permitted with attribution.

---

## Acknowledgments

The framework here is not novel; consumer protection lawyers have known about it for years. This repo just writes it down in a form non-lawyers can use.

The skill stands on the work of state Attorneys General, the FTC, congressional constituent services staff, and the consumer protection bar — public servants and private practitioners who actually do the work of holding platforms accountable when their own processes fail.

---

## License

[Apache License 2.0](LICENSE). Use it, fork it, adapt it. If you build something useful on top of it, link back here so others can find both.

---

## A note from the contributors

If you're reading this because you just lost something — your account, your community, your years of content, your verified identity, your professional connections, or just a piece of yourself you didn't expect to lose — we're sorry. The platforms are not built to handle these moments well, and the moment of realizing that is uniquely awful.

What we can tell you, having watched the framework work in multiple cases: **the system is more responsive to paperwork than it looks.** Customer support is a wall. State Attorneys General are not. The Federal Trade Commission is not. Your senator's constituent services staff is not. An attorney's letterhead is not.

You will probably feel like nothing is working for the first three weeks of this. That's normal. The pressure compounds. The response, when it comes, often comes silently — an account quietly restored, a ban quietly lifted, an email from someone you've never heard of saying "we've reviewed your case and acted." That silence is the system doing its job.

Stay calm. Document everything. Run the plays in order. Hire an attorney for the close.

Good luck.
