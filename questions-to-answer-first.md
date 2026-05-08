# Questions to Answer First

Before you start filing things, answer these. Your answers determine which skill variant applies, which templates you'll need, and which arguments are strongest in your case.

If you can't answer a question, mark it "unknown" and continue. Some unknowns get resolved as you work through Stage 0.

If you're using this repo as a Claude skill, Claude asks you these questions conversationally as needed and routes the output to the right templates automatically.

---

## 1. Identity & jurisdiction

**1.1 What state do you live in?**
> Determines which Attorney General will handle your complaint. Every state's AG accepts complaints from residents about out-of-state companies.

**1.2 Are you a US resident?**
> If no, the regulatory pathway in Stage 3 will need to be adapted for your jurisdiction. Stages 0, 1, 2, 4, 5 work everywhere.

**1.3 Are you the legitimate, sole owner of the account?**
> If no — close this guide. The framework only works for legitimate owners with provable ownership.

---

## 2. Platform & account specifics

**2.1 Which platform is this about?**
> Determines which addendum in `/platforms/` applies to you.

**2.2 What is your username/handle on that platform?**
> You'll need this for every escalation.

**2.3 What email was associated with the account?**
> The email at the time of the incident matters more than your current one.

**2.4 Approximately when did you create the account?**
> "I've used this account since 2014" is a stronger ownership claim than "I created this last month."

**2.5 Did your account have any special status?** (verified, partnered, monetized, business, advertiser, developer, enterprise customer, paid tier, premium subscription)
> Special status often unlocks separate escalation channels and strengthens harm narrative.

---

## 3. The incident

**3.1 What happened to the account?** Pick the closest:
- Hacked / compromised by a third party
- Banned / disabled for alleged Terms of Service violation
- Locked out (forgot credentials, lost access to email/phone, MFA issue)
- Disputed billing / unauthorized charges
- Impersonated by someone claiming to be you
- Other

**3.2 When did it happen?** (date, approximate time, time zone)

**3.3 What evidence do you have that an incident occurred?** (platform-generated emails, login alerts, friends receiving phishing from your account, password change confirmations you didn't initiate, a ban email with reason, etc.)

**3.4 If hacked: what did the attacker do with the account?** (deleted it, changed details, sent phishing, made purchases, destroyed assets, posted content, took over assets you owned)

**3.5 If banned: what was the stated reason?** (the platform almost always sends an email or in-app notice with a reason — even a vague one. Save that text exactly.)

**3.6 Was there a triggering event you can identify?** (clicked a phishing link, used a weak password, vendor data breach, social engineering attempt, third-party app you authorized, content that may have been auto-flagged, etc.)

---

## 4. Stakes & harm

**4.1 What value is tied to this account?** Be specific. Examples:
- Money in unauthorized charges (with dollar amounts)
- Active subscriptions you cannot cancel
- Years of personal content (messages, photos, videos)
- Professional/business contacts and revenue
- Community ownership (followers, server members, subscribers)
- Verified identity / public-figure status
- Linked services that depend on this account

**4.2 What is the dollar value of the harm, approximately?**
> Vague harm gets ignored. Specific dollar harm gets attention. Even rough estimates ("$500/month in Patreon revenue tied to this community") are far stronger than "I lost something important."

**4.3 Are others harmed by your account loss?** (community members locked out, business clients disrupted, family members cut off, customers unable to reach you)

**4.4 How long has this been going on?**
> Timeline matters. "Locked out for 4 days" is different from "Locked out for 14 months."

---

## 5. What you've already tried

**5.1 Have you filed the platform's official ticket?** (When? What was the response?)

**5.2 Have you filed multiple tickets?**
> Some platforms slow down review when you file multiple tickets. Document them all but stop opening new ones if you're past the first.

**5.3 Have you contacted any other channel?** (legal notices email, special-status escalation, public social pressure, friends with industry contacts at the platform)

**5.4 Have you escalated to any regulator yet?** (state AG, FTC, BBB, congressional office)

**5.5 Have you spoken with an attorney yet?**

---

## 6. Documentation status

**6.1 Do you have a Documentation Package?**
> See `templates/documentation-package-checklist.md`. If no, build it before any further escalation.

**6.2 Do you still control the email originally associated with the account?**
> Critical. If yes, the platform's recovery flow may still work. If no, your case is harder and recovery needs explicit ownership documentation.

**6.3 Can you provide government photo ID?**
> Required for some state AG forms and any attorney engagement.

**6.4 Do you have proof of payment?** (credit card statements, PayPal/Stripe receipts, App Store / Google Play purchase history)
> The single strongest ownership proof for any account that has ever paid for anything.

**6.5 Are there witnesses who can confirm ownership?** (friends, business contacts, co-mods, subscribers, employees)

---

## 7. Tactical decisions

**7.1 What's your timeline?**
- Immediate (urgent business or safety dependency) → fast-track all five stages in parallel
- Standard (1–3 months acceptable) → run stages 0–4 in order with overlapping timing
- Patient (6+ months acceptable) → run stages 0–4 sequentially with full waiting periods

**7.2 What's your budget for this?**
- $0 → Stages 0–3 plus self-filed Stage 5 small claims. Skip attorney.
- $500–$2,000 → All stages including attorney demand letter (Stage 4)
- $5,000+ → All stages plus litigation if needed

**7.3 Are you comfortable being public about this?**
> Public visibility (social posts, press) sometimes accelerates recovery. It also makes you a higher-profile target if the bad actor is still active. Default: stay public-but-factual. Don't be hostile, don't share sensitive details.

---

## What your answers tell you

After answering these, you should be able to identify:

- **Your scenario type** (hack vs. ban vs. lockout vs. billing — see [decision-tree.md](decision-tree.md))
- **Your platform addendum** (`/platforms/[name].md`)
- **Your harm narrative** (what to write in the "harm" section of every escalation)
- **Your documentation gaps** (what you need to gather before escalating)
- **Your tactical pacing** (which stages to run sequentially vs. in parallel)

If you've answered every question and you're not sure where to start: the answer is almost always **Stage 0** (stop the bleeding) followed by **Documentation Package assembly**. Skipping these makes every later step weaker.
