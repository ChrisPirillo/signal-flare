# Discord Addendum

> **Last verified:** 2026-05-06
>
> **Maintainer:** Initial draft from primary research

---

## Platform identity

- **Legal entity name:** Discord Inc.
- **Headquarters address:** 444 De Haro Street, Suite 200, San Francisco, CA 94107, United States
- **Authorized representative / Chief Legal Officer:** Clint Smith, CLO
- **State of incorporation:** Delaware
- **Phone (general):** 888-594-0085
- **EU subsidiary:** Discord Netherlands B.V., Schiphol Boulevard 195, 1118BG Schiphol, Netherlands
- **Source:** https://discord.com/company-information

---

## Official support channels (Stage 0–1)

- **General support URL:** https://support.discord.com/hc/en-us/requests/new
- **Compromised-account ticket URL:** https://dis.gd/hackedaccount (redirects to the official Trust & Safety form)
- **Ban appeals URL:** https://dis.gd/contact (use the Trust & Safety category for ban appeals)
- **Billing dispute URL:** https://support.discord.com — choose "Help & Support" → "Billing & Payments"
- **MFA recovery (locked out):** https://support.discord.com/hc/en-us/articles/115001221072
- **Server ownership transfer request:** https://support.discord.com/hc/en-us/requests/new?ticket_form_id=360000029212 — select "Help & Support" → "Server Related Requests" → "Server Ownership Transfer Request"

---

## Legal & compliance contacts (Stage 1)

- **Legal notices email:** `legal.notices@discord.com`
- **Source citation:** Discord Master Services Agreement, Section 13.4 — https://support.discord.com/hc/en-us/articles/24774824186263
- **DMCA agent:** https://support.discord.com/hc/en-us/articles/4410339349911-Copyright-IP-Policy

---

## Special-status escalation paths

- **Discord Partner Program:** `partner@discord.com` — separate communication channel for Partnered accounts. Partner Managers (when assigned) can escalate cases to senior Trust & Safety reviewers.
- **HypeSquad / Moderator Programs:** Limited escalation through program-specific channels; not as effective as Partner Program.
- **Verified servers:** Verification team handles verification-related issues; not effective for general account recovery.
- **Server commerce / monetization:** Monetization team handles revenue-related disputes; can sometimes escalate the underlying account.

---

## Known organizational gaps

- **Gap 1: Trust & Safety vs. Account Support.** Hijacked accounts that have been used for ToS violations by the attacker get banned by Trust & Safety. The ban becomes the Account Support team's "reason" for not restoring access, even when the underlying compromise is documented. Neither team owns the reinstatement.
  - **Workaround:** Frame the case as a Trust & Safety request to overturn the ban based on documented unauthorized access, not as an account recovery request.

- **Gap 2: Server ownership transfer denial loop.** Discord's published criteria for transferring ownership of a server when the owner is inactive specify 30+ days of owner inactivity. But Discord's own footnote states "if the previous server owner's account was disabled, the transfer may be denied." This creates a Catch-22 for hijacked accounts: the owner wants their account back, but if Discord disables the hijacked account during the recovery process, the server transfer to an eligible admin gets denied as a side effect.
  - **Source:** https://support.discord.com/hc/en-us/articles/26286635870359
  - **Workaround:** File the server transfer request from the eligible admin (not from the original owner), framing the request as "recovery of a server from unauthorized takeover" rather than "transfer from a banned account."

- **Gap 3: Server destruction has no built-in recovery.** When a server is deleted (whether by owner, by hijacker, or by ToS action), there is no user-facing restoration flow. Trust & Safety can sometimes restore servers within an unofficial 30–45 day window, but there is no published policy or guarantee.
  - **Workaround:** File a server restoration request via the standard ticket system as soon as possible. Most are denied. Some succeed.

---

## Documented patterns of failure

- **Partnered-account hijacking-for-resale:** Documented pattern of attackers targeting Discord Partner accounts specifically because of their commercial value. The Yellow Fellows Partnered server case is a publicly visible example: https://support.discord.com/hc/en-us/community/posts/4413209659031
- **October 2025 Zendesk breach:** Discord disclosed in October 2025 that a third-party customer support vendor (Zendesk) was breached, exposing approximately 70,000 users' data including names, usernames, emails, IPs, and support correspondence. Some hijacking incidents may be downstream consequences of this breach, where attackers used stolen support data to identify and target valuable accounts.
  - **Source:** https://www.malwarebytes.com/blog/news/2025/10/discord-warns-users-after-data-stolen-in-third-party-breach
- **Server-nuke attacks:** When attackers gain access to high-value accounts, scorched-earth destruction of owned servers is a common pattern. Discord has no rapid restoration path.
- **Auto-banning of legitimate users for false-positive ToS detection:** Multiple public reports of accounts banned for "violations" the user did not commit, with appeals receiving only automated rejections.

