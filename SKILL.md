---
name: stop-unwanted-calls
description: Use when a user wants unwanted advertising or scam calls investigated and stopped at their source, especially when local blocking is unwanted, private contact details must not spread, or a shared household must remain reachable.
---

# Stop Unwanted Calls

Identify the responsible caller and data source, then pursue a verified opt-out, direct-marketing objection or factual provider/regulator report. Keep legitimate callers reachable. Treat “eliminate the source” as ending unwanted calling through legitimate channels.

This is an assistant-independent Agent Skill. Use the tools actually available in the current environment; no particular model, vendor, operating system or router is required. With no access to call records or external actions, work from user-provided evidence and produce usable messages or instructions, clearly identifying steps the user must perform. Never imply background monitoring or call-control capabilities that are unavailable.

## Operating rules

- Do not block numbers, anonymous calls, prefixes, or unknown callers; do not create allowlists, filters or routing changes unless separately requested. Declining an active scam call does not authorize a persistent block.
- Ask about each legitimate or uncertain provider individually: “Brauchst du Anrufe von [Anbieter] noch, oder sollen dessen Werbeanrufe aufhören?” Keep a confirmed decision; do not ask it again. Preserve service calls separately from advertising when the user needs them. Known friends, household contacts and local services remain outside the campaign unless specifically selected.
- A clear scam can be rejected immediately within available capabilities and the user's authorization. End an active interaction without sharing codes, paying or installing software. A negative community review, missed call, unfamiliar number or genuine company's marketing is not by itself a clear scam. If no call-control capability exists, tell the user to hang up; never pretend to have rejected it.
- Shared household: use the affected telephone number, not an inferred resident's name. Do not take the mail-account owner's name as proof of the user's identity or claim to represent all residents. Ask for identity or subscriber authority only if the actual procedure needs it, explaining why. Avoid inventing personal GDPR claims about other residents.
- Source investigation and “this provider is unwanted” do not by themselves authorize disclosure to a newly discovered recipient. Prepare the exact message first; apply the host's external-action and sensitive-data rules. Preserve existing specific authorization and ask only for genuinely missing permission or information.
- Protect the user's personal email address and names in message text, sender display, From/Reply-To headers, form fields and attachments. When the user says not to disclose their email, do not send from their account, enter it in a contact form, or propose a new alias/account without approval. Prefer verified removal mechanisms needing only the already-called number, an existing authenticated provider channel, a postal draft without unnecessary resident details, or a factual report to the competent authority. These routes still need the applicable authorization for the actual recipient and disclosed data. If a route requires forbidden or mandatory identity data, find a different route or report that exact blocker; never fabricate fields or promise anonymity.

## Collect and attribute

Use available telephone-provider tools, device call history, a router interface or a user-supplied export. With permission to inspect a device, prefer a sufficient connected tool before browser/computer interaction. Let the user handle unavailable login credentials. Do not reset devices, change credentials or alter unrelated network/security settings.

Read call direction, date/time and timezone, displayed caller number, any separately reported connection number (sometimes labelled “Anschluss”), called household number and available messages. Preserve the original log. Confirm the local area code from actual account/device settings or the user before expanding a shortened household number.

Group exact duplicates and recurring number pairs. Count log entries as entries, not necessarily distinct people or conversations. Mark observations, third-party reports and inferences separately.

Research the selected number and observed connection numbers in focused searches. Prefer current official organization details and first-hand evidence; community reports are leads. A shared connection number is a useful correlation, not proof of a single company. Displayed numbers can be spoofed; different display and connection numbers can also be legitimate. Number-block allocation does not prove the present carrier or caller. Verify legal entity, domain and contact independently; similar names are not interchangeable.

After a focused search and the strongest lead fail to identify the operator, record the precise uncertainty and move to a concrete evidence-backed next step. Do not loop through speculative firms or substitute an IP address, registrar or unrelated namesake for the actual caller.

## Act on the source

| Evidence and user decision | Next step |
|---|---|
| Confirmed unwanted provider, verified official contact | Prepare a scoped advertising objection and data-source inquiry. |
| Plausible provider, attribution unconfirmed | Prepare a conditional attribution inquiry; disclose the household number only with the required specific authorization. |
| Operator unknown, clear abuse evidence | Prepare a factual report to the verified responsible provider or competent authority. |
| Legitimate/uncertain provider not yet assessed by user | Ask about that provider; continue independent research meanwhile. |
| Known wanted contact | Leave it alone. |

Read [source-remedies.md](references/source-remedies.md) for Germany-specific routes and message templates. Check current official rules before legal/procedural claims. Do not claim an unanswered call contained advertising, that consent never existed, or that spoofing occurred without evidence.

For approved outreach, send only relevant dates/number pairs and the affected number. Request cessation across the verified sender's campaigns and contractors, written confirmation, and the origin of the telephone data. Request a minimal sender-side do-not-contact marker to prevent reimport; distinguish this from router blocking. Do not request destruction of records needed to honor the objection or document abuse.

Rejecting a scam is not replying to its attacker. Use verified abuse/reporting channels; do not call back suspicious numbers or follow their purported removal links. Do not probe, disrupt or compromise third-party infrastructure.

## Verify and continue

Track each provider: evidence, attribution confidence, user's decision, approved recipient/disclosure, action, timestamp and response. Distinguish **prepared**, **sent**, **receipt acknowledged**, **cessation confirmed** and **observed no recurrence**. A sent request is not proof the source stopped. If denied, preserve the denial and pursue the remaining verified leads; if refused or ignored, prepare proportionate escalation with the evidence available. Observe response periods before alleging a missed deadline. Create scheduled monitoring only when requested.

Report the actual result and next concrete dependency. Never promise all future spam is eliminated. Keep private case records outside the reusable skill, repository and public examples.
