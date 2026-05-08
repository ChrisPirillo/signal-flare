# The Framework

A platform-agnostic 5-stage escalation framework for legitimate account holders whose recovery has failed through standard support channels.

The framework is the same regardless of which platform you're dealing with. The platform-specific details — official ticket URLs, legal-notices email addresses, known organizational gaps, restoration windows — live in the `/platforms/` directory.

---

## The mental model

Every major platform has organizational gaps. Trust & Safety handles bans. Account Support handles logins. Billing handles payments. Legal handles regulators. Each team can say "not our problem" when your case sits between two of them. **Standard support tickets stay inside that gap forever.**

To get out of the gap, you need to escalate to channels the platform's legal and compliance teams actually monitor. Those teams are staffed by people with authority customer service does not have. Your job is to put your case in front of them through legitimate channels — primarily regulatory complaints — that platforms cannot route to a chatbot.

The five stages compound. Each one you complete strengthens every later one. Stage 3 (regulatory pressure) is where most cases resolve, but Stage 3 only works if you've cleared Stages 0–1 first, because the regulators will ask "did you try the company's process first?" and you need to answer yes with paper trail.

---

## Stage 0: Stop the bleeding (first 24 hours)

If your account was hacked or compromised, the attacker is using it right now to damage you and others. The first 24 hours are about damage control, not recovery.

### A. Secure your email account

If your email account is compromised, anything you do on the platform can be reversed by the attacker. Before anything else:

- Change your email password from a device you trust (not the one that may have been compromised)
- Enable two-factor authentication on the email account
- Check email forwarding rules — attackers often add a forward to capture future password resets. Remove anything you didn't set up.
- Sign out all sessions on the email account
- Review the email's "Sent" folder for messages you didn't send

### B. Lock down adjacent accounts

The attacker likely has access to anything else linked to the same email. Change passwords and enable 2FA on:

- Your password manager (rotate all passwords if it was compromised)
- Banks, payment processors (PayPal, Stripe, Apple ID, Google account)
- Any subscription services with stored payment methods
- Other social media accounts

This isn't paranoia — it's standard incident response. If someone invested effort to hijack one of your accounts, they're going to use anything else they got along the way.

### C. File the platform's official ticket

Every platform has an official "compromised account" or "appeal a decision" ticket form. Find yours in the platform's addendum (`/platforms/[your-platform].md`).

This will likely produce only a templated response or no response at all. **That's fine.** You're not filing this ticket because you expect it to work. You're filing it because every later step requires you to have already filed it.

### D. Warn your audience (if you have one)

If you have followers, a community, a customer list, professional contacts, or anyone else who might receive phishing from your hijacked account: tell them, fast.

Post on every channel you control:

> "PSA: My [platform] account [@handle] was hijacked on [date]. The account is currently controlled by an unauthorized third party. If you receive any messages from it, do NOT click any links. I'm working on recovery and will post updates."

This serves three purposes:
- Protects others from the attacker using your reputation
- Documents the timeline (the timestamp of your warning becomes evidence)
- Shows you took reasonable mitigation steps (which strengthens your harm narrative later)

### E. Save evidence before it disappears

Before doing anything else, save copies of:

- Every platform-generated email related to the incident (password change confirmations, login alerts, MFA-set notifications) — full headers, save as .eml or PDF
- Any messages your contacts received from your hijacked account (ask them to forward with full headers)
- Bank or payment processor statements showing any unauthorized charges
- Screenshots of any visible state of your account or assets before they're modified or destroyed

Save everything to a single folder. This becomes your **Documentation Package**, used in every later stage.

---

## Stage 1: Internal channels (7–14 days, paper trail building)

The platform has multiple internal escalation paths beyond the main ticket. Use all of them. Each one creates a paper trail you'll reference later.

The specific channels vary by platform — see the relevant platform addendum — but the categories are universal:

### A. The official compromised-account ticket (already filed in Stage 0)

Reply to it with formal reconsideration if the response was inadequate. Use `templates/internal-reconsideration.md`.

### B. The legal-notices email

Every major platform has a published legal notices address (usually `legal@[platform].com` or `legal.notices@[platform].com`). It's typically buried in their Terms of Service or Master Services Agreement.

Send a formal notice using `templates/legal-notice.md`. This rarely gets a personal reply. The point is creating a record. When the AG asks the platform "did this user attempt formal escalation?", they cannot say no.

### C. Special-status escalation (if applicable)

If you have any special status with the platform — verified, partnered, monetized, business account, advertiser, developer, enterprise customer — there's usually a separate communication channel. Use it. These channels are staffed by people with different incentives than standard support: retention, program reputation, account-manager relationships.

