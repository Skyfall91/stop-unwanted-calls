# Source remedies and templates

These are starting points, not a substitute for current official guidance. Identify the jurisdiction and whether the number is a consumer, business or shared-household line. The examples intentionally contain placeholders, not real case data.

## Germany: choose the supported route

- **Advertising objection:** communicate that advertising calls to the affected number are unwanted. Where the user's own personal data are processed, Article 21(2)–(3) GDPR addresses direct marketing; Article 15 can support a scoped data-source/recipient inquiry. Withdraw any applicable advertising consent prospectively without asserting that consent never existed. Preserve wanted contractual or service communications. Use a minimal internal exclusion marker rather than demanding a deletion that could cause the number to be reimported.
- **Unanswered/repeated attempts:** use the Bundesnetzagentur route for belästigende Anrufversuche where the facts support it. Its assessment is case-specific; missed calls alone do not automatically establish a violation. Do not invent ringing duration, silence after answering, or conversation content.
- **Actually received advertising:** use the telephone-advertising route and record what was offered, who called and the user's actual consent history. Do not submit third-party reviews as the user's experience.
- **Suspected number manipulation:** include observed display/connection pairs as evidence; describe manipulation as a suspicion unless established. Different numbers alone are not proof. Anonymous calls cannot simply be assigned to another campaign.
- **Fraud:** preserve evidence and use the appropriate police, financial institution or infrastructure-abuse channel for the specific facts. Check the competent route; not every scam falls within the telecommunications regulator's remit.

Official starting points:

