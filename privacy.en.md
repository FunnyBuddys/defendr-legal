> ENTWURF – anwaltliche Prüfung erforderlich / DRAFT – requires legal review

# Privacy Policy for Defendr

Version 2026-09-19 · effective 2026-09-19

The German version is legally binding. This English translation is provided for convenience: https://github.com/FunnyBuddys/defendr-legal/blob/main/privacy.de.md

## 1. Controller

<!-- anchor: contact -->

Samuel Sakli, Wegsfeld 42, 30455 Hannover, Deutschland, e-mail: support@seismicdrop.com. Contact inside Discord: /defendr support.

## 2. What is Defendr?

<!-- anchor: summary -->

Defendr is a security bot for Discord servers. It detects phishing links, malware links, scam images, QR codes that
take over Discord accounts, spam, raids and hijacked accounts. Defendr runs entirely inside Discord. There is no
website, no web dashboard and no login outside Discord.

## 3. What we process

<!-- anchor: data -->

3.1 Message content (text, embeds, attachments, forwarded messages, polls) is checked in memory for a moment and not
stored. The only exception applies when a server explicitly turns it on (off by default): for
messages Defendr acts on, a shortened, defanged excerpt is stored (encrypted, deleted after at most

1095 days, earlier together with the moderation case).

3.2 Moderation cases and detections: Discord user ID, reason code, action, time, server ID.

