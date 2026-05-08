# Construction Brief: Legal Notice to Platform

This is not a fill-in-the-blank template. It is a brief for constructing a formal notice from the user (acting as their own representative, not as an attorney) to the platform's legal-notices address. Construct each one from this brief and the user's specific case facts.

> ⚠ **Before this is sent:** the user is asserting facts that will be read by the platform's legal team and may end up referenced in subsequent regulatory filings. Verify every factual claim against their evidence first. Any inflated or unverifiable claim becomes a credibility problem in every later stage.

---

## What this document needs to do

A pro se legal notice (sent by the user, not by an attorney) serves two purposes:

1. **It moves the case out of the support queue and into the legal/compliance queue.** Most platforms route correspondence sent to their legal-notices email — published on their site for receipt of subpoenas, DMCA notices, and regulatory inquiries — to a different team than support. That team has authority and incentive to resolve cases before they generate further regulatory exposure.
2. **It builds the paper trail for Stage 3.** A documented legal notice — with a delivery receipt — is required content in subsequent state AG and FTC complaints. Without this step, regulatory filings can be dismissed as premature ("did you contact the company directly?").

The notice is written by the user, not an attorney, and should not pretend to be from an attorney. Pretending to be represented when you're not is poor strategy and may be unauthorized practice issues. The notice's authority comes from its precision and procedural posture, not from a fake letterhead.

---

## What always goes in