---

## Regulatory precedents

- **New Jersey AG consumer fraud lawsuit:** April 2026, Discord's removal to federal court was denied; case remanded to state court. The action establishes that state AGs are willing to pursue Discord on consumer protection grounds.
- **EU Digital Services Act compliance:** Discord is registered as a service under the DSA (https://www.lobbyfacts.eu/datacard/discord-inc) and is subject to EU enforcement mechanisms for EU users.

---

## Asset preservation specifics

- **Data export:** Available at User Settings → Privacy & Safety → Request All My Data. Takes ~30 days. Includes account info, server memberships, activity, and (sometimes) message history.
- **Server ownership transfer:** Possible but requires meeting all criteria (100+ members, owner inactive 30+ days, requestor active, requestor has admin/mod permissions, server not monetized).
- **Server restoration:** Unofficial window appears to be 30–45 days. No guarantees.
- **Backup tools:** RestoreCord (https://restorecord.com), Wick Bot, Security Bot — these MUST be installed before a nuke to be useful afterward. They cannot recover what they didn't see.

---

## Public-pressure channels

- **Official X handles:** @discord, @discord_support
- **Official subreddit:** r/discordapp (community-moderated, but Discord staff occasionally respond)
- **Discord's support community (meta-forum):** https://support.discord.com/hc/en-us/community/topics — public posts here are sometimes elevated by Discord staff
- **Discord's public Discord server:** Discord Townhall (invite varies, find via discord.com)

---

## Anti-patterns specific to Discord

- **Don't open multiple tickets.** Discord explicitly says this slows review. Reply to your existing ticket thread instead.
- **Don't try to log in repeatedly from new devices/IPs.** Discord uses login-pattern trust signals; rapid attempts from many sources degrade the platform's ability to verify you.
- **Don't scan QR codes from untrusted sources.** Discord's QR-based login is a known attack vector — scammers can capture session tokens this way.
- **Don't issue chargebacks before opening a Discord billing dispute.** Discord automatically suspends accounts with unresolved chargebacks.
- **Don't pay anyone on Telegram, Reddit, or Fiverr promising "Discord recovery."** These are scams.
- **Don't post invite links to your old (hijacked) server.** Invite links are dead once the server is destroyed; posting them just confuses your community.

---

## Platform-specific harm narrative angles

- **Loss of Partner status** — commercially recognized designation
- **Destruction of community servers** with specific member counts and years invested
- **Loss of monetized server revenue** (Server Boosts, Server Subscriptions)
- **Reputational harm** from phishing DMs sent to professional contacts during compromise
- **Loss of community moderator/admin responsibilities** to other servers (if applicable)
- **Loss of access to verified or partnered communities** the user was a member of (downstream effect)

---

## Templates that need adaptation for Discord

- `internal-reconsideration.md` → reference `dis.gd/hackedaccount` and Trust & Safety
- `legal-notice.md` → cite the MSA Section 13.4 for legal notices address
- `state-ag-complaint.md` → reference Discord's San Francisco HQ and Delaware incorporation
- All templates → for Partnered accounts, cite the Yellow Fellows precedent and (if applicable) the October 2025 Zendesk breach as platform-known patterns

For Discord-specific server destruction cases, use these additional templates:
- `templates/server-transfer-request.md` (specific to Discord — filed by an eligible admin)
- `templates/server-restoration-request.md` (specific to Discord — request to T&S to restore destroyed servers)
- `templates/discord-partner-escalation.md` (specific to Discord Partner Program escalation)

---

## Recent changes log

- **2026-05-06:** Initial addendum created. Reflects October 2025 Zendesk breach disclosure, NJ AG action (April 2026), and current Discord HQ/legal contacts.

---

## Sources & citations

1. Discord Company Information — https://discord.com/company-information — verified 2026-05-06
2. Discord Master Services Agreement — https://support.discord.com/hc/en-us/articles/24774824186263 — verified 2026-05-06
3. Discord Server Ownership Transfer Article — https://support.discord.com/hc/en-us/articles/26286635870359 — verified 2026-05-06
4. Discord Hacked Account Article — https://support.discord.com/hc/en-us/articles/24160905919511 — verified 2026-05-06
5. Discord MFA Recovery Article — https://support.discord.com/hc/en-us/articles/115001221072 — verified 2026-05-06
6. Yellow Fellows Partnered Server Hijacking case (public Discord support forum) — https://support.discord.com/hc/en-us/community/posts/4413209659031 — verified 2026-05-06
7. October 2025 Discord third-party (Zendesk) breach — Malwarebytes Labs report — https://www.malwarebytes.com/blog/news/2025/10/discord-warns-users-after-data-stolen-in-third-party-breach — verified 2026-05-06
8. New Jersey AG vs. Discord remand — Multiple news sources from April 2026
