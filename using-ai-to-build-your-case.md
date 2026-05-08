# Using AI to Build Your Case

A practical, stairstep guide for using an AI assistant (Claude, ChatGPT, Gemini, or any modern large language model) as a thinking partner while you work through this framework.

> **Who this guide is for:** people who want to use a general-purpose AI chat (claude.ai, chatgpt.com, gemini.google.com, or similar) to help them work through their account-recovery case. **If you're using the `signal-flare` skill installed in Claude, you don't need this guide** — the skill does the work this guide describes, conversationally, without you having to copy-paste prompts. This guide exists for users who don't have the skill installed (or who are using a different AI provider) and want to replicate what the skill does.

This is **optional but genuinely helpful**. The framework works without AI. But for someone in distress with a messy pile of evidence and a 3,500-character AG complaint to write, an AI assistant can compress days of work into hours.

---

## Never used an AI assistant before? Start here.

If you're not sure what "Claude" or "ChatGPT" or "Gemini" actually is, this section is for you. Skip it if you've used these tools before.

**An AI assistant is a website (or phone app) where you type a question and get a written answer back.** It looks like text-messaging with someone who is good at writing and has read a lot of books, but isn't a real person. You can also paste large amounts of text into it and ask for help organizing, summarizing, or rewriting that text.

Three of the most common ones, all free for basic use:

- **Claude** — go to `claude.ai` in your web browser. Click "Sign up" or "Continue with Google" if you have a Google account. (There is also a Claude phone app on the App Store and Google Play.)
- **ChatGPT** — go to `chatgpt.com`. Click "Sign up" or sign in. (Phone apps available too.)
- **Gemini** — go to `gemini.google.com`. Sign in with a Google account. (Phone app on Android, web on iPhone.)

You only need one. Pick whichever is easiest for you.

**How to start a conversation:**

1. Open the website or app.
2. You'll see a big text box, usually at the bottom of the screen, that says something like "Ask anything" or "Message Claude."
3. Click in the box. Paste or type your prompt.
4. Press Enter (on a keyboard) or tap the up-arrow / send button (on a phone).
5. Wait a few seconds. The AI will write back in the same window. Read it. Ask a follow-up by typing in the same box.

**That's it.** Each session is one long conversation. Everything you type and everything the AI types is visible scrolling up the page.

**If you've never copied and pasted text on a phone:** press and hold on a block of text until a menu pops up. Tap "Copy." Open the AI app, press and hold in the message box, tap "Paste." You can do this with everything in this framework.

**If a chat gets messy or confused, start a new one.** There's usually a "New Chat" button in the corner. Each new chat starts fresh — the AI doesn't remember the old one. That's a feature, not a bug.

---

## What AI is good at (and what it isn't)

**AI can help with:**

- Extracting a clean timeline from unstructured ticket history, email threads, and screenshots
- Identifying what's evidence vs. what's noise in your documentation
- Drafting tight harm narratives that fit character limits
- Catching gaps in your documentation package
- Re-writing your case in different registers (formal for legal notice, plain English for AG complaint, technical for attorney brief)
- Stress-testing your case from the platform's perspective ("what would the platform's lawyer argue?")
- Identifying patterns in your evidence you might have missed
- Translating platform jargon, ToS language, or legal terms

**AI is unreliable for:**

