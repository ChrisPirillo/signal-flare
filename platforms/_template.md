# [Platform Name] Addendum

> **Schema notes for contributors:** This file documents platform-specific information that supplements the general [FRAMEWORK.md](../FRAMEWORK.md). Every section below should be filled in with verified, dated information. Cite sources for non-obvious claims. Update the "Last verified" date when you change anything.
>
> **Last verified:** [YYYY-MM-DD]
>
> **Maintainer:** [GitHub handle of person who last verified, optional]

---

## Platform identity

- **Legal entity name:** [e.g., "Discord Inc." or "Meta Platforms, Inc."]
- **Headquarters address:** [Full mailing address — used in legal correspondence and AG complaints]
- **Authorized representative / Chief Legal Officer:** [Name and title, if publicly available]
- **State of incorporation:** [e.g., Delaware]
- **Phone (general):** [Public-facing customer service number, if any]
- **Source for above:** [Link to platform's company information page or filings]

---

## Official support channels (Stage 0–1)

- **General support URL:** [The starting point for any user]
- **Compromised-account ticket URL:** [Direct link to hacked-account form, if separate]
- **Ban appeals URL:** [Direct link to ToS appeal form, if separate]
- **Billing dispute URL:** [Direct link to billing dispute form, if separate]
- **Identity verification URL:** [If platform has separate process]
- **Source for above:** [Links to each official page]

---

## Legal & compliance contacts (Stage 1)

- **Legal notices email:** [The published address for legal correspondence — usually `legal.notices@[platform].com` or in their MSA/ToS]
- **Source citation:** [Link to ToS or MSA page where this address is published]
- **Government affairs / public policy contact (if known):** [Often not publicly listed]
- **DMCA agent (if applicable):** [Required to be public for §512 protections]

---

## Special-status escalation paths

For users with elevated platform status. Document each that applies:

- **Verified accounts:** [Channel and contact]
- **Partner / Creator program:** [Channel and contact]
- **Monetized accounts:** [Channel and contact]
- **Business / advertising accounts:** [Channel and contact]
- **Developer accounts:** [Channel and contact]
- **Enterprise customers:** [Channel and contact]

If a status program has a private Discord server, Slack workspace, or partner-only forum, note that — even if you can't link to it.

---

## Known organizational gaps

This is the most important section. Document the specific between-teams failure modes that cause cases to stall on this platform.

Format:

- **Gap 1:** [Description — e.g., "Trust & Safety handles bans but Account Support handles logins; cases where account is disabled due to T&S action but standard recovery is needed fall between teams"]
  - **How this manifests:** [What the user sees]
  - **Workaround:** [If known]

- **Gap 2:** [...]

---

## Documented patterns of failure

Cite public sources for known patterns. Examples:
- Wrongful copyright disabling
- Auto-banning of legitimate users for false-positive ToS violations
- Targeted hijacking of accounts with specific characteristics
- Billing failures of a recurring type
- Verification process failures

For each, link to the public source documenting it (subreddit threads, news articles, forum posts, regulatory filings).

---

## Regulatory precedents

Has the platform been subject to:
- State AG actions? [Cite filing names, dates, status]
- FTC consent decrees or actions? [Cite]
- Class action settlements relating to account/content issues? [Cite]
- Foreign regulatory actions (EU, UK, Australia)? [Cite]

These strengthen your AG complaint by establishing pattern.

---

## Asset preservation specifics

- **Data export available:** [Yes/No, link to feature]
- **Asset transfer (community ownership, etc.):** [Process and criteria]
- **Restoration windows:** [If platform can restore destroyed assets within a window — official or unofficial]
- **Backup tools:** [Third-party tools that work for this platform — RestoreCord, etc.]

---

## Public-pressure channels

- **Official support handle on X:** [@handle]
- **Official subreddit:** [r/subreddit, with note on whether it's officially monitored]
- **Discord support server (meta — for getting help from the platform's community):** [link, if applicable]
- **Public-facing executive contacts:** [LinkedIn profiles of relevant executives, with caveat that direct contact rarely works]

---

## Anti-patterns specific to this platform

What NOT to do on this platform:

- [Anti-pattern 1 with explanation]
- [Anti-pattern 2 with explanation]
- ...

Examples of anti-patterns:
- "Don't open multiple support tickets — the platform explicitly slows review when this happens"
- "Don't try to log in from many new devices — degrades the platform's ability to verify you"
- "Don't issue chargebacks before opening a billing dispute — triggers automatic suspension"

---

## Platform-specific harm narrative angles

What harm framings work especially well for this platform:

- [Angle 1]
- [Angle 2]
- ...

Example: For Discord, "loss of Partner status" carries weight because the program is commercially recognized. For Twitch, "loss of Affiliate/Partner monetization" similarly. For Meta, "loss of verified status / Messenger Kids family connectivity / years of personal communications."

---

## Templates that need adaptation for this platform

Most templates in `/templates/` are platform-agnostic with `[PLATFORM_NAME]` placeholders. Document any that need additional adaptation for this platform:

- `[template-name]`: [What needs adapting]
- ...

---

## Recent changes log

Track significant changes to this addendum:

- **YYYY-MM-DD:** [Change description, by @contributor]
- **YYYY-MM-DD:** [Change description, by @contributor]
- ...

---

## Sources & citations

A consolidated list of public sources cited in this addendum:

1. [Source title — URL — date accessed]
2. [Source title — URL — date accessed]
3. ...