1. **Sender identification.** User's real legal name, mailing address, and a contact email (not the email associated with the disputed account, which may be inaccessible). Date of the notice.
2. **Recipient identification.** Platform's legal entity name and legal-notices address — read from the relevant `platforms/{platform}.md` addendum. Send to the legal-notices email AND, for higher-stakes cases, also send via certified mail to the legal entity's HQ. Both receipts get cited in subsequent regulatory filings.
3. **Subject line that signals legal posture.** "Formal Notice — Account Recovery, [Username]" or "Notice of Continued Inaction — Account Restoration Required." Avoid the word "complaint" (signals support routing) and avoid "demand letter" (signals attorney representation, which is misleading if the user isn't represented).
4. **A factual recitation.** Same factual content as the AG complaint will eventually contain, but in slightly more formal register. Dated events, ticket numbers, platform responses (or non-responses), evidence the user has.
5. **A statement of the platform's failure.** What specifically the platform has failed to do, with reference to the platform's own published policies or commitments where applicable. This is the framing that distinguishes this from "I'm unhappy" — it's "the platform's own stated process has failed in this specific way."
6. **A specific cure period.** Typically 14 days from receipt. "If this matter is not substantively addressed within 14 days, I will pursue regulatory remedies, including but not limited to filing complaints with the [state] Attorney General, the Federal Trade Commission, and my congressional representatives." This is fact (the user *will* do this), not threat.
7. **A request for written response.** "Please provide a substantive written response to this notice referencing my case [reference number]."
8. **The user's signature block.** Full name, no fake credentials, contact info.

---

## What varies by case

### High-stakes verified or business cases

Add a short paragraph on the account's professional/business significance and the operational harm of continued inaction. Do not threaten litigation; do reference that the harm is escalating and quantifiable. The platform's legal team reads this for risk-of-litigation cues; concrete escalating harm signals "this case is going somewhere if not resolved."

### Compromised accounts where the hijacker is still active

Add a separate, clearly-marked paragraph describing the ongoing third-party harm. "The party currently in control of my account has continued to [send unsolicited messages / promote scams to my followers / make purchases on linked payment methods]. Each additional [day/hour] of platform inaction causes additional documented harm to me and to third parties." This makes a continued-failure-to-act argument the platform's compliance team has to take seriously.

### Cases with retracted third-party reports

If the case is built on third-party reports that have been retracted (false copyright claims, retracted abuse reports, withdrawn impersonation claims), state the retraction clearly: "The original [reporting party] has withdrawn the report on [date]. Despite this, the platform has not reversed the resulting account action." This is the strongest possible posture — the platform is failing to act on its own internal data.

### Cases involving financial regulation (PayPal, etc.)

Add a paragraph noting parallel CFPB jurisdiction. "This matter implicates Consumer Financial Protection Bureau oversight in addition to general consumer protection. I will pursue both pathways in the absence of substantive response." For PayPal specifically, this dual-pathway pressure is meaningfully more effective than state AG alone.

---

## What good looks like

A representative legal notice is 400–700 words. Concise, formal, fact-dense. The opening establishes posture; the middle recites facts; the close states cure period and remedies-on-default.

A typical opening:

> Re: Formal Notice — Account Recovery, @[username]
>
> [Recipient legal entity], by service to legal-notices@[platform-domain]:
>
> I am writing to formally notify you that I am the lawful owner of [Platform] account [@username], created [approximate month and year], with [followers / customers / community members]. I have been [denied access / banned / impersonated / charged without authorization] since [date] and have been unable to resolve this matter through your standard support process despite [N] documented attempts. This notice is intended to provide [Platform] a final opportunity to substantively review my case before I pursue regulatory remedies.

Then a chronological factual recitation, then platform-failure paragraph, then cure-period paragraph, then signature.

The tone is professional but not affected. The user is a private individual writing to a corporation about a specific case; they should sound like that, not like a TV lawyer.

---

## What to avoid

- **Pretending to be an attorney.** No fake letterhead, no titles, no claims of representation. The user is writing pro se. Saying so plainly is more effective than implying otherwise.
- **Naming legal theories or statutes.** Same constraint as everywhere else. The notice asserts facts and procedural failures, not legal theories.
- **Dollar demands.** This is not a demand letter. The user is requesting account restoration (or whatever the actual remedy is), not damages. Damages, if pursued, are an attorney's domain or small-claims court.
- **Hyperbole.** "Egregious," "unconscionable," "predatory practices" — all signal an unrepresented complainant trying to sound legal. Use plain factual language.
- **Empty threats.** Don't reference remedies the user isn't actually willing to pursue. State only what the user *will* do — file with state AG, FTC, etc. — and only if the user is actually committed to following through.
- **Multi-issue scope.** One case. One set of facts. Don't reference other users' situations or the platform's "general practices."

---

## Required structural elements

- **Format.** Plain text email and/or printed letter. No fake legal letterhead.
- **Subject line.** Clear, specific, references account.
- **Recipient block.** Legal entity name, address, "By service to: [email]".
- **Body paragraphs.** 4–6 paragraphs typical: introduction, factual recitation, platform-failure statement, escalating harm (if applicable), cure period and remedies, signature.
- **Signature block.** Full legal name, mailing address, contact email, date.
- **Delivery method.** Both email to legal-notices address and certified mail to corporate HQ for higher-stakes cases. Save delivery receipts — they get cited in subsequent regulatory filings.

---

## Outline-first protocol (REQUIRED for this document)

Before writing the notice, produce a structured outline:

1. **The case-summary sentence** — one sentence the platform's legal team could quote.
2. **The single specific platform failure** the notice will assert (failure to respond, failure to act on retracted report, failure to remedy compromise, etc.).
3. **The cure period** (typically 14 days; can be 7 for ongoing harm cases).
4. **The remedies the user is actually willing to pursue on default** (state AG always; FTC always; congressional inquiry usually; small claims if applicable; attorney engagement if applicable).
5. **The single sentence in the planned notice most likely to be challenged** by the platform — flagged so the user can verify it's airtight before sending.

Present the outline to the user. Get confirmation. Then write the prose.

---

## After the user sends the notice

Walk them through:

1. **Save delivery confirmation.** Email auto-acknowledgment is fine; certified-mail receipt is better. Both get cited in Stage 3 filings.
2. **Don't expect a substantive response.** Most platforms acknowledge receipt with an automated reply. Some respond substantively; most don't. Either way, the cure period runs from delivery.
3. **Use the cure-period silence productively.** Stage 3 filings (state AG, FTC, congressional) can be drafted and held during the cure period. The day after the cure period expires without substantive response, file all Stage 3 channels in parallel.
4. **If the platform does respond substantively:** the user evaluates whether it's a real resolution or a delay tactic. If it's resolution: stop. If it's not: file Stage 3 anyway, and reference the platform's response in the filings.
