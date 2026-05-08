# Decision Tree

Different scenarios need different emphasis. The 5-stage framework applies to all of them, but which tactics matter most varies. This guide routes you to the right priorities.

---

## First branch: what kind of recovery is this?

```
What happened to your account?
├── Hacked / compromised by a third party        → Scenario A
├── Banned / disabled for alleged ToS violation  → Scenario B
├── Locked out (no hack, can't access)           → Scenario C
├── Disputed billing / unauthorized charges      → Scenario D
└── Impersonated (someone else claiming to be you) → Scenario E
```

---

## Scenario A: Hacked / compromised account

**Highest-priority tactics:**

| Stage | What to emphasize |
|-------|-------------------|
| 0 | Secure email FIRST. Lock down adjacent accounts immediately. Warn audience. Save platform-generated emails (the timestamp on "your password was changed" emails is the smoking gun). |
| 1 | The official compromised-account ticket; legal notice citing unauthorized access; special-status escalation if applicable |
| 2 | If others depended on the account (community, business, audience), run asset preservation in parallel — don't wait for recovery |
| 3 | AG complaint frames the case as victim of unauthorized access plus failure of platform recovery process |
| 4 | Attorney letter has unusually strong leverage when the account had commercial value |

**Strongest harm narrative angles:**
- Specific dollar amount of unauthorized charges
- Documented community/asset destruction by attacker
- Phishing sent from your account to others (reputational harm)
- Loss of verification or special status

**Templates that apply:**
- `internal-reconsideration.md` (filed as compromised-account ticket)
- `legal-notice.md`
- `state-ag-complaint.md`
- `ftc-complaint.md`
- `congressional-letter.md`
- `attorney-demand-brief.md`
- `community-announcement.md`
- `documentation-package-checklist.md`

**Anti-patterns specific to this scenario:**
- Don't keep filing new tickets — reply to existing ones
- Don't try to log in repeatedly from new devices/IPs (degrades the platform's ability to verify you)
- Don't pay anyone on Telegram/Fiverr/Reddit promising recovery — those are scams

---

## Scenario B: Banned / disabled for alleged ToS violation

**Highest-priority tactics:**

| Stage | What to emphasize |
|-------|-------------------|
| 0 | Save the ban email with full text of the stated reason. Document any context that contradicts the alleged violation. Do NOT create a backup account on the same platform — this is often itself a violation. |
| 1 | Formal appeal through the platform's appeals process. Reconsideration request citing specific evidence the ban was in error. Legal notice if appeal is denied. |
| 2 | If you had a community/audience, set up an alternate presence on a different platform (not the same one) |
| 3 | AG complaint frames the case as wrongful enforcement / failure to provide meaningful appeal process |
| 4 | Attorney letter cites the platform's own ToS appeal commitments and any evidence of automated decisioning errors |

**Strongest harm narrative angles:**
- Specific evidence the alleged violation didn't occur (timestamps, original content, contractual authorization)
- Pattern of similar wrongful bans on the same platform (cite public examples)
- Platform's stated commitment to "fair appeals" or "reasonable review" in their ToS
- Documented appeals that received no substantive review

**Templates that apply:**
- `internal-reconsideration.md` (adapted for appeal language)
- `legal-notice.md`
- `state-ag-complaint.md`
- `ftc-complaint.md`
- `congressional-letter.md`
- `attorney-demand-brief.md`
- `documentation-package-checklist.md`

**Anti-patterns specific to this scenario:**
- Don't admit fault in your appeal language. State facts.
- Don't create a new account on the same platform to "replace" the banned one — this is often a separate ToS violation that prejudices your case
- Don't argue ToS interpretation in early appeals (low-tier reviewers won't engage)
- Don't lie about the alleged violation — see "When this skill is the wrong tool"

---

## Scenario C: Locked out (no hack, can't access)

This includes: forgot credentials, lost access to email or phone number for MFA, locked out by platform's automated security challenges, account marked "needs verification" with no way to verify.

**Highest-priority tactics:**

| Stage | What to emphasize |
|-------|-------------------|
| 0 | Recover access to the email or phone if possible (this often resolves Scenario C without further steps). Document every recovery attempt. |
| 1 | Identity verification ticket with strong documentation. Legal notice if standard recovery fails. |
| 2 | Less critical for this scenario — the account isn't being misused, just inaccessible |
| 3 | AG complaint frames as failure to provide adequate recovery for legitimate owners |
| 4 | Attorney letter usually unnecessary unless damages are significant |

**Strongest harm narrative angles:**
- Comprehensive ownership proof (purchase history, content history, government ID, device records)
- Specific harm from lockout (subscriptions you can't cancel, content you can't access)
- Platform's failure to provide adequate alternative verification