- [Bundesnetzagentur complaint categories](https://www.bundesnetzagentur.de/DE/Vportal/TK/Aerger/Beschwerde/start.html)
- [Belästigende Anrufversuche](https://www.bundesnetzagentur.de/DE/Vportal/TK/Aerger/Faelle/PredictiveDialer/start.html)
- [Unerlaubte Telefonwerbung](https://www.bundesnetzagentur.de/DE/Vportal/TK/Aerger/Faelle/UEW/start.html)
- [Rufnummernmanipulation](https://www.bundesnetzagentur.de/DE/Vportal/TK/Aerger/Faelle/Manipulation/start.html)
- [Official German geographic number block register](https://www.bundesnetzagentur.de/DE/Fachthemen/Telekommunikation/Nummerierung/ONRufnr/Verzeichnisse/start.html)
- [Bundesnetzagentur: information rights for telephone numbers](https://www.bundesnetzagentur.de/DE/Vportal/TK/Aerger/Auskunft/artikel.html)
- [Berlin data-protection authority: advertising objections](https://www.datenschutz-berlin.de/buergerinnen-und-buerger/selbstdatenschutz/ueberpruefung-ihrer-daten/werbung/)
- [GDPR official text](https://eur-lex.europa.eu/eli/reg/2016/679/oj)

## Germany and EU: legal and privacy checks

Check current official sources and the specific facts before invoking a rule. The relevant law, authority, category of caller and available evidence differ by jurisdiction and by consumer or business context. Distinguish a factual report from a formal claim and explain material uncertainty.

- **Carrier information:** For German geographic and mobile numbers the Bundesnetzagentur describes a right to identify the original block holder, but no corresponding TKG entitlement against that carrier to reveal the individual assignee. A block assignment or confirmation of current network service does not establish the caller or customer. Ask the verified carrier whether it can investigate internally or accept a report without disclosing another customer's information. The rules for special number ranges can differ; check the official guidance above.
- **Calls and evidence:** For the Bundesnetzagentur's consumer telephone-advertising procedure, a completed advertising conversation and the other stated conditions matter. A missed call alone does not establish an unlawful advertising call. Use the authority's separate guidance on nuisance call attempts when applicable and report only what actually happened. Do not assume the same conditions apply to all business calls or all enforcement routes.
- **Personal data:** Where the request concerns an identifiable natural person's personal data, check whether access under GDPR Article 15, rectification under Article 16, erasure under Article 17 or objection to direct marketing under Article 21 applies. Article 19 concerns notification of recipients subject to its conditions and exceptions. Ask about actual recipients and data origin where relevant. Erasure has exceptions and does not automatically reach every third party. A minimal suppression record may be needed to honor an advertising objection. Confirm the user's authority before asserting another person's rights or acting as their representative; a factual notice of an obsolete listing need not claim such authority.
- **Identity and timing:** Check whether identification or proof of authority is genuinely needed and request only proportionate information. Under GDPR Article 12, a response is generally due within one month, with possible extension under the stated conditions. Verify the correct start date, applicable exceptions and any notice before alleging a missed deadline. Refer unresolved data-protection issues to the competent supervisory authority where appropriate.
- **Public artifacts:** Check both content and Git author/committer metadata before publishing. A later correction to `main` does not itself remove earlier commits, pull-request references, cached views, forks or copies. Identify affected references and use the host's current documented procedure; obtain any required authorization before rewriting published history or force-pushing.

## Ask a carrier to check a number

When the call log lists both a displayed number and a network-provided number, check the device documentation for what the two fields represent. Look up the network-provided number in the official block register if one exists. Use the original block holder as a routing lead. Porting can change the current carrier, and an allocation says nothing about who placed or commissioned a call.

For a first inquiry, use the original block holder's official contact. Omit the household number and full call log. Check what the sender address and display name expose before sending. Check that any permission to use a personal sender address covers the original block holder in that role. If it does, ask the recipient to keep the address from the suspected caller and its client.

> Guten Tag, bei wiederholten unerwünschten Anrufversuchen wurde [ANGEZEIGTE_RUFNUMMER] angezeigt und zusätzlich [NETZSEITIGE_RUFNUMMER] übermittelt. Laut [AMTLICHES_VERZEICHNIS] wurde der zugehörige Block ursprünglich Ihnen zugeteilt. Können Sie prüfen, ob diese Anschlussnummer aktuell über Ihr Netz bereitgestellt wird? An welche Stelle kann ich die Anrufversuche zur Prüfung melden? Bitte antworten Sie schriftlich und geben Sie meine Absenderadresse nicht an den Anrufer oder dessen Auftraggeber weiter. Ein Rückruf ist nicht erwünscht.

## Message to a verified provider

The text can be used in an authorized form, postal letter or email. First check what the selected channel exposes. If the user prohibits personal email disclosure, do not use their mail account or a form requiring that email. For a postal letter, replace the email reply instruction with the separately agreed response channel; do not invent a return address. A number-only removal interface may offer no written response: record the actual visible outcome instead.

To: <OFFICIALLY_VERIFIED_CONTACT>

Subject: Keine Werbeanrufe an <AFFECTED_NUMBER> – Widerspruch und Datenherkunft

Guten Tag,

an die Rufnummer <AFFECTED_NUMBER> sind keine weiteren Werbeanrufe erwünscht. Bitte nehmen Sie die Nummer aus Ihren Anrufkampagnen und veranlassen Sie dies auch bei den in Ihrem Auftrag tätigen Dienstleistern. Eine etwaige Einwilligung in telefonische Werbung wird vorsorglich für die Zukunft widerrufen. Bitte bestätigen Sie die Umsetzung schriftlich; bitte keine telefonische Rückfrage.

Dokumentiert sind folgende Anrufversuche: <RELEVANT_DATES_AND_NUMBER_PAIRS>.

Bitte teilen Sie mit, aus welcher konkreten Quelle die Nummer stammt, zu welchen Werbezwecken Sie diese verwenden und welche Dienstleister oder Empfänger für die Anrufkampagnen eingebunden wurden. Eine minimale interne Kennzeichnung, die weitere Werbeanrufe und einen erneuten Import verhindert, soll erhalten bleiben.

Mit freundlichen Grüßen

Include a name only when needed or requested. Add a personal GDPR access request only to the extent the user is entitled and wants it; do not assert household-wide representation.

## Attribution not yet confirmed

Use this opening before the objection, adapting to the evidence:

> Zu den unten aufgeführten Rufnummern gibt es öffentliche Hinweise auf Ihr Unternehmen. Die Zuordnung ist nicht gesichert. Bitte bestätigen Sie zunächst, ob die Anrufe von Ihnen oder einem Ihrer beauftragten Dienstleister stammen. Falls dies zutrifft, gilt der folgende Werbewiderspruch. Andernfalls bitte ich um kurze schriftliche Mitteilung; ich behaupte keine feststehende Verantwortlichkeit Ihres Unternehmens.

Before sending, explain that the recipient is a hypothesis, and enumerate the private data it would receive. Do not send the complete household log to establish attribution.

## Alternatives without disclosing a personal email address

Check the independently verified organization's own privacy/contact information for an existing number-only objection/removal mechanism. Inspect mandatory fields before entering any data. Avoid marketing callback and lead-generation forms; they can create a fresh contact request rather than remove one.

An authenticated telephone-provider support portal can be a route to request an investigation or submit evidence without sharing an email address with the suspected marketer. Check who will receive the data and what the provider can actually do; it is not automatic source shutdown.

Prepare a postal objection with the already-called number and relevant evidence, omitting resident names and email when the chosen procedure allows this. Verify the postal recipient. Do not buy postage or send a letter without the required authorization.

For authority reports, inspect the current form's mandatory identity/contact requirements and confidentiality information. Never assume the complainant's details remain hidden from the respondent. If a personal email, name, signature or subscriber authority is mandatory, explain the specific requirement and obtain the user's decision instead of entering false information or silently relaxing their privacy preference.

## Factual report to a provider or authority

Record the affected number, connection provider if verified, timezone, relevant dates/times, displayed/connection numbers, call direction, actual observed conduct, and the user's statement that the calls are unwanted. Keep any public reputation evidence in a separate section labelled third-party reports. State operator identity as unknown when unknown. Include previous objections and replies only if they actually occurred.

An authority may require a complainant's identity or subscriber authority. Prepare the report without unnecessary resident names; ask for the actual mandatory information before submission. Never manufacture an identity or evade required fields.