Examples:
- Discord: `partner@discord.com` for Partner Program
- Meta: business account managers, advertiser support
- YouTube: Partner Manager, Creator Liaison
- Twitch: Partner support, monetization team
- LinkedIn: customer success for premium accounts

Check your platform's addendum for specifics.

### D. Public pressure on social channels

Post on the platform's public-facing support handles (`@SupportName` on X, etc.) and in their official subreddit. **Keep it factual.** Include your ticket number. Do not be hostile. Do not include sensitive details (no email addresses, no payment info, no real name).

This works occasionally. It doesn't usually work alone, but it costs nothing and adds visibility. The Yellow Fellows Discord case is a documented example of public visibility eventually getting attention — the post is publicly indexed on Discord's own support forum and surfaces the pattern of partnered-account hijacking that the company had not addressed.

### E. Wait 7 days

After exhausting these internal channels, wait 7 calendar days. The waiting period strengthens later regulatory complaints — when the AG asks "what response did you receive in writing within a reasonable timeframe?", "no response in 7 days after a formal notice to legal" is a strong record.

---

## Stage 2: Asset preservation (parallel track, continuous)

Run this in parallel with Stages 1, 3, and 4 — not after them. The community/data/content you're trying to recover decays every day you wait.

### A. Data export

Every major platform has a "download your data" or "request my data" feature, often a GDPR-compliance artifact even for non-EU users. Use it from any account that has visibility into the assets you care about (an admin, a co-mod, a friend who follows you).

Even if your account is inaccessible, others' data exports may include cached references to your content, member-list metadata, or interaction history.

### B. Audience preservation

Where does your audience live besides the compromised platform?
- Patreon supporters
- Newsletter subscribers
- YouTube channel subscribers
- Other social platforms
- Discord servers (if the loss is on another platform) or vice versa

Pull every external list. These become the seeds for any rebuild.

### C. Backup presence

If you've lost a community or audience presence, set up an alternate immediately. Don't wait for recovery.

- Create a new account or community on the same platform under a temporary name signaling rebuild ("[Original Name] — Rebuild" or "[Original Name] 2.0")
- Promote multiple admins/co-owners with full permissions (do not be single-point-of-failure again)
- Enable security requirements (2FA mandatory, etc.)
- Set up automated backups going forward (RestoreCord, Wick, or platform-equivalent tools)

### D. Restoration request

Some platforms can restore destroyed assets within a window (typically 30–45 days, often unofficial). File a restoration request even if you're skeptical it'll work. The rejection becomes evidence; the success is rare but real.

### E. Migrate where you can

Post invite links or your new presence everywhere your audience lives. Set realistic expectations: without a pre-installed backup tool, you'll typically recover 10–30% of your previous audience.

---

## Stage 3: Regulatory pressure (the unlock)

This is the stage where most cases actually resolve. Run all four of these **in the same week**, ideally on the same day.

### A. State Attorney General complaint (highest priority)

Every US state's AG accepts consumer complaints from their residents about out-of-state companies. The platform may be headquartered in California or Delaware — irrelevant. Your AG has jurisdiction over harm done to you as a resident of your state.

Find your state's AG complaint portal:
- Google: `[your state] attorney general consumer complaint`
- Or use the National Association of Attorneys General directory: https://www.naag.org/find-my-ag/