**Templates that apply:**
- `internal-reconsideration.md` (adapted for identity verification)
- `legal-notice.md`
- `state-ag-complaint.md` (often produces results without going further)
- `documentation-package-checklist.md`

**Anti-patterns specific to this scenario:**
- Don't try password resets repeatedly from different IPs (adds noise)
- Don't lie about why you don't have access (regulators check)
- Don't skip the email/phone recovery attempt — that's the simplest fix and you should have a clean record of trying it

---

## Scenario D: Disputed billing / unauthorized charges

**Highest-priority tactics:**

| Stage | What to emphasize |
|-------|-------------------|
| 0 | File chargebacks with your card issuer / Apple / Google AFTER opening the platform's dispute ticket (chargebacks before tickets often trigger platform suspension). Document every charge with date, amount, transaction ID. |
| 1 | Platform's billing dispute process; legal notice if denied; chargeback follow-through |
| 2 | Less relevant for this scenario unless the account also has community/content value |
| 3 | AG complaint specifically targets unauthorized charges as a consumer-protection violation |
| 4 | Small claims court is unusually viable for billing disputes — direct dollar damages, low evidentiary bar |

**Strongest harm narrative angles:**
- Specific transaction IDs and dollar amounts
- Platform's failure to refund despite clear evidence
- Pattern of similar billing failures (cite public examples)

**Templates that apply:**
- `internal-reconsideration.md` (adapted for billing dispute)
- `legal-notice.md`
- `state-ag-complaint.md`
- `ftc-complaint.md` (FTC takes billing fraud seriously)
- Small claims forms (state-specific, not provided in this repo)

**Anti-patterns specific to this scenario:**
- Don't file chargebacks before opening platform tickets — it triggers automatic account suspension on most platforms and prejudices your case
- Don't conflate billing disputes with account disputes — keep them separate where possible
- Don't accept "store credit" if you want a real refund — accepting partial remedy can extinguish your claim

---

## Scenario E: Impersonation

Someone else is claiming to be you on the platform — running an account with your name, photo, or branding, or has somehow been verified as you when they aren't.

**Highest-priority tactics:**

| Stage | What to emphasize |
|-------|-------------------|
| 0 | Document the impersonation thoroughly (screenshots with URLs and timestamps, archived snapshots via web.archive.org). File the platform's impersonation report. |
| 1 | Verified identity claim through platform's official process. Legal notice citing trademark or right-of-publicity violations if applicable. |
| 2 | Public-facing announcement clarifying which account is real (this is itself protective and an evidence record) |
| 3 | AG complaint less powerful for this scenario than for hacks/bans, but still useful |
| 4 | Attorney letter is unusually effective — impersonation often involves clear legal violations (trademark, right of publicity, fraud) |

**Strongest harm narrative angles:**
- Right-of-publicity violation (using your likeness without consent)
- Trademark infringement (if you have a registered mark)
- Fraud (if the impersonator is conducting transactions in your name)
- Platform's stated impersonation policies and failure to enforce

**Templates that apply:**
- `internal-reconsideration.md` (adapted for impersonation report)
- `legal-notice.md`
- `attorney-demand-brief.md` (often goes further faster than other escalation)
- `documentation-package-checklist.md`

**Anti-patterns specific to this scenario:**
- Don't engage publicly with the impersonator — it amplifies them
- Don't pretend to be someone else to "test" their account (creates ToS issues for you)
- Don't skip platform reporting and go straight to attorney — platforms often want to see they had reasonable opportunity to act

---

## Cross-scenario notes

### When multiple scenarios apply

If your situation is "hacked + banned" (a common combination — attacker got in, did something that violated ToS, account was banned for the attacker's behavior):

- Treat it primarily as **Scenario A (hacked)** for narrative purposes
- Add the ban-was-due-to-attacker-not-me framing explicitly in every escalation
- The legal notice and AG complaint should clearly distinguish the unauthorized actor from you
- Documentation must include both the original compromise evidence AND the ban notice

### When you're not sure which scenario applies

When in doubt, treat the situation as Scenario A or B (whichever is more visible — was there a ban notice? Was there a hack notice?). Update your framing as facts emerge.

### When the platform is unresponsive at every stage

This is the most common failure mode, and the framework is built for it. The key insight: **unresponsiveness is itself evidence**. Document it. The AG complaint specifically asks "what response have you received from the company?" — "no response after [N] days" is a meaningful answer that shapes the AG's intervention.

---

## Next: build your Documentation Package

Whichever scenario applies, the next step is the same: assemble your Documentation Package using `templates/documentation-package-checklist.md`. Every later escalation depends on it.