- Current platform contact information (URLs, emails, phone numbers — these change frequently and AI training data is often outdated)
- Specific platform policies (always verify against the platform addendum or the platform's actual current policy page)
- Legal advice (AI is not a lawyer; it cannot tell you what your case is worth, what your odds are, or what to do)
- Specific regulatory rules in your state (consumer protection law varies by state)
- Specific case law or court precedent (AI hallucinates citations confidently)

**Hard rule: anything an AI gives you that involves a URL, email address, phone number, statute citation, court case, or specific dollar threshold — verify against an authoritative source before relying on it.**

---

## Privacy: what to paste, what NOT to paste

AI services generally retain some logs of what you paste into them. Most major providers do not train on your conversations by default in their consumer products as of 2026, but that's not a guarantee, and policies change.

For a case involving a hijacked account, you have unusual privacy risk.

### Safe to paste

- The platform name, your username/handle, the incident date
- Your harm narrative, dollar harm estimates, timeline
- The platform's ticket replies (already public to anyone who has the ticket)
- Your draft templates with placeholder data
- General questions about the framework or your scenario

### Pause before pasting

- Your real full legal name (use [Your Name] in drafts; substitute at the end)
- Your full mailing address (use [Address])
- Bank statements with full account numbers, transaction IDs, or balances
- Card statements with full card numbers
- Government ID images or numbers
- Your old account email (if you suspect the email itself is compromised)
- Other people's contact information that appears in screenshots
- Anything that, if leaked from the AI service to a third party, would make your situation worse

### Never paste

- Account passwords, even old ones
- Full credit card numbers, CVVs, or banking PINs
- Social Security Numbers, Tax IDs, passport numbers
- Multi-factor authentication backup codes
- Recovery phrases for crypto wallets or password managers
- Private keys, API tokens, or session cookies
- Any other secret that would compromise an account or identity if leaked

A reasonable rule of thumb: if it's something you'd cover with your hand on a public bus, don't paste it into an AI service.

### Practical privacy workflow

1. Make a working copy of your evidence with sensitive details redacted (use `[REDACTED]` placeholders)
2. Paste the redacted version into the AI for help drafting
3. Substitute your real details back in only on your own machine, in the final version you'll send

This is the same discipline you'd use sharing a draft with a friend who didn't need to see your card number.

### Worked example: what redaction looks like

Here's a single ticket reply from a fictional platform. Pretend this is what's in your inbox.

**BEFORE redaction (do not paste this version into AI):**

```
From: support@example-platform.com
To: jane.smith.real.email@gmail.com
Date: April 3, 2026
Subject: Re: Account jsmith — recovery request #4471

Hi Jane,

Thanks for contacting us. We see your account jsmith was registered to
1247 Maple Street, Apt 3B, Seattle, WA 98101.

To verify ownership, please reply with the last 4 digits of the credit card
on file (you said it was a Visa ending in 4729) and your government ID.

— Support
```

**AFTER redaction (paste THIS version into AI):**

```
From: support@[PLATFORM]
To: [MY_EMAIL]
Date: April 3, 2026
Subject: Re: Account [MY_USERNAME] — recovery request [TICKET_NUMBER]

Hi [MY_FIRST_NAME],

Thanks for contacting us. We see your account [MY_USERNAME] was registered
to [MY_ADDRESS].

To verify ownership, please reply with the last 4 digits of the credit card
on file (you said it was a [CARD_BRAND] ending in [CARD_LAST_4]) and your
government ID.

— Support
```

**Notice what stayed and what changed:**

- ✅ Date stayed (it's not personally identifying)
- ✅ Ticket structure and language stayed (the AI needs that to help you draft a reply)
- ❌ Real name, email, address, username, ticket number, card brand, card digits — all replaced with placeholders in `[BRACKETS]`
- ❌ Even the platform name was placeholder-ed if you want extra caution (the AI doesn't need to know which platform to help you write a clean reply)

When the AI gives you a draft back, it will use the same placeholders. **You do the final substitution on your own computer**, in your own document, before sending. The AI never sees the real values.

If you have a long thread of messages, redact them in a text editor first using Find & Replace before pasting:

- Find: `Jane Smith` → Replace with: `[MY_NAME]`
- Find: `jane.smith.real.email@gmail.com` → Replace with: `[MY_EMAIL]`
- Find: `1247 Maple Street, Apt 3B, Seattle, WA 98101` → Replace with: `[MY_ADDRESS]`
- Find: `4729` → Replace with: `[CARD_LAST_4]`

This takes 5 minutes. It is the single most important habit on this whole page.

---

## Setup: starting your AI conversation

Most general-purpose AI assistants work for this. Paste this system prompt at the start of a fresh conversation to set the assistant up correctly:

```
I'm working through an account recovery case for [PLATFORM_NAME]. The scenario is [hacked / banned / locked out / billing dispute / impersonation].

I'm using a structured framework with five escalation stages: stop the bleeding, internal channels, asset preservation, regulatory pressure, and attorney demand letter.

I'd like you to act as a calm, structured thinking partner who helps me:
1. Organize my evidence into a clean documentation package
2. Build a clear timeline from messy raw materials
3. Draft tight, factual templates for each escalation stage
4. Stress-test my case for weaknesses before I send anything

Important constraints:
- You are not a lawyer. Don't give legal advice; flag anything that requires an attorney.
- Don't invent platform contact information, URLs, email addresses, statutes, or case law. If I need a current URL or email, tell me to verify it from the platform's actual website.
- Be direct about gaps in my evidence. Don't reassure me prematurely.
- Keep the tone calm and factual. I'm stressed; help me write like I'm not.

I'll paste my evidence and drafts as we go. Let's start with what you need from me to be useful.
```

The assistant will typically respond by asking what you have so far. From there, walk through the stages below.

---

## Stage-by-stage AI usage

### Stage 0: Stop the bleeding

**Use AI to:**

- Build a triage checklist for your specific scenario. Prompt: "Given that my [scenario] just happened, what are the three things I should do in the next hour? Order them by priority."
- Decide whether to warn your audience publicly. Prompt: "I have [N] followers on [platform]. Help me think through whether to post a public PSA, what to include, and what to leave out."
- Draft your first community announcement. Prompt: "I need a 280-character X post warning my followers that my account was [hijacked/banned]. Tone should be calm, factual, no panic."

**Don't use AI to:**

- Guess at the right URL for the platform's compromised-account form. Always verify against the platform addendum.

---

### Stage 1: Internal channels — Build the documentation package

This is where AI saves the most time.

**Workflow:**

1. **Dump everything.** In a single AI conversation, paste in:
   - Every email from the platform (you can copy/paste the body text — strip your real email address if you want)
   - Every reply from the platform's support
   - Your own notes about what happened, in whatever order they came to you
   - Screenshots' contents (transcribe what's in them, or paste text recognized via OCR)

2. **Ask for a structured timeline:**

```
Here is everything I have from the past [N] days about my [PLATFORM] account issue. Some of it is in chronological order, some isn't. Some details may be redundant.

Build me a clean dated timeline using this format:

YYYY-MM-DD, HH:MM TZ — [event]

Group by event type when helpful (e.g., "Platform notifications received," "My actions taken," "Platform support responses"). Flag any apparent gaps or inconsistencies.
```

3. **Ask for a documentation gap analysis:**

```
Based on what I just gave you and the standard documentation package checklist (identity proof, ownership proof, incident timeline, platform-generated emails, harm statement, platform support correspondence) — what's missing? What evidence should I gather that I haven't yet?
```

4. **Ask for a harm narrative draft:**

```
Help me write a 4–8 sentence harm narrative based on what I've shared. Be specific with dollar amounts and concrete impacts. Don't add any harm I didn't actually mention. Tone: factual, not emotional.
```

5. **Iterate:**

```
This draft includes [X] which actually didn't happen. Remove it. Also, add that [Y] happened on [date] — that's an important harm I forgot to mention.
```

The AI is your editor, not your reporter. It can only work with what you give it.

---

### Stage 1: Internal channels — Draft the reconsideration ticket and legal notice

Once you have the timeline and harm narrative:

```
Using the [internal-reconsideration / legal-notice] construction brief from the framework (a guide for what the document should do, what always goes in, and what varies by case scenario — not a fill-in-the-blank template), draft a personalized version using these facts:

[paste the relevant sections of your timeline and harm narrative]

[paste any specific evidence references]

Keep the tone calm and professional. Don't make claims I haven't supported with evidence.
```

After the draft:

```
Now play the role of [PLATFORM]'s legal team reading this. What would your three biggest objections be? What would you ignore? What would you respond to first?
```

This is the most valuable single AI prompt in the framework. **It catches weaknesses before a regulator does.**

---

### Stage 2: Asset preservation

**Use AI to:**

- List the data exports available for your platform (then verify against the platform addendum and the platform's actual current settings)
- Brainstorm your audience touch points beyond the affected platform: "If I have a Patreon, a newsletter, and three other social accounts, what's the right sequence to message each to migrate followers?"
- Draft outreach to community moderators or co-admins to pre-position alternates

**Don't use AI to:**

- Provide direct download links for data export tools — verify against the platform's actual settings menu

---

### Stage 3: Regulatory pressure — The state AG complaint

This is where character limits matter most.

```
My state AG's complaint form has a [3,500] character limit for the narrative section. Using the state-ag-complaint construction brief and the facts below, draft a complaint that fits the character limit.

[paste timeline, harm narrative, ticket history, your state]

The first sentence should establish I'm a resident of [STATE]. The rest should follow the brief's guidance on what always goes in, what varies for my scenario, and what to avoid. Cut anything not strictly necessary to fit the character limit.
```

After the draft:

```
Tell me three things that, if removed, would make this stronger by being shorter. And tell me three things that are missing that I should consider adding if I have room.
```

For the FTC complaint and congressional letter, similar workflow with shorter limits.

---

### Stage 3: Where to file

**Use AI to:**

- Identify which state AG portal applies based on your state of residence
- Identify your federal House Representative based on your address
- Identify the type of agency to contact for platform-specific issues (CFPB for financial platforms, FCC for telecom, etc.)

**Don't use AI to:**

- Provide the actual URL for your state's AG portal — search for it directly. AI can be weeks or years out of date on URL changes.
- Provide your representative's actual email or contact form URL — get it from house.gov or senate.gov directly.

---

### Stage 4: Attorney engagement

**Use AI to:**

- Draft your attorney brief (the document you give the attorney, not the demand letter itself)
- Prepare your questions for the initial consultation
- Translate your case into the legal-theory language an attorney will recognize
- Stress-test the strength of various legal theories before the call

**Don't use AI to:**

- Generate the demand letter itself for you to send unsigned. The leverage of a demand letter comes from being on attorney letterhead, signed by an attorney with bar credentials. A self-sent letter pretending to be from an attorney is unauthorized practice of law and can hurt your case.
- Tell you which attorney to hire. Use the guidance in `FRAMEWORK.md` and `templates/attorney-demand-brief.md` for how to search for candidates and what to look for.

---

### Stage 5: Litigation

If you're at this stage, you have an attorney. Stop using AI for substantive case work — your attorney is your assistant now, and AI advice can conflict with their strategy. Limit AI use to organizational help (timeline updates, document indexing).

---

## Across all stages: stress testing

After every draft, before you send anything:

```
You're now a hostile reviewer reading this. Find every weakness. List:
1. Anything that sounds emotional, exaggerated, or unsubstantiated
2. Any factual claim I can't back up with documents I've shared
3. Any internal contradiction with my timeline
4. Anything missing that a regulator/attorney would expect to see
5. Anything that an attorney for the platform would seize on to push back
```

Iterate until the AI has no more substantive critiques. Then iterate one more time.

---

## What to do if AI tells you something that doesn't match the framework

The framework is the source of truth. If an AI gives advice that contradicts:

- A platform addendum's documented contact, channel, or process
- The framework's stage ordering
- The decision tree's scenario routing
- A template's recommended language

Trust the framework documents over the AI. The framework was written by humans with verified information; the AI is generating plausible-sounding text and may be wrong.

If you find a real conflict where the framework seems wrong, [open an issue](CONTRIBUTING.md#reporting-a-problem) — the framework gets corrected, and everyone benefits.

---

## What to do if the AI gets confused or unhelpful

This will happen. Here's how to recover.

**The AI gives you something that doesn't sound right, or feels generic:**
- Be more specific. Replace "help with my case" with "draft a 200-word ticket reply for [PLATFORM] using these specific facts: [paste 3-5 bullet points of facts]."
- Tell the AI what's wrong with the draft. "This sounds emotional. Make it factual." or "You included a harm I didn't actually mention — remove it."
- Ask the AI to explain its reasoning: "Why did you write that paragraph? What evidence are you basing it on?"

**The AI invents facts that aren't in your case:**
- Stop. Tell it directly: "You added [X]. I never said [X]. Remove it and draft again using only what I gave you."
- If it keeps inventing, paste your facts back in a numbered list and tell it: "Use only these 8 facts. Nothing else. Anything else is wrong."

**The AI gives you a URL, email, or phone number:**
- Don't trust it. AI training data is months or years out of date. Always verify the contact information against the platform's actual current website or the platform addendum in the framework.
- Tell the AI: "Don't give me URLs or contact info — only help me draft the message."

**The AI's answer is too long, or it's adding sections you didn't ask for:**
- Tell it the format you want: "Reply in 4 sentences. No headers. No bullet points. Plain paragraph form."
- Tell it the length: "Maximum 280 characters." or "Under 500 words."

**The AI sounds robotic or formal in a way that doesn't match the situation:**
- Give it a tone instruction: "Write this in plain, calm English. Don't use words like 'pursuant,' 'aforementioned,' or 'hereby.' I'm a regular person, not a lawyer."

**The AI keeps repeating itself or going in circles:**
- Start a new chat. Paste a fresh, organized summary of where you are. Don't try to drag the confused conversation along.
- Sometimes a fresh start with a tighter prompt is faster than fixing a tangled one.

**The AI refuses to help, citing legal advice or "harmful" topics:**
- Reframe the request as drafting documents based on your own facts (which is what's actually happening) rather than asking for advice.
- Make clear you are the legitimate account owner and following an established framework for legitimate disputes.
- Switch assistants — different services have different sensitivity calibrations. Claude, ChatGPT, and Gemini all have different defaults.
- Fall back to using the framework templates directly without AI help.

**You're not sure if the AI's answer is good or bad:**
- Ask the AI to grade itself: "Pretend you're a hostile critic. Find three weaknesses in what you just wrote."
- Or: "Pretend you're [PLATFORM]'s in-house lawyer. What's the weakest part of this draft?"
- The AI will often expose problems it created itself in the previous answer.

The framework works without AI. AI just makes it faster — and only when it's actually working *with* you, not generating filler. If a session goes off the rails for more than 10 minutes, close it and start fresh.

---

## A note on AI hallucinations

Even the best AI assistants sometimes generate plausible-looking but false information — hallucinations. Common ones for this use case:

- Made-up platform email addresses (often follow the pattern `support@[platform].com` or `legal@[platform].com` even when those don't exist or aren't monitored)
- Made-up support URLs that don't go anywhere
- Fabricated case citations or statute numbers
- Confident statements about platform policies that changed last year
- Claims about specific dollar limits or thresholds that don't match the actual law in your state

The single best defense is verification. **Anything from the AI that involves a URL, email, phone number, citation, or specific number — check it against an authoritative source before you use it.**

---

## A final reframe

Using AI for this isn't a shortcut around doing the work. It's a force multiplier on the work you're already doing. The framework is yours. The evidence is yours. The AI just helps you organize it faster.

If at any point the AI is doing something you can't follow, stop. Re-read the relevant framework document. Resume only when you understand what's being drafted on your behalf. You have to be able to defend every word in your AG complaint, your legal notice, and your attorney brief — even the parts the AI helped write.

You're the one whose name is on the paperwork. The AI is just helping you write it more cleanly than you would alone.
