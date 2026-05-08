# Documentation Package Checklist

> **Role of this file in the skill:** unlike the other files in `templates/`, this is not a construction brief. It is a checklist. When Claude guides the user through evidence gathering (during Stage 0–1 of the framework), use this checklist directly: walk the user through each category, ask what they have for each, and flag what's missing. The completeness of this package is the single biggest predictor of outcome — every later step in the framework depends on it.
>
> Don't generate the checklist; *use* it. When the user has assembled their materials, this same checklist becomes the basis of the documentation package they attach to regulatory filings.

Build this once. Use it for every escalation. The strength of every later step depends on the completeness of this package.

## Save as PDF or PNG. Keep originals in a single folder.

### Identity proof

- [ ] Government photo ID with name visible (redact ID number — leave name + photo)
- [ ] Proof of current address (utility bill, bank statement) — required by some AG forms
- [ ] If applicable: proof of legal name change, marriage, or other identity-document discrepancy

### Account ownership proof

The strongest single piece of ownership evidence is **payment history**. If you've ever paid the platform anything, that's gold.

- [ ] Subscription / purchase receipts (PayPal, Stripe, Apple App Store, Google Play, direct credit card)
- [ ] Bank or credit card statements showing platform charges (redact card number, leave merchant + date + amount)
- [ ] Email correspondence with the platform (welcome emails, monthly receipts, security notifications)
- [ ] Special-status emails (verification confirmation, partnership acceptance, monetization approval)
- [ ] Profile screenshots from before the incident (any source: cached pages, friends' screenshots, Wayback Machine archive)
- [ ] Witness statements from friends, business contacts, co-workers, community members confirming you are the legitimate account owner

### The incident timeline (single document)

Format every entry like this:

```
2026-XX-XX, HH:MM TZ — [What happened]
2026-XX-XX, HH:MM TZ — [What you did]
```

Include at minimum:

- [ ] When you first noticed something was wrong
- [ ] What you observed (login alert, password change email, account access denied, ban notification, friends getting phishing from your account, billing charges, etc.)
- [ ] Every action you took (password reset attempts, support tickets opened, app revocations, public announcements)
- [ ] Every reply from the platform, with date and ticket number

### Platform-generated email evidence

These come straight from the platform with timestamps. Save with full headers:

- [ ] "Your password has been changed" notification
- [ ] "Your email has been changed" notification (often the smoking gun for hacks)
- [ ] "New device login" notifications
- [ ] "Multi-factor authentication enabled" notification
- [ ] Ban / account disable notification
- [ ] Any platform support replies (yes, even bot replies)

### Adverse evidence (if applicable)

For hijacking cases:
- [ ] Screenshots of suspicious messages your contacts received from your account
- [ ] Screenshots of unauthorized actions taken during the compromise (posts, purchases, asset destruction)
- [ ] Bank statements showing unauthorized charges with transaction IDs

For ban cases:
- [ ] The exact text of the ban reason (full email)
- [ ] Evidence contradicting the alleged violation (timestamps, contracts, content originals, contractual authorization)

For lockout cases:
- [ ] Proof of original email/phone control (welcome emails, prior security correspondence)
- [ ] Documentation of why standard recovery fails (lost phone, changed email, missing MFA backup codes)

For billing cases:
- [ ] Each disputed transaction with date, amount, transaction ID, payment method
- [ ] Original purchase confirmation (what you intended to buy, if anything)
- [ ] Communication with the platform's billing dispute process

For impersonation cases:
- [ ] Screenshots of the impersonating account with URL and timestamp
- [ ] Archive.org snapshots of the impersonating account
- [ ] Evidence of your established prior identity on the platform

### Platform support correspondence

- [ ] Original ticket number(s) — there will likely be multiple
- [ ] Every reply from the platform, with date
- [ ] Any rejection language used (this becomes evidence)
- [ ] Screenshots of any in-app support interactions

### Harm statement (4–8 sentences, plain English)

Cover all that apply. Be specific with dollar amounts and timeframes:

- [ ] Money lost: unauthorized charges, lost subscriptions, lost monetized revenue
- [ ] Active obligations you cannot fulfill: subscriptions you can't cancel, services you can't access
- [ ] Communities/audiences affected: specific member counts, years invested
- [ ] Business or professional impact: revenue tied to the account, professional contacts, customer relationships
- [ ] Personal communication impact: cut off from friends/family, lost message history, lost photo/content history
- [ ] Reputational harm: phishing sent from your account, false statements made by attacker, impersonation damage
- [ ] Time spent on resolution attempts: count the hours

### External corroborating evidence (strengthens the case)

If applicable to your platform:
- [ ] Public posts about your situation that document the timeline
- [ ] Reports of similar incidents on the same platform (Reddit threads, news articles, regulatory filings)
- [ ] Documentation of platform-wide breaches or known patterns affecting your account class
- [ ] Press coverage of the broader pattern

### Combine into one PDF

Once collected, merge into a single PDF named:

```
[YourName]-[Platform]-Recovery-Documentation.pdf
```

This single file becomes your attachment for every regulatory complaint and the attorney letter.

### Privacy reminder before sharing

Before this PDF goes anywhere:

- Redact any account passwords (you should not have written them down anyway)
- Redact full credit card numbers (last 4 digits visible is fine)
- Redact Social Security Number / Tax ID if any document shows it
- Redact other people's private contact info if it appears in screenshots
- **Keep your full name, contact email, current address visible** — regulators need them to process your complaint

### Update the package as you go

The Documentation Package is not built once and frozen. As you receive new platform replies, file new tickets, or see new evidence, add it to the package with dates. The dated chronology is itself part of the evidence.
