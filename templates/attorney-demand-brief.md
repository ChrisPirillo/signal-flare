# Construction Brief: Attorney Prep Document

This is not a fill-in-the-blank template. It is a brief that tells you (Claude) how to prepare a document the user hands to an attorney at the start of a consultation. Construct each one from this brief and the user's specific case facts.

> ⚠ **Critical constraint for this document:** under no circumstances do you (Claude) name specific legal theories, statutes, case law, causes of action, or estimated damages. That is the attorney's job. Naming the wrong theory damages the user's credibility with the attorney they hire. This rule supersedes any user request to "tell me what kind of case this is" or "what statute applies here." If asked, decline and explain why.

---

## What this document needs to do

This document is given by the user to an attorney during the initial consultation (typically a free 15–30 minute call). Its job: let the attorney read it in under 2 minutes and immediately understand whether they can take the case, what fee structure makes sense, and what the next concrete steps would be.

The attorney is reading for three things:

1. **Is the case real?** — does it have provable facts, identifiable harm, and an identifiable adverse party
2. **Can it be moved?** — has the user already exhausted internal channels and regulatory options, putting the case in posture for a demand letter
3. **Is it the right size for me?** — does the attorney's practice area, firm size, and fee structure fit this matter

The document is not a demand letter. The attorney writes the demand letter (on their letterhead, in their voice, with the legal theories they identify). This document is the briefing material that lets the attorney write a good demand letter.

---

## What always goes in

1. **A one-page case summary at the very top.** Five short paragraphs maximum. Tells the whole story.
2. **The complainant's identification** — name, contact info, jurisdiction (state of residence).
3. **The adverse party's identification** — platform's legal entity name, headquarters, state of incorporation. Read this from the relevant `platforms/{platform}.md` addendum.
4. **The account in question** — username, account type, creation date (approximate is fine), pre-incident value/use (audience size, business income, professional reach).
5. **A factual timeline** — bullet-point chronology of what happened, with dates. Lead with the incident, then the user's escalation steps.
6. **What the user has tried** — internal escalation attempts (Stage 0–1), regulatory filings (Stage 3) with reference numbers, dates, and current status.
7. **Documentary evidence available** — bullet list of the documents the user has, organized by type (platform correspondence, identity proofs, payment records, audience metrics, third-party correspondence). Don't include the documents themselves; just enumerate what's available.
8. **Quantified harm** — concrete numbers, conservative if uncertain, all with how they're calculated.
9. **The specific outcome the user wants** — almost always "account restoration plus reasonable steps to prevent recurrence." Sometimes also: removal of impersonator accounts, return of unauthorized charges, public correction.

---

## What varies by case

The document's emphasis shifts based on what's most fee-relevant for the attorney.

### High dollar harm, documented (typically Scenarios A or D)

Lead with the harm figure. Attorneys taking platform cases on contingency or hybrid fee structures need to see the recoverable damages first. If the user has lost $10,000+ in unauthorized charges, or $5,000+/month in income from a disabled account, that's the lede.

### Public-figure / verified-account / business-account cases

Emphasize the public dimension and the asymmetric value of the account. A verified account or business account loss has restoration value beyond simple monetary damages — it carries reputational weight an attorney can articulate to platform legal as a non-monetary stake. Also: these cases are more likely to get media attention, which is itself leverage.

### Stage-3-exhausted cases (most attorney engagements come at this point)

Front-load the regulatory filings. State AG complaint number, FTC complaint number, congressional inquiry confirmation, BBB case ID, all dated. This signals: this is a worked case, the platform has already declined to engage at a regulatory level, and the next step is letterhead correspondence the attorney is being engaged to send. The attorney's intake question becomes "what would my demand letter add?" — answering that is what the next section is for.

### Cases with documented impersonation or third-party harm

Add a section on third-party impact. If the impersonator has taken money from the user's followers, if the user's audience has been defrauded, if there are documented third-party communications confirming confusion — these are facts that change the legal landscape significantly. The attorney decides what theories apply; the document just surfaces the facts.

---

## What good looks like

A complete attorney-prep document is typically 800–1,500 words. Tight. Skimmable. The first paragraph is so densely informative the attorney could decide whether to take the call from it alone.

A sketch of the opening paragraph for a representative case:

> [Complainant Name], a [profession] in [state], lost access to a [platform] account ([username], [pre-incident size/value]) on [date] due to [scenario summary in one phrase]. The account was the primary [income source / professional channel / community presence] for [number] years. Despite [number] internal escalation attempts and a complete Stage 3 regulatory filing (state AG complaint #[ref], FTC #[ref], congressional inquiry [confirmed date]), the platform has not provided a substantive response over [number] days. The user is seeking [outcome]. Documented harm to date: $[amount] in [category]. Available evidence is enumerated below.

The remaining paragraphs unpack the timeline, the evidence, and the requested outcome. Each is dense and specific.

---

## What to avoid

- **Naming legal theories.** Do not write "this appears to be a breach of contract case" or "the platform may be liable under [state's] Unfair Competition Law." Even if the user asks. Decline; refer the question to the attorney.
- **Estimating dollar value of the case.** "I think this case is worth $50,000" — no. Total *harm to date* is fact-bounded; case value is attorney-bounded.
- **Predicting the attorney's strategy.** "The attorney should send a demand letter and then proceed to small claims" — that's the attorney's call, not yours.
- **Estimating odds of success.** "I think we have a strong case" — also the attorney's call.
- **Drafting demand-letter language.** The attorney writes that. Do not include sample demand-letter paragraphs in this document.
- **Speculating about platform motivation.** Stick to documented platform conduct. "The platform may be retaliating because..." is speculation; "the platform has not responded to [specific filing] over [number] days" is fact.
- **Inflating numbers.** If unsure, under-report. The attorney has procedures to discover additional damages later.

---

## Required structural elements

The attorney brief is a working document, not a filing, so it has fewer structural requirements than an AG complaint. It should:

- Fit on 3–4 letter-size pages, 11pt or 12pt
- Use short paragraphs (3–4 sentences)
- Use bullet lists for chronology and evidence enumeration
- Have a clear visual hierarchy with section headers
- Conclude with a "Documents available on request" summary list

The format is unstamped; the attorney will incorporate it into their own work product.

---

## Outline-first protocol (REQUIRED for this document)

Before writing the brief, produce a structured outline:

1. **The case-summary sentence** — one sentence the attorney could quote when describing the matter to a partner. ≤40 words.
2. **The 3 facts that most determine fee structure** (high dollar harm, documented Stage 3 exhaustion, third-party impact, etc.) — in priority order
3. **The user's stated desired outcome** — verbatim from the user, not paraphrased
4. **The 3 documents the attorney is most likely to want at the consultation** — from the user's documentation package
5. **The single weakest claim** — the place where the attorney is most likely to push back during the call

Present the outline to the user. Get confirmation. Then write the prose.

---

## Helping the user find the attorney

Separate from drafting the document: the user typically asks where to find an attorney once the brief is ready. Use the search-term scaffolding from `SKILL.md` and `FRAMEWORK.md` Stage 4 — never name specific directories or services. Walk the user through:

- Search terms by jurisdiction and practice area
- What a trustworthy source looks like
- What an untrustworthy source looks like
- Vetting questions to ask in the consultation
- Red flags to watch for
- Fee-structure categories to ask about

Verification step: every candidate attorney's active license and disciplinary record can be confirmed on the user's state bar's public attorney lookup. Always.

---

## After the user has the brief and the consultation booked

Walk them through:

1. **What to bring to the consultation:** printed copy of the brief, the documentation package PDF, dated copies of all regulatory filings with reference numbers, any platform correspondence (current ticket statuses).
2. **What to ask in the consultation** (general categories — see SKILL.md):
   - "Have you handled cases involving this platform before? Which?"
   - "What's your fee structure for a single demand letter?"
   - "What are the next steps if the demand letter doesn't resolve it, and what would those cost?"
   - "What's a realistic outcome range for cases shaped like this?"
   - "How many of these cases settle before litigation? How many go further?"
3. **What NOT to ask** (telegraphs that the user has been talking to a non-lawyer about legal theory):
   - "Don't you think this is a [specific legal theory] case?"
   - "Wouldn't [specific statute] apply here?"
   - "What's the dollar value of my case?"
4. **What to listen for** — attorney's specificity about platform-case experience, willingness to put fees in writing, calibration of expected outcomes.