3.3 Joins: user ID, account creation date, avatar present yes/no, time-limited flags (for example "verification
pending") – for raid detection, join rules and verification.

3.4 Safety Records in the Defendr network: user ID, reason code, evidence, review status, expiry date. Unreviewed
records are only shown to moderators as a hint and never trigger an automated action.

3.5 Reports (including as a co-reporter), appeals and requests about your rights: the content and files you submit
yourself.

3.6 Server settings: role and channel IDs, IDs of the admins and moderators who change settings or take decisions.

3.7 No IP addresses, no device data, no profiling, no training of AI models.

3.8 The complete list of data categories with their retention is in section 7. It is generated from the same registry
the deletion jobs read their deadlines from.

## 4. Purposes and legal bases

<!-- anchor: purposes -->

- Protecting Discord communities against fraud, malware and abuse: Art. 6(1)(f) GDPR.
- Handling appeals and data subject requests: Art. 6(1)(c) and (f) GDPR.
- Network-wide Safety Records: Art. 6(1)(f) GDPR; the legitimate interest assessment is available on request.

[Lawyer review: Art. 10 GDPR, Art. 22 GDPR, joint controllership with server operators (Art. 26)]

## 5. Recipients

<!-- anchor: processors -->

Discord Inc. (platform), the moderators of the server concerned (their own server data only), Offsite-Backup-Anbieter (noch nicht festgelegt, OD-12) (EU, encrypted offsite backups; only if enabled (OD-12)); Google Ireland Ltd. (Web Risk) (EU/US, URL lookups against the Google Web Risk list; only if enabled (OD-6)).

The operator aggregates detection data from every server Defendr runs on into one
team-internal channel on the support server. That channel holds **no message
content** – only the server, the channel, the user id concerned, the action taken,
the detected indicator (rendered defanged), technical checksums and the time. Its
purpose is operating the service and countering abuse across servers; access is
limited to the operator and the support team.

## 6. Transfers to third countries

Discord (USA) – using Discord is subject to Discord's own privacy policy. Discord Inc. also processes data in the United States. There are no other transfers to third countries; a processor located in EU/US is used only once the owner decision named next to it enables it.

## 7. Retention

<!-- anchor: retention -->

| Data class | Retention | Deletion mechanism |
| --- | --- | --- |
| Message content during scanning | Seconds (memory only) | not stored |
| Detection records (ids, type, action; no message content) | 1825 days | `retention.purge` |
| Moderation cases (+ events) | 1825 days (owner-set, identical in every server) | `retention.purge` |
| Message excerpts (opt-in per server) | at most 1095 days, never longer than the case | purge (sealed; crypto-shredding) |
| Uploaded evidence (reports, appeals, rectification requests) | 1095 days; report evidence 1095 days after decision; record evidence with the record; legal hold suspends deletion | purge + file unlink (crypto-shredding) |
| Reports and co-reporter links | accepted: 1825 days after decision; rejected/spam: 365 days; pending: auto-closed after 90 days | purge |
| Reporter reputation | 1825 days after last report | purge |
| False-positive signals (moderator id, case) | 1095 days | purge |
| Review votes and staff threads | with the reviewed item | purge (+ thread deletion) |
| Appeals (incl. recommendations) | 1825 days after decision or lapse | purge |
| Data subject requests; processing restrictions | 1825 days (accountability; content minimized and sealed); restrictions 1825 days after lifting | purge |
| Active network listing | no automatic expiry; re-review reminder after 12 months (a status change always needs a staff decision) | re-review reminder + purge 1095 days after close |
| Quarantined imported listings (811 + 4) | until reviewed; reminder after 6 months (OD-7) | review decision |
| Closed Safety Records (revoked/rejected/expired) | 1095 days | purge |
| Member flags: hijacked account / raid cohort / network hint shown | 72 hours / 7 days / 30 days | `member-flags.expire` |
| Member flag: pending verification | at least 24 hours, as long as the server's kick-unverified delay + 1 hour | `member-flags.expire` |
| Member flags: join-gate quarantine role / suspect role applied by Defendr | while the role is held; 30 days after leaving | reconcile jobs + `member-flags.expire` |
| Raid cohorts (metadata only) | 365 days | purge |
| Incidents | 1825 days | purge |
| Anti-nuke role strips / structure snapshots / deleted entities (2.1) | 30 / 7 / 14 days | purge |
| Lockdown records | 1095 days after end | purge |
| Verification challenges | 24 hours | purge |
| Interactive UI state (sealed) | ≤ 24 hours | `ui_state.purge` |
| Pending messages (outbox) | content wiped when sent or given up; rows 7 days (sent) / 30 days (failed) | purge |
| Config revisions; preset and migration card decisions | last 100, max 1 year; decisions 90 days | purge |
| Staff audit log (`ops_audit`, incl. evidence views) | 1825 days | purge |
| Staff membership | 1825 days after deactivation | purge |
| Anonymous network signals (2.1) | 48 hours | purge |
| Premium entitlements (2.2) | 30 days after end | purge |
| Application logs (no content) | 90 days | rotation |
| Error events (redacted) | 365 days | purge |
| Statistics aggregates (no user IDs): counts per day, server and metric, incl. per reason code and per detection family | indefinite | — |
| All guild data after Defendr leaves | 90 days (or immediately if configured); cancelled by re-invite | `guilds.purge` |
| Local backups | 14 daily / 8 weekly / 6 monthly | prune |
| Offsite backups (encrypted) | 14 daily / 8 weekly / 12 monthly | restic forget/prune |
| v1 history dossiers | not migrated; destroyed at v1 decommission (T+30 d, encrypted archive destroyed after 90 d) | owner runbook |

Deletion inside backups happens through their rotation; the maximum backup retention is in the table.

## 8. Your rights

<!-- anchor: rights -->

Access (/defendr mydata export), erasure (/defendr mydata delete), objection (/defendr mydata object), rectification
(/defendr mydata rectify), restriction (/defendr mydata restrict), review of a decision (/appeal), and a complaint to a
supervisory authority (Der Landesbeauftragte für den Datenschutz Niedersachsen, Prinzenstraße 5, 30159 Hannover, Deutschland).

## 9. Automated decisions

Server operators decide how Defendr reacts to a detected threat. Defendr limits actions by
how reliable the evidence is (for example, never a ban on an external list alone). Network
records never take effect without human review. Every decision can be reviewed with /appeal: a server's moderators
decide about its own cases, the Defendr team about network-wide records.

Defendr only sends a direct message when an action concerns you or when you started a flow
yourself (appeal, report, data subject request) – never as advertising or a welcome.

## 10. Security

Encryption of stored sensitive data, restricted access, logging of staff access, regular backups.

## 11. Changes

Versions: https://github.com/FunnyBuddys/defendr-legal/tags. The current English text is at https://github.com/FunnyBuddys/defendr-legal/blob/main/privacy.en.md.
