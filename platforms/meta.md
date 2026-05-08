# Meta (Facebook, Instagram, Threads) Addendum

> **Last verified:** 2026-05-06
>
> **Maintainer:** Initial draft

This addendum covers Facebook, Instagram, and Threads, which are all owned and operated by Meta Platforms, Inc. The recovery framework is largely the same across all three; differences are noted where they apply.

---

## Platform identity

- **Legal entity name:** Meta Platforms, Inc.
- **Headquarters address:** 1 Hacker Way, Menlo Park, CA 94025, United States
- **State of incorporation:** Delaware
- **Phone (general):** No direct customer service phone for users
- **Source:** https://about.meta.com

---

## Official support channels (Stage 0–1)

### Facebook

- **General help center:** https://www.facebook.com/help
- **Compromised-account form:** https://www.facebook.com/hacked
- **Disabled-account appeals:** https://www.facebook.com/help/contact/260749603972907
- **IP retraction form (for retracted copyright claims):** https://www.facebook.com/help/contact/237593160842825

### Instagram

- **General help center:** https://help.instagram.com
- **Compromised-account form:** https://help.instagram.com/contact/740949042640030
- **Disabled-account appeals:** https://help.instagram.com/contact/606967319425038
- **Verified identity / impersonation:** https://help.instagram.com/contact/636276399721841

### Threads

- **Help center:** https://help.instagram.com/threads (Threads support is largely routed through Instagram's support infrastructure)

---

## Legal & compliance contacts (Stage 1)

- **Legal notices email:** Meta does not publish a single legal-notices email for general user correspondence. For DMCA: `ip@fb.com` (Facebook) and `ip@instagram.com` (Instagram).
- **Legal notice mailing address (when sending paper):** Meta Platforms, Inc., Attn: Legal Department, 1 Hacker Way, Menlo Park, CA 94025
- **Government affairs:** Meta has a Government Affairs team that handles state AG and congressional inquiries. They are not directly user-contactable.

---

## Special-status escalation paths

