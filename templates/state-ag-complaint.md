# Construction Brief: State Attorney General Complaint

This is not a fill-in-the-blank template. It is a brief that tells you (Claude) what an effective state AG complaint needs to do, what to include, what to vary based on the user's case, and what to avoid. Construct each complaint from this brief and the user's specific facts.

> ⚠ **Before this document is sent:** the user is asserting facts under their own name to a state regulator. Filing knowingly false statements with state Attorneys General is a crime in most jurisdictions and will end the case the moment it's caught. Walk the user through every factual claim and verify each is supported by their evidence before they file.

---

## What this document needs to do

A state Attorney General consumer-protection complaint serves one purpose: cause an investigator at the state AG office to forward the case to the platform's government-affairs team for response. Nothing else. Not winning damages, not establishing legal theory, not getting an apology. Just: getting the case picked up and forwarded.

The investigator reads the complaint in 60–120 seconds and decides whether to take the case seriously. They apply three filters:

1. **Does this look like a real case from a real person, or is it templated activism?** The investigator's office sees patterns. Boilerplate openings, identical paragraph structures, and stock phrasings cluster as form-letter complaints and get de-prioritized.
2. **Is the harm specific, documented, and quantifiable?** "I lost my account" is weak. "I lost an Etsy account that generated $3,400/mo in income, with 847 listings, on the basis of a copyright claim that was retracted by the original claimant on April 14" is strong.
3. **Is the platform's role clear, and is this within the AG's jurisdiction?** Person-vs-platform consumer disputes are in scope. Person-vs-person disputes (an ex won't return shared property) are not.

A complaint that fails any of these three filters dies in intake, regardless of how true or sympathetic it is.

---

## What always goes in

Every state AG complaint needs these elements. Order can vary; presence cannot.

1. **Complainant identification.** Real legal name, real mailing address (to the user's actual residence in the state), real contact info. State AGs only forward complaints from constituents in their state; the address has to match.
2. **Respondent identification.** Platform's legal entity name (read from the relevant `platforms/{platform}.md` addendum — e.g., "Discord, Inc." not "Discord"), legal-notices address, state of incorporation. Be precise — wrong entity name signals the complainant didn't research, which weakens the case.
3. **A factual narrative.** Plain English, chronological, third-grade-reading-level prose. What happened, in what order, with dates. The user is telling the investigator their story. Not legal language. Not aggrieved-customer language. Just facts.
4. **Specific quantifiable harm.** Dollar figures if any (unauthorized charges, lost income, replacement costs). Non-dollar harm if no dollars (audience size, account age, professional reach, accessibility loss, public-figure verification status). Always concrete numbers, never "significant" or "substantial."
5. **What the user has already tried.** Evidence of exhaustion of internal channels — ticket numbers, dates of submissions, contents of platform replies. This signals the AG isn't being asked to do support's job.
6. **Requested relief.** Phrased as something the AG can actually do: "I respectfully request that your office forward this complaint to [Platform's legal entity]'s government affairs office and request a substantive review of my case." Never: "force the platform to," "compel," "order the platform to" — AGs don't have unilateral authority over interstate platforms in this posture.

---

## What varies by scenario

The user's scenario reshapes which elements get emphasized. Read `decision-tree.md` for scenario definitions if you haven't.

### Scenario A — Hijacked / compromised

**Lead with the takeover timeline.** Establish the moment of unauthorized access — login alerts, IP changes, password reset emails the user didn't initiate, sudden change of recovery email/phone. Make clear this was a security breach the platform failed to remedy after notification, not a routine account dispute.

**Quantify harm primarily as account-value plus direct loss.** Followers/subscribers (with numbers), content (with examples and dates), business reach if applicable, plus any direct financial loss from the hijacker (purchases on linked cards, ransom demands, secondary account compromises).

**Frame the platform's failure precisely.** The complaint is not "I got hacked" — that's the user's misfortune, not the platform's. The complaint is: "I documented a confirmed account compromise to [Platform] on [date]. They received my report through their stated reporting channel. They have failed to restore access to the verified owner over [N] days, despite my providing [list of evidence types]."

### Scenario B — Banned / disabled for stated ToS violation

**Address the alleged violation head-on.** State the platform's stated reason for the action. State, plainly, that the user did not commit the violation. Then provide concrete evidence — what the user was actually doing at the time (with timestamps if possible), why the platform's basis was incorrect (false report, misidentified content, automated false-positive).

**Emphasize the user's good-faith engagement.** They submitted appeals through the proper channel, provided evidence, received only automated responses. The complaint is not about the platform's right to enforce ToS — that's well-established. The complaint is about the platform's failure to provide a meaningful review.

**Quantify harm with care.** Banned-for-cause complaints face higher skepticism. Lead with the most concrete, third-party-verifiable harm types: business income loss with documentation, professional reach loss, contract obligations the user couldn't meet because the account was unavailable.

### Scenario C — Lockout / inaccessible without explanation

**Lead with the silence.** A lockout without a stated reason is the platform's most defensible posture *and* its most regulator-frustrating one. The complaint frames the silence as the harm: "I cannot access my account. The platform has not given me a reason. I have submitted [N] tickets over [N] days. I have received only automated responses. I am asking your office to ascertain whether there is a substantive issue I can address, or whether this is a system failure."

**The investigator can do something here that the user cannot:** ask the platform to explain. That ask is realistic. Make it the relief request.

### Scenario D — Billing / unauthorized charges

**Lead with the dollar amount.** State AG offices strongly prioritize cases involving direct financial harm. The first sentence should establish: "I have been charged $X.XX by [Platform] for charges I did not authorize, and I have been unable to dispute those charges through the platform's standard process."

**Frame as a consumer protection issue, not a platform-dispute issue.** Unauthorized charges are squarely within most state AG consumer protection mandates. If charges relate to a financial service (PayPal, Cash App, Venmo), also reference CFPB jurisdiction and consider parallel filing.

**Document chargeback attempts.** If the user has attempted credit-card chargeback through their bank, mention the result (granted, denied, pending). If they haven't, encourage them to do that in parallel — but don't make it a precondition.

### Scenario E — Impersonation

**Lead with the impersonator's account, not the user's.** The complaint is that the platform has failed to remove an account specifically created to impersonate the user, despite being notified with proof of identity. Provide URLs, screenshots of the impersonator's content, and any harm the impersonator has caused (financial scams in the user's name, defamation, audience confusion).

**Quantify reputational and financial harm specifically.** "People believe these statements are mine," "the impersonator solicited and received $X from my followers under false pretenses," "I have been forced to publicly disavow [N] times."

---

## What good looks like

Two examples — both following this brief, both producing very different complaints because the underlying cases are different.

**Example 1: Small-business Etsy account, false-report cluster, Scenario B**

> [Caption block with complainant and respondent details]
>
> I run a small home-business selling handmade leather goods on Etsy. My shop, [shop name], operated continuously for 4 years and 7 months. It generated approximately $3,400 in monthly revenue and was my primary household income.
>
> On April 11, 2026, my shop was suspended without prior warning. The notification cited "intellectual property violations" and listed three of my listings as the basis. The listings in question were original photographs of my own products, taken in my own workshop. I have the raw camera files, the workshop EXIF data, and time-lapse video documenting the photo shoots.
>
> The intellectual-property reports came from a single competitor account, [redacted competitor handle], who had previously left negative reviews on my listings and contacted me directly demanding I take down "her" designs. Her designs were never on my listings. I have her messages.
>
> I submitted a counter-notice through Etsy's IP dispute process on April 12, with the raw photo files and a sworn declaration of original authorship. I received an automated acknowledgment. Twenty-eight days later, I have received no further communication. My shop remains suspended. I have lost approximately $3,200 in income and am unable to fulfill 14 outstanding orders for which buyers have already paid.
>
> I respectfully request that your office forward this complaint to Etsy, Inc.'s government affairs office and request a substantive review of my IP counter-notice and shop reinstatement.

**Example 2: Hijacked Instagram of a working musician, Scenario A**

> [Caption block]
>
> I am a working musician based in [city]. My Instagram account, @[handle], with 41,200 followers, has been my primary professional booking channel for 6 years. I have booked approximately $18,000 in performances through it in the past 12 months alone.
>
> On the evening of March 28, 2026, I received three login-attempt notifications from Instagram while at a venue without service. By the time I reached internet, my account had been taken over: my email and phone number on the account were changed, my profile picture was replaced, and the account had been used to send unsolicited cryptocurrency promotion to my followers.
>
> I reported the compromise to Instagram's hijacked-account form (linked: [URL]) at 11:42 PM on March 28, including a video selfie matching my prior posts and a government ID matching the name on the account. I have received only automated responses. As of today, 31 days later, the hijacker still has access. They have continued to post fraudulent cryptocurrency promotions in my name. Three of my followers have contacted me directly believing those posts were mine, and one has reported losing $400 to a scheme the impersonator promoted.
>
> The professional impact has been immediate. Two booking inquiries that came through the account during the compromise period went unanswered. My agent reports that prospective bookers have started contacting them directly because they cannot reach me through the channel they're used to.
>
> I respectfully request that your office forward this complaint to Meta Platforms, Inc.'s government affairs office and request that Meta substantively review the hijacked-account report I filed on March 28 (case reference [number]) and restore the account to verified ownership.

Notice what these examples share: real numbers, specific dates, named platform reporting channels, calm tone, identifiable third-party harm. Notice what they don't share: opening structure, paragraph order, length distribution, emphasis. They sound like two different real people with two different real problems.

---

## What to avoid

- **Boilerplate openings.** Anything that begins "I am writing to file a formal complaint regarding..." reads as templated. Open with the specific case in the user's voice. The reader has already inferred what kind of document they're looking at from the form they received it through.
- **Emotional flooding.** Investigators are sympathetic to legitimate harm but trained to discount complaints that lead with feelings rather than facts. One brief sentence acknowledging the impact ("This account loss has been financially devastating to my family") is acceptable. A paragraph of escalating distress is not.
- **Legal-theory shopping.** Do NOT name specific statutes, causes of action, or legal theories. The investigator knows the law. Naming it incorrectly damages credibility. (This is reinforced by the skill-level rule — see SKILL.md.)
- **Platform-bashing.** "Big Tech doesn't care about real users" frames the case as ideological grievance, not consumer protection. The investigator stops reading.
- **Demands the AG can't grant.** "Force the platform to restore my account," "order the platform to pay damages," "prosecute [platform]" — none of these are within the AG's authority in this posture. Stick to "review and forward."
- **Multi-issue complaints.** One case, one set of facts. Don't bolt on "and they also did X to my friend last year" or "and their general practices are bad because." Tight focus.
- **Hyperlinks the investigator can't click.** State AG portals often strip URLs or render them inert. Reference URLs by what they are ("Instagram's published hijacked-account reporting form, located at help.instagram.com/[path]") not as raw hyperlinks.
- **Inflated dollar figures.** If unsure, under-report. The investigator can ask for more documentation; they can't easily verify exaggerated numbers, and an exaggeration discovered later kills the case.

---

## Required structural elements

Every state AG complaint needs to satisfy the receiving portal's intake requirements, which vary by state. Common required elements across nearly all state portals:

- **Complainant** name, mailing address, phone, email
- **Respondent** legal entity name, mailing address (use the legal-notices address from the platform addendum, not the corporate HQ), state of incorporation
- **Date the issue began**
- **Total dollar amount of harm** (a numeric field; if non-financial, enter `0` and explain in narrative)
- **Has the complainant attempted to resolve directly with the company?** (Always yes — describe the attempts.)
- **Has the complainant filed elsewhere?** (FTC complaint number if applicable, BBB if applicable, prior AG complaints if applicable.)
- **Narrative section** (this is where the bulk of the case-specific writing lives — typically capped at 3,500–5,000 characters)
- **Supporting documents** (uploaded as attachments — generated from the user's documentation package)

Read the user's state's AG complaint portal to confirm specific field requirements. Major state portals (CA, NY, TX, WA, FL, IL) have intake forms with slightly different field structures.

---

## Outline-first protocol (REQUIRED for this document)

Before writing the complaint, produce a structured outline and present it to the user for confirmation. The outline must include:

1. **The case-summary sentence** — one sentence the investigator could quote. ≤30 words.
2. **The 3 facts that will most move the investigator**, in order of importance. For each, the user-provided evidence that backs it.
3. **The dollar harm figure**, with how it's calculated.
4. **The specific platform team requested for forwarding** (e.g., "Meta Platforms government affairs office").
5. **The single sentence in the planned complaint most likely to be challenged** by the platform's response — flagged so the user can verify it's airtight before sending.

Do not write the prose complaint until the user has reviewed the outline and confirmed each element. This step catches hallucinated claims at outline stage rather than at finished-document stage. It is non-negotiable for state AG complaints.

---

## After the user has the complaint

Walk them through:

1. **Where to file.** Search "[user's state] attorney general consumer complaint" or direct them to the correct portal URL. Do not assume the URL — verify it via web search if available, otherwise instruct the user how to find it.
2. **What to attach.** The full documentation package built earlier (see `documentation-package-checklist.md`). Most state AG portals accept PDF and image attachments.
3. **What to expect.** State AG complaints typically take 21–35 days for a response. The response is usually "your complaint has been forwarded to the company; we are awaiting their reply." Then nothing visible happens for another 2–3 weeks. Then, often, the account is silently restored.
4. **Confirmation tracking.** The user should save the complaint reference number from the portal acknowledgment. Subsequent communications with the AG, the platform, and any attorney will reference it.
