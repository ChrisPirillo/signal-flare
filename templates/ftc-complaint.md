# Construction Brief: FTC Complaint

This is not a fill-in-the-blank template. It is a brief for constructing a complaint to the Federal Trade Commission's consumer complaint system (ReportFraud.ftc.gov).

> ⚠ **Before this is filed:** the user is asserting facts to a federal regulator. Verify each factual claim. FTC complaints are searchable by federal and state regulators and become part of the FTC's data set.

---

## What this document needs to do

An FTC complaint serves a different purpose than a state AG complaint. The FTC does not typically act on individual cases — it aggregates complaints and acts when a pattern emerges. The user's complaint adds one data point to a larger picture.

Two outcomes:

1. **The user's case becomes part of an FTC enforcement matter.** Rare, but real — FTC cases against major platforms are built from accumulated complaints. The user's may be the case that pushes a pattern past the threshold for action.
2. **The complaint reference becomes evidence in other filings.** State AG offices, congressional staff, and attorneys all reference FTC complaint numbers as part of regulatory exhaustion documentation. The number itself is leverage.

The audience is FTC complaint-intake software (the form is structured) and, eventually, FTC analysts looking for patterns. Tight, factual, scenario-categorized writing is what gets the data point indexed correctly.

The platform is largely the same: ReportFraud.ftc.gov. The form is structured with required fields. Free-text sections are limited.

---

## What always goes in

The FTC's intake form has structured fields the user must complete. The construction brief mostly applies to the free-text sections.

1. **Complainant identification.** Real name, address, phone, email — all collected by the form.
2. **Respondent identification.** Platform's legal entity name. The form has a company-search function; verify the entity matches the relevant `platforms/{platform}.md` addendum.
3. **Category selection.** The form asks the user to categorize the complaint. For account-recovery cases, common appropriate categories include:
   - "Online Services" (for general platform issues)
   - "Online Shopping" (for billing-related issues)
   - "Imposter Scams" (for impersonation)
   - "Identity Theft" (for hijacked accounts where the hijacker has used the account for fraud against third parties)
   The category determines downstream routing. Pick the one that best matches; do not multi-categorize unless the form allows.
4. **Date the issue began.**
5. **Dollar harm if any.**
6. **A free-text narrative.** Typically 1,000–2,000 character limit. This is where the construction brief matters most — concise, factual, scenario-specific writing.

---

## What varies by case

### Hijacked accounts where the hijacker has defrauded third parties (Scenario A with third-party harm)

This is the strongest FTC case posture. Categorize as "Identity Theft" or "Imposter Scams" depending on specifics. Lead with the third-party harm: "The party in control of my account has used it to solicit and receive $[amount] from my followers under false pretenses." This puts the case in an FTC-relevant frame (federal consumer fraud) rather than a platform-dispute frame.

### Billing / unauthorized charges (Scenario D)

Categorize as "Online Shopping" or, for financial-services platforms, also file with the CFPB in parallel. Lead with the dollar amount. The FTC tracks unauthorized-billing patterns across platforms and acts on them periodically.

### Banned-for-cause cases (Scenario B) where the platform's basis is provably wrong

These are weaker FTC cases — the FTC does not typically intervene in platform content moderation. File anyway for the reference number and pattern data, but expect no individual case action. Categorize as "Online Services" or, if platform-specific, the closest fit.

### Lockout cases (Scenario C)

Categorize as "Online Services." Frame as a consumer service-deprivation issue. The FTC has occasionally pursued enforcement against platforms for systematic service failures; individual lockouts feed that data set.

### Impersonation (Scenario E)

Categorize as "Imposter Scams." The FTC has dedicated tracking for imposter accounts. Provide URLs and screenshots of the impersonator account; the FTC's intake system can index these.

---

## What good looks like

The free-text narrative is short — 1,000–2,000 characters max, depending on the form's current limit. Get the case across in 2–3 paragraphs.

A representative narrative:

> I am the verified owner of [Platform] account [@username], created [year], with [size]. On [date], my account was [scenario]. I documented the issue to the platform on [date] through [their stated reporting channel] and provided [evidence types]. The platform has not provided a substantive response over [N] days.
>
> The harm to me totals approximately $[amount], composed of [breakdown — unauthorized charges, lost income, replacement costs, etc.]. [If applicable: third parties have also been harmed: [brief description].]
>
> I have filed parallel complaints with the [state] Attorney General [#reference if filed first, or "concurrently"] and have submitted a formal legal notice to [platform's legal entity] on [date]. The platform's continued inaction in the face of documented evidence motivates this filing.

Then the form's structured fields capture the rest.

---

## What to avoid

- **Multi-issue narratives.** The FTC's pattern-detection benefits from clean single-issue cases. Don't bolt on multiple complaints into one filing.
- **Naming legal theories.** Same constraint as everywhere else. The FTC has its own categorization; don't try to predict it.
- **Threats or demands.** The FTC is a regulator, not a negotiator. The complaint reports facts; it does not demand outcomes.
- **Inflated numbers.** FTC analysts cross-reference complaint data. Inflated dollar figures get caught.
- **Personal opinions about Big Tech.** The narrative is the case, not the user's worldview.

---

## Required structural elements

The FTC form structure is fixed; the user fills the fields the form asks for. The construction brief governs the narrative section. Required:

- Complainant identification fields (form-required)
- Respondent identification (legal entity name)
- Date issue began (form-required)
- Dollar harm (form-required, can be 0)
- Category selection (form-required)
- Narrative (≤ form's character limit; aim for 1,000–1,500 characters typical)

---

## Outline-first protocol (REQUIRED for this document)

Before writing the narrative, produce an outline:

1. **The category that best matches the case** — pick one, with reasoning.
2. **The case-summary sentence** — one sentence that captures the FTC-relevant aspect of the case.
3. **The dollar harm figure** with how it's calculated.
4. **The third-party harm** if any (this is what often elevates an individual case to FTC relevance).
5. **The most pattern-relevant fact** — the detail most likely to match other complaints already in the FTC's data set.

Present the outline to the user. Get confirmation. Then write the narrative.

---

## After the user files

Walk them through:

1. **Save the FTC complaint reference number.** It will be cited in subsequent state AG and congressional filings.
2. **Don't expect a personal response.** The FTC rarely contacts individual complainants about specific cases. The complaint becomes part of their data set.
3. **The reference number is the leverage.** State AG, congressional, and attorney correspondence references it. Even without an FTC response, the number signals federal regulatory exposure to the platform.
4. **For financial cases, file with CFPB in parallel.** PayPal, Cash App, Venmo, financial-services-related billing — these have parallel CFPB jurisdiction. The CFPB does, in many cases, contact platforms about individual cases.