- **Verified accounts (blue check):** Verified users have a separate support flow within the platform, but it routes through the same Trust & Safety team for serious issues
- **Meta Verified subscribers (paid blue check):** Have access to "priority support" via the Meta Verified portal
- **Business accounts:** Meta Business Suite has its own support (https://business.facebook.com/support)
- **Advertisers:** Account managers and advertiser support — typically contactable through ad accounts
- **Creators (Reels Play, Bonuses, etc.):** Creator monetization support; Partner Managers for top creators
- **Oversight Board:** Independent appeals body for content moderation decisions, but only for specific content cases — does not handle account-level disputes (https://www.oversightboard.com)

---

## Known organizational gaps

- **Gap 1: Copyright team vs. Account team.** A Page or content gets disabled due to a copyright claim. The claim is later retracted by the claimant. Meta restores the content but the originating account's "repeat infringer" flag is on a separate system. Neither team owns reinstatement.
  - **Workaround:** State AG complaint citing the retracted-claim documentation has resolved this pattern in documented cases.

- **Gap 2: Facebook vs. Instagram support silos.** Despite shared ownership, Facebook and Instagram support teams operate separately. Cases that span both (e.g., a Meta account with both a Facebook profile and Instagram account, where one is affected) often get bounced between teams.
  - **Workaround:** File separately on each platform; reference both in legal/regulatory correspondence.

- **Gap 3: Automated decisioning with insufficient appeals.** A high volume of bans and disabling actions are made by automated systems. The "appeal" process often consists of a second automated review with the same training data, producing the same result. Human review only kicks in at higher escalation tiers.
  - **Workaround:** The Oversight Board can sometimes force human review for content cases. For account cases, regulatory escalation is more effective.

- **Gap 4: Messenger Kids dependencies.** When a parent account is disabled, the child's Messenger Kids account is also affected. There's no documented process for restoring child connectivity independently.
  - **Workaround:** Cite the family-connectivity harm explicitly in AG complaints — this is unusually compelling to regulators.

---

## Documented patterns of failure

- **Wrongful copyright disabling:** Pattern of legitimate users being disabled based on automated DMCA claims that are later retracted. Meta's repeat infringer policy under 17 U.S.C. § 512(i) requires "reasonable implementation" but the implementation does not adequately handle retracted claims.
- **Account hijacking via session token theft:** Documented widespread pattern of attackers stealing session tokens (often via malicious browser extensions or compromised vendor SDKs).
- **Verified-account targeting:** Verified accounts are higher-value targets for hijacking; recovery is often slower because Meta's verification systems are entangled with account status.
- **Mass auto-banning waves:** Periodic incidents of large numbers of legitimate accounts being disabled simultaneously, typically attributed to ML model errors. Examples occurred in 2024 and 2025 affecting tens of thousands of users.

---

## Regulatory precedents

- **State AG actions:** Multiple state Attorneys General have pursued Meta on consumer protection grounds over the years; informal complaint resolution through state AGs remains the channel that matters most for individual users.
- **FTC consent decrees:** 2012 and 2019 FTC orders against Meta create ongoing compliance obligations; user complaints can reference these.
- **Multistate AG actions:** Coalition of state AGs has pursued Meta on multiple consumer protection fronts.
- **EU Digital Services Act and Digital Markets Act:** Meta is a designated "Very Large Online Platform" under DSA and a "Gatekeeper" under DMA, subject to EU enforcement.

---

## Asset preservation specifics

- **Data export:** Available at Settings → Privacy → Your Information → Download Your Information. Comprehensive (posts, photos, messages, friends, etc.). Takes hours to days to generate.
- **Page transfer:** Available within Meta Business Suite for Pages with multiple admins. Cannot transfer ownership of a personal profile.
- **Restoration windows:** Disabled accounts are typically retained for ~30 days before deletion. After deletion, recovery is very difficult.
- **Off-platform backups:** Meta provides "Transfer Your Information" tools to copy data to Google Photos, Dropbox, Backblaze, etc. Use these proactively for any account you care about.

---

## Public-pressure channels

- **Official X handles:** @Meta, @facebook, @instagram, @MetaforBusiness
- **Official subreddits:** r/facebook, r/Instagram (community-moderated, occasionally Meta staff respond)
- **Public-facing executives:** LinkedIn profiles of Meta's communications and policy executives (direct contact rarely produces results, but can occasionally accelerate via public visibility)

---

## Anti-patterns specific to Meta

- **Don't keep submitting the same form repeatedly.** Meta's systems flag repeated identical submissions and can apply rate limits or further restrictions.
- **Don't try to log in from many new devices.** Login-pattern trust signals matter heavily on Meta platforms.
- **Don't submit ID without redacting the ID number.** Name and photo are sufficient; ID number creates unnecessary privacy risk.
- **Don't create a duplicate account to "replace" a disabled one.** This is a separate ToS violation that prejudices your case for recovering the original.
- **Don't pay anyone for "Facebook recovery services."** These are virtually all scams.
- **Don't email random Meta employees you find on LinkedIn.** They cannot help, will not help, and may flag the contact internally as suspicious.

---

## Platform-specific harm narrative angles

- **Years of personal communications and content** (Facebook accounts often span decades for older users)
- **Loss of Messenger Kids family connectivity** (children cut off from parents — uncommon but powerful framing)
- **Loss of business presence / Page admin status**
- **Loss of monetized content / Reels Play income / Stars**
- **Loss of verified identity** (especially relevant for public figures)
- **Loss of community-management responsibilities** for Groups
- **Disruption to advertising or business operations** for business accounts

---

## Templates that need adaptation for Meta

- `internal-reconsideration.md` → reference Facebook.com/hacked or Instagram contact form
- `legal-notice.md` → addressed to Meta Platforms, Inc., 1 Hacker Way; no single legal-notices email exists
- `state-ag-complaint.md` → frame around documented organizational gaps and prior multistate AG actions
- All templates → cite Meta's published commitments under FTC consent decrees if relevant to your case

---

## Recent changes log

- **2026-05-06:** Initial addendum created.

---

## Sources & citations

1. Meta about page — https://about.meta.com — verified 2026-05-06
2. Facebook hacked-account form — https://www.facebook.com/hacked — verified 2026-05-06
3. Instagram compromised-account form — https://help.instagram.com/contact/740949042640030 — verified 2026-05-06
4. Meta Oversight Board — https://www.oversightboard.com — verified 2026-05-06
5. 17 U.S.C. § 512 (DMCA repeat infringer policy) — public statute
6. FTC vs. Facebook 2019 consent order — public regulatory record