Use `templates/state-ag-complaint.md` (a construction brief). Most state AG forms have character limits (Washington's is 3,500). The brief notes typical limits and tells Claude to construct narratives that fit them.

The AG will:
1. Acknowledge receipt within 7–14 days, with a complaint/file number
2. Forward your complaint to the platform with a request for written response within 21–35 days
3. Forward the platform's response back to you when received

**The file number you receive becomes the single most powerful piece of paper in this entire process.** It transforms your case from a customer service annoyance into a regulatory matter. Reference it in every later step.

The AG won't sue the platform for you (mostly — some state AGs do file pattern-based actions, and your complaint may be aggregated). Their core role is informal mediation. The mechanism that makes it work is that your complaint goes to the platform's government affairs / legal team, who have authority customer service does not.

### B. FTC complaint

File at: **https://reportfraud.ftc.gov**

This won't trigger individual action, but it adds your complaint to the FTC's pattern-recognition database. Use `templates/ftc-complaint.md`. Takes about 10 minutes.

### C. Congressional constituent services

Your two US Senators and your House Representative all have constituent services staff whose job includes resolving disputes between you and large companies. Tech companies respond to congressional inquiries because they go to a Government Affairs inbox, not customer support.

Find your representatives:
- Senate: https://www.senate.gov/senators/senators-contact.htm
- House: https://www.house.gov/representatives/find-your-representative

Each has a "Help with a Federal Agency" or "Constituent Services" form. Use `templates/congressional-letter.md`. Send to all three.

### D. Better Business Bureau complaint

File at: **https://www.bbb.org/file-a-complaint**

Lowest impact of the four, but takes 5 minutes and adds public record. Most major platforms have BBB profiles and respond to BBB complaints to maintain their rating.

### E. Wait

After filing all four, the typical resolution window is 14–35 days. During this time:
- Continue Stage 2 work (asset preservation, community rebuild)
- Don't file additional duplicative complaints
- Save every reply that comes in
- Reference your AG file number in any further correspondence

In documented cases, accounts have been silently restored approximately three weeks after the state AG forwarded the complaint. No personal reply from the platform. Just a fix.

---

## Stage 4: Attorney demand letter (the close)

If 35 days after the AG complaint there's no resolution, this is the close.

### Why it works

A demand letter on attorney letterhead, sent to the platform's legal-notices email, goes to a real lawyer at the platform with authority to flip the switch. Unlike customer service, attorneys answer attorney letters. Unlike chatbots, attorneys read context.

Cost is typically $500–$2,000 for a single demand letter. For most cases with quantifiable damages, this is straightforwardly worth it.

### Who to hire

You want an internet/technology attorney, not a generalist. The right specialty matters more than location — most internet attorneys operate cross-jurisdiction.

**What to search for:**

- "Internet law attorney [your city/state]"
- "Technology law attorney [your city/state]"
- "Consumer protection attorney [your state]"
- "Platform account dispute attorney"
- For billing-specific disputes: "FCRA attorney" or "consumer financial protection attorney"
- For impersonation cases: "right of publicity attorney" or "trademark attorney"

**Where to look (no specific service endorsed — find them yourself, then vet them):**

The goal is to find an *independent, neutral source* listing attorneys with verifiable credentials. You're not looking for advertising — you're looking for screened or peer-rated information.

- **Your state bar's lawyer referral service.** Every US state bar runs one. They pre-screen attorneys for active license, malpractice insurance, and area of practice. Search: `[your state] bar lawyer referral service` (e.g., `Washington state bar lawyer referral service`). This is the most trustworthy starting point — it's run by the body that licenses attorneys in your state.
- **Independent attorney directories.** Several large web directories list attorneys with peer or client ratings, disciplinary records, and area-of-practice tags. Search: `attorney directory peer rated`, `attorney directory consumer reviews`, `attorney directory disciplinary records`. Look for directories that *show* disciplinary history, not just star ratings.
- **Consumer protection attorney associations.** National and state-level associations of consumer advocates publish member directories. Search: `consumer advocates association directory`, `consumer protection attorney directory [your state]`.
- **Trade-press attorney listings.** Legal trade publications publish annual "best of" or "rising star" lists, peer-nominated. These can surface senior practitioners. Search: `[your state] best lawyers internet law`, `top consumer protection attorneys [your state]`.
- **Bar association sections.** Most state bars have practice-area sections (e.g., a Technology Law section). Section officer lists are usually public and identify active specialists. Search: `[your state] bar technology law section`.

**What a trustworthy source looks like:**

- It's run by a bar association, a non-profit advocacy group, or a long-established trade publication — not a single firm
- It shows credentials you can independently verify (bar number, year admitted, state licensed in)
- It surfaces disciplinary history, not just ratings
- It does not require payment from the attorney to be listed (paid-only listings are advertising, not screening)
- It distinguishes specialty (internet/technology law, consumer protection) from generalist practice

**What an untrustworthy source looks like:**

- A single firm's own site presented as a "directory"
- "Top attorney" lists with no disclosed methodology
- Sites that hide disciplinary records behind paywalls
- Sponsored placements without disclosure
- Testimonials only, no objective credential data

**Always cross-check.** Once you find candidate names, verify each one on **your state's official bar website** (every US state bar has a public attorney lookup). Confirm: (1) active license, (2) no recent suspensions, (3) practice area listed includes what you need.

**Questions to ask in the first consultation (most attorneys offer a free 15–30 minute call):**

1. "Have you handled platform account cases involving [your specific platform]?"
2. "Have you sent demand letters to major tech companies before? Which?"
3. "What's your fee structure for a single demand letter — flat fee, capped fee, or hourly?"
4. "If the demand letter doesn't resolve it, what are the next steps and what would they cost?"
5. "What's a realistic outcome range for a case like mine?"
6. "Do you charge for the initial document review, or is that part of engagement?"
7. "How many of these cases have settled before litigation? How many went further?"

**Red flags to watch for:**

- Pressure to engage immediately without time to think
- Refusal to give a fee range in writing
- Promises of guaranteed outcomes (no ethical attorney guarantees outcomes)
- "Specializes in everything" — internet law is a genuine specialty; generalists are usually less effective here
- No published reviews or peer ratings anywhere
- No verifiable active state bar license
- Reluctance to provide a written engagement letter
- Vague answers about prior platform cases ("I've handled lots of similar matters" without specifics)
- Cold outreach offering to take your case after a public AG filing — this is solicitation; reverse the search and verify *you* found *them*, not the other way around

**What to expect for fees:**

- Single demand letter (flat fee): typically $500–$2,500 depending on complexity and attorney seniority
- Document review and engagement: sometimes free as part of the demand letter package, sometimes $200–$500 separately
- If escalating beyond demand letter: hourly rates for litigation typically $300–$700/hour for internet specialists in major US cities; contingency arrangements possible for cases with quantifiable damages
- Avoid: paying a flat-fee retainer up front for "ongoing representation" before the demand letter is even drafted

### What to give your attorney

Use `templates/attorney-demand-brief.md` as a starting point. Provide them:
1. Your complete documentation package PDF
2. Your AG complaint number
3. Your FTC complaint reference
4. Confirmation of congressional inquiries opened
5. Records of every platform correspondence

The attorney will rewrite the brief on letterhead in their voice. The cost-saver for you is doing the homework — they're paid to be a lawyer, not a research assistant.

---

## Stage 5: Litigation (last resort)

Most cases don't reach this stage. If yours does:

### Small claims court

Every state has one. Dollar limits typically $5,000–$10,000. You can sue the platform in your state's small claims court for the dollar value of any unauthorized charges, lost subscription value, and (in some states) reasonable damages for documented harm.

The platform must send a representative or default. This is a real lever for billing-related damages and modest harm cases.

### Superior court / state court

For damages exceeding small claims limits, your attorney can file in:
- The platform's home jurisdiction (often San Francisco County Superior Court for California-based platforms)
- Your state's court of competent jurisdiction (for cases where harm occurred where you live)

Most cases settle once filed. Few go to trial.

### Class action exploration

If a documented pattern exists (other users similarly affected), a class action is theoretically viable. Your attorney can investigate whether other potential class members exist. This is uncommon but real — examples include the New Jersey AG's consumer fraud action against Discord (April 2026, currently active in state court).

### Federal court

Reserved for very large damages or class-action contexts where federal jurisdiction is appropriate. If your case is here, you have an attorney. Listen to them, not to this document.

---

## What makes this work

The framework succeeds because it does not depend on the platform's customer service. It depends on the platform's *legal exposure to regulators*, which is a different department staffed by different people who have authority customer service does not.

The compounding pressure mechanic:
- Stage 1 creates evidence that customer service failed
- Stage 3 puts that evidence in front of regulators
- Stage 4 puts the same evidence in front of the platform's own lawyers, who must now respond not to a customer but to a peer who could file a lawsuit
- Stage 5 is the lawsuit, made cheap and credible by everything before it

At each stage, the platform's cost of continuing to ignore your case rises, while the platform's cost of resolving it stays low (it's just an account or a server — flipping the switch is free). At some stage, the resolution becomes cheaper than the continuation, and the platform acts.

That stage is usually 3. Sometimes 4. Rarely 5. The framework's job is to get you to that point with the strongest possible documentation.

---

## What this framework does not do

- It does not work for cases without legitimate ownership. Regulators check.
- It does not work outside the US for Stage 3 specifically (international readers need substitute mechanisms — see the platform addendums and the [regional adaptations directory](regions/README.md)).
- It does not work fast. Plan for 30–60 days from start to resolution.
- It does not guarantee outcomes. It improves them.

---

## Next steps

1. Read [questions-to-answer-first.md](questions-to-answer-first.md) and answer them about your situation
2. Open [decision-tree.md](decision-tree.md) to see which scenario applies
3. Read [your platform's addendum](platforms/) for the platform-specific details
4. Build your [Documentation Package](templates/documentation-package-checklist.md)
5. Begin Stage 0 if you haven't already

Or install this repo as a Claude skill and let Claude do all of the above conversationally — gathering your case facts, constructing each escalation document tailored to your specific situation, stress-testing it against adversarial perspectives, and preparing you for an attorney consultation if it gets that far.
