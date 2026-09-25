# Privacy Policy for Defendr

Version 2026-09-27 · effective 2026-09-27

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
stored. One exception applies when a server explicitly turns it on (off by default): for
messages Defendr acts on, a shortened, defanged excerpt is stored (encrypted, deleted after at
most 1095 days, earlier together with the moderation case). A second exception: what
you write to Defendr in a direct message (text, file names and links) is kept in a private channel of the Defendr
support server (#ops-chat) so the Defendr team can read and answer it, until 1825 days after the last message of the
conversation or until you ask for erasure (see 3.11).

3.2 Moderation cases and detections: Discord user ID, reason code, action, time, server ID.

3.3 Joins: user ID, account creation date, avatar present yes/no, time-limited flags (for example "verification
pending") – for raid detection, join rules and verification.

3.4 Safety Records in the Defendr network: user ID, reason code, evidence, review status, expiry date. Unreviewed
records are only shown to moderators as a hint and never trigger an automated action. The Defendr team can look up one
person's network records and the number of moderation cases per server only with a stated reason; every such lookup is
logged, and while a processing restriction applies the team sees only each record's ID, source and status. The operator
of Defendr can also make a network record active personally, without a second review and also without evidence, based on
the operator's own decision or on reports from the ScammerAlert community list. Such a record is marked as an owner
decision wherever it is shown; Defendr stores when and by whom it was decided and how many evidence items the record
held at that moment. It stays a hint for moderators and never triggers an automated action. A record decided this way
without evidence that rests on the ScammerAlert list is removed automatically when ScammerAlert removes the entry.

3.5 Reports (including as a co-reporter), appeals and requests about your rights: the text you write yourself. Files
you attach to them are not stored: an image you report is hashed once while the report is taken and the hash is kept
instead of the picture, and of every other attachment only the fact that you offered it is noted (how many, and what
type Discord declared) so that the person handling your case can ask you for it.

3.6 Server settings: role and channel IDs, IDs of the admins and moderators who change settings or take decisions.
If an admin answers the optional question "Where did you find Defendr?" in `/setup`, one of six fixed answers (for
example "top.gg" or "A friend") is stored for the server and not assigned to any person. It is used only to understand
how servers find Defendr, is shown to the Defendr team only as a count across all servers, and is deleted together
with the server's configuration.

3.7 No IP addresses, no device data, no profiling, no training of AI models.

3.8 The complete list of data categories with their retention is in section 7. It is generated from the same registry
the deletion jobs read their deadlines from.

3.9 Oversight of the bot itself: the Defendr team keeps a private channel on the Defendr server with one entry per
action Defendr took on any server and per moderation, report and appeal event handled through Defendr — user, server and
channel IDs, including the ID of the moderator or team member who acted, the names Discord showed for them at that
moment (the server's name, the channel's name, the display or user name of the member and of the moderator or team
member), the type of action or event, counts and times, and for a link or invite Defendr detected the listed threat
value it matched (from a threat list, never what the member wrote); never the content of a message, a note, a report or an
appeal, never who reported whom. It exists so the team can see what the bot does across all servers and notice a
mistake (legitimate interest, section 4). It is kept until the team deletes it.

3.10 Support tickets in the support server: user ID, topic, subject, description and form fields (encrypted), the
private thread, who closed or reopened the ticket, ticket bans. What exactly, why and for how long is in section 11.

3.11 Direct messages to Defendr: if you send Defendr a direct message, the Defendr team sees it (text, file names and
links, time) in a private channel of the support server so that it can answer you; answers reach you as direct messages
from Defendr. Defendr itself stores only that a conversation exists (your user ID, the post in that channel, the time of
the last message and whether the team muted it), never the text of your messages or of the answers. The conversation
(the post and this record) is deleted 1825 days after the last message; /defendr mydata delete deletes it within an
hour, and /defendr mydata export shows it. Legal basis: Art. 6(1)(f) GDPR (answering people who contact us).

## 4. Purposes and legal bases

<!-- anchor: purposes -->

- Protecting Discord communities against fraud, malware and abuse: Art. 6(1)(f) GDPR.
- Handling appeals and data subject requests: Art. 6(1)(c) and (f) GDPR.
- Network-wide Safety Records: Art. 6(1)(f) GDPR; the legitimate interest assessment is available on request.
- Understanding how servers find Defendr (the optional setup answer "Where did you find Defendr?", stored per server
  and not assigned to any person): Art. 6(1)(f) GDPR; the answer is voluntary and can be left out.
- Oversight of Defendr's own actions and of the moderation, report and appeal events handled through it
  (section 3.9): Art. 6(1)(f) GDPR.
- Handling support tickets in the support server (section 11): Art. 6(1)(b) GDPR where you use Defendr under the
  terms of service, otherwise Art. 6(1)(f) GDPR.
  <!-- OD-17: lawyer review — legal basis of support tickets (Art. 6(1)(b) towards users, (f) otherwise) -->
- Answering direct messages to Defendr (section 3.11): Art. 6(1)(f) GDPR.

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
| Uploaded evidence (staff uploads on Safety Records and cases) | 1095 days; record evidence with the record; legal hold suspends deletion; nothing a member attaches is stored | purge + file unlink (crypto-shredding) |
| Reports and co-reporter links | accepted: 1825 days after decision; rejected/spam: 365 days; pending: auto-closed after 90 days | purge |
| Reporter reputation | 1825 days after last report | purge |
| False-positive signals (moderator id, case) | 1095 days | purge |
| Review votes and staff threads | with the reviewed item | purge (+ thread deletion) |
| Appeals (incl. recommendations) | 1825 days after decision or lapse | purge |
| Support tickets (form text sealed; the private thread in the support server) and ticket bans | 1825 days after closing (row and thread); a ticket thread left without its record (after a failed creation or a restore from a backup) is deleted 1825 days after it was created (possibly locked and archived before then) — because no record links it to a member, the team deletes it by hand on an erasure request; ticket bans until lifted | `support.tickets` (thread first, then the row; a thread without a record by the list of the job, `kv.support.orphans`); a ban is deleted when lifted |
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
| Global mirror (#global-logs, staff channel): ids, action and event types, counts and times of Defendr's actions and of the moderation, report and appeal events handled through it (moderator and staff ids included), the names Discord showed for the server, the channel, the member and the moderator or staff member at that moment, and the listed threat value a link or invite Defendr detected matched; never message content | kept until the operator deletes it (owner-set retention, decision of 2026-09) | operator (Discord channel) |
| Error events (redacted) | 365 days | purge |
| Statistics aggregates (no user IDs): counts per day, server and metric, incl. per reason code and per detection family | indefinite | — |
| Setup answer "Where did you find Defendr?" (per server, optional; not assigned to a person) | with the server's configuration: 90 days after Defendr leaves (or immediately if configured) | `guilds.purge` |
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

Support tickets (section 11) are part of the export and are deleted with an erasure; a ticket ban is kept
(section 11.6).

## 9. Automated decisions

Server operators decide how Defendr reacts to a detected threat. Defendr limits actions by
how reliable the evidence is (for example, never a ban on an external list alone). Network
records never take effect without human review. Every decision can be reviewed with /appeal: a server's moderators
decide about its own cases, the Defendr team about network-wide records.

Defendr only sends a direct message when an action concerns you, when you started a flow yourself
(appeal, report, data subject request), when you wrote to Defendr and the Defendr team answers you, or – if you own a
server – once per incident when Defendr cannot show an anti-nuke alarm in your server (who did what and when, and a
button to restore deleted channels and roles) – never as advertising or a welcome.

When a network record about you becomes active, Defendr sends you one direct message, but only if you share a server
with Defendr, in that server's Defendr language. It states the reason, what the record means and how to appeal. If such
a record is later removed because ScammerAlert withdrew it, you get one short message about the removal. Defendr stores
only whether and when these messages were sent, refused or could not be delivered. A record that rests only on the
ScammerAlert list is appealed at ScammerAlert; your data subject rights against Defendr (/defendr mydata) remain.

## 10. Security

Encryption of stored sensitive data, restricted access, logging of staff access, regular backups.

## 11. Support tickets in the support server

<!-- anchor: support -->

11.1 Who and what. When you open a ticket in the `#contact-staff` channel of the Defendr & Checkout support server, we
process: your Discord user ID, the topic you picked, the subject, the description and the other fields of the form
(stored encrypted), the server the summary in section 11.2 is about, the times of opening and of the last
activity, the private thread with its messages (it stays on Discord; it can be seen by you, Defendr's support staff,
the server's team role and whoever may manage threads in that channel), who closed or reopened the ticket, and ticket
bans (who set one and when). Purpose: answering your request and troubleshooting. Legal basis: Art. 6(1)(b) GDPR where
you use Defendr under the terms of service, otherwise Art. 6(1)(f) GDPR.

11.2 What the thread shows the team automatically. When the ticket opens, Defendr posts into the thread only what you
could already see about yourself: your own moderation cases, network listings, appeals and data requests, a
processing restriction that applies to you, and the result of checking a link you put into the form. For topics about
a server it shows the setup summary of a server you administer: the one you pick, or the only one Defendr can confirm.
It never shows other people's data. Anything beyond that is a lookup by the team as described in section 3.4.

11.3 Checkout topics. Defendr and Checkout are two separate bots with separate data; both are operated by the
controller named in section 1 on the same machine. For the two Checkout topics (setup, bug) Defendr reads from the
Checkout bot's files the Checkout configuration of the server you pick, your own time-tracking figures in that server
and that server's totals (number of tracked people and sessions, no figures of other individuals) – read only. The
result appears only in the private thread; Defendr stores none of it.

11.4 No transcript. Defendr keeps no copy of the thread and, for the ticket, uses only the time of the newest message
in order to close a ticket automatically after seven days without activity (tickets of the data-access-or-deletion
topic are exempt; a person closes them once the request has been answered). As on every server Defendr protects,
messages in the thread are checked in memory for a moment and not stored (section 3.1). The team can reopen a ticket
as long as the thread exists.

11.5 Retention. The ticket and the thread are deleted five years after the ticket was closed (table in section 7). An
open ticket has no expiry date. A ticket ban lasts until the team lifts it. A ticket thread left without its record
(after a failed creation or a restore from a backup) is deleted five years after it was created; until then Defendr
may lock and archive it if nobody wrote in it. Because no record links it to a member, the team deletes it by hand on
an erasure request.

11.6 Your rights. Your tickets are part of your export (/defendr mydata export), including the subject, the
description and the form fields; the messages in the thread exist only on Discord and stay visible to you as long as
the thread exists. A ticket ban appears in the export without the person who set it. An erasure (/defendr mydata
delete) deletes your tickets and their threads – an open ticket is ended by it too; a ticket ban is kept (protection
of others). The fastest way to make a request about your data is /defendr mydata: it records the request and its
deadline. A request you make in a ticket of the data-access-or-deletion topic is handled just the same; the one-month
deadline (Art. 12(3) GDPR) runs from the opening of the ticket.

<!-- OD-17: lawyer review — 11.3: change of purpose (Art. 6(4)) for the read-only access to Checkout data, a sentence in Checkout's privacy notice, stale Checkout owner; 11.6: a ticket of the data-access-or-deletion topic is a received data-subject request, the deadline runs from the opening of the ticket; ticket bans survive an erasure -->

## 12. Changes

Versions: https://github.com/FunnyBuddys/defendr-legal/tags. The current English text is at https://github.com/FunnyBuddys/defendr-legal/blob/main/privacy.en.md.
