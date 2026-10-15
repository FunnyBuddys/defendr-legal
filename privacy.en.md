# Privacy Policy for Defendr

Version 2026-10-19 · effective 2026-10-19

The German version is legally binding. This English translation is provided for convenience: https://defendr.live/de/privacy

## 1. Controller

<!-- anchor: contact -->

Samuel Sakli, c/o Autorenglück #66851, Albert-Einstein-Straße 47, 02977 Hoyerswerda, Deutschland, e-mail: contact@defendr.live. For privacy questions and requests about your
rights: privacy@defendr.live. Contact inside Discord: /defendr › Support. We have not appointed a data protection
officer.

## 2. What is Defendr?

<!-- anchor: summary -->

Defendr is a security bot for Discord servers. It detects phishing links, malware links, scam images, QR codes that
take over Discord accounts, spam, raids and hijacked accounts.

Defendr also has the website defendr.live: public information pages, a personal area ("My Defendr") and server
administration at app.defendr.live, which you sign in to with your Discord account, and a status page at
status.defendr.live. The website is a second way to the same features: you see and may do there only what Defendr
also shows you and allows you in Discord. There is no separate Defendr account, no password and no sign-up with an
e-mail address. What the website processes is in sections 12 and 13.

## 3. What we process

<!-- anchor: data -->

3.1 Message content (text, embeds, attachments, forwarded messages, polls) is checked in memory for a moment and not
stored. One exception applies when a server explicitly turns it on (off by default): for
messages Defendr acts on, a shortened, defanged excerpt is stored (encrypted, deleted after at
most 1095 days, earlier together with the moderation case). A second exception: what
you write to Defendr in a direct message (text, file names and links) is kept in a private channel of the Defendr
support server so the Defendr team can read and answer it, until
1825 days after the last message of the conversation or until you ask for
erasure (see 3.11). A third exception applies only in Defendr's own support server: the messages in support ticket
threads (private threads between you and Defendr's support team) are stored encrypted as the ticket's transcript, so
that you and the team can also read and answer the ticket on the website (see section 11.4).

3.2 Moderation cases and detections: Discord user ID, reason code, action, time, server ID.

3.3 Joins: user ID, account creation date, avatar present yes/no, time-limited flags (for example "verification
pending") – for raid detection, join rules and verification.

3.4 Safety Records in the Defendr network: user ID, reason code, evidence, review status, expiry date. Records from
external lists, and records still awaiting review, are only shown to moderators as a warning and never trigger an
automated action on their own. This includes the entries that Defendr takes over automatically from the ScammerAlert
community lists: since version 2.0.9 they become active network records automatically, unless the operator has switched
this off or a safety limit holds them back. They are marked with the list they come from ("known scam accounts", "deal
with caution" or, for older entries, "list not recorded") and as an external list. The card moderators get when such a
person joins their server also shows the reason ScammerAlert states for the entry, but only in a log channel that not
everyone on the server can see. They are withdrawn automatically as soon as ScammerAlert strikes through or deletes the
entry. If a person at Defendr closed an earlier record about you (for example after an appeal), a new ScammerAlert entry
about you does not become active by itself. A server can switch these warnings off. A moderator who sees such a warning
may decide to act on it; that is the moderator's own decision and is recorded as a case of that moderator. The Defendr
team looks up one person's network records and the number of moderation cases per server to handle reports, appeals
and requests. The operator of Defendr can also activate a network record personally, based on the operator's own
assessment or on reports from the ScammerAlert community list, also without evidence. Such a record is marked as an owner decision wherever it is shown; Defendr stores when and by whom it was decided and
how many evidence items the record held at that moment. It stays a hint for moderators and never triggers an automated
action. A record decided this way without evidence that rests on the ScammerAlert list is removed automatically when
ScammerAlert removes the entry.

3.5 Reports (including as a co-reporter), appeals and requests about your rights: the text you write yourself. Files
you attach to them are not stored: an image you report is hashed once while the report is taken and the hash is kept
instead of the picture, and of every other attachment only the fact that you offered it is noted (how many, and what
type Discord declared) so that the person handling your case can ask you for it.

3.6 Server settings: role and channel IDs, IDs of the admins and moderators who change settings or take decisions.
If an admin answers the optional question "Where did you find Defendr?" in `/setup`, one of six fixed answers (for
example "top.gg" or "A friend") is stored for the server and not assigned to any person. It is used only to understand
how servers find Defendr, is shown to the Defendr team only as a count across all servers, and is deleted together
with the server's configuration.

3.7 Defendr stores no IP addresses in its database, builds no device fingerprints and no
behavioural profiles, and trains no AI models. When you open the website your IP address is processed for the
connection: our web server keeps it in memory only for a short time, and Cloudflare, as our processor, records it in
analytics and security logs. On the pages after you sign in, Discord receives it too when your browser loads profile
pictures and server icons from Discord there. What exactly happens is described in section 12.

3.8 The complete list of data categories with their retention is in section 7. It is created automatically from the
same settings Defendr uses to delete the data.

3.9 Overview of Defendr's actions: the Defendr team keeps a private channel on the Defendr server with one entry per
action Defendr took on any server and per moderation, report and appeal event handled through Defendr — user, server and
channel IDs, including the ID of the moderator or team member who acted, the names Discord showed for them at that
moment (the server's name, the channel's name, the display or user name of the member and of the moderator or team
member), the type of action or event, counts and times, and for a link or invite Defendr detected the listed threat
value it matched (from a threat list, never what the member wrote); never the content of a message, a note, a report or
an appeal, never who reported whom. It exists so the team can see what Defendr does across all servers and fix
mistakes quickly (legitimate interest, section 4). It is kept until the team deletes it.

3.10 Support tickets in the support server: user ID, topic, subject, description and form fields (encrypted), the
private thread and the transcript of its messages (text encrypted; of attachments only the name, size, type, picture
dimensions and the spoiler mark; who wrote a message with which Discord name and profile picture, when it was written or
edited, whether in Discord or on the website, and which message it replies to), replies sent from the website, who
closed or reopened the ticket, ticket bans. What exactly, why and for how long is in section 11.

3.11 Direct messages to Defendr: if you send Defendr a direct message, the Defendr team sees it (text, file names and
links, time) in a private channel of the support server so that it can answer you; answers reach you as direct messages
from Defendr. Defendr itself stores only that a conversation exists (your user ID, the post in that channel, the time of
the last message and whether the team muted it), never the text of your messages or of the answers. The conversation
(the post and this record) is deleted 1825 days after the last message;
/defendr › My data › Delete my data deletes it within an hour, and /defendr › My data › Export shows it. Legal basis:
Art. 6(1)(f) GDPR (answering people who contact us).

3.12 Website: opening pages, logs, sign-in with Discord, profile pictures and server icons from Discord after you sign
in (on the pages of your support tickets also the profile pictures of the other people in the ticket), sessions,
sign-in history, personal settings and what you do there, such as reading and answering your support tickets. The
details are in sections 11 and 12, cookies and browser storage in section 13.

## 4. Purposes and legal bases

<!-- anchor: purposes -->

- Protecting Discord communities against fraud, malware and abuse: Art. 6(1)(f) GDPR.
- Handling appeals and data subject requests: Art. 6(1)(c) and (f) GDPR.
- Network-wide Safety Records: Art. 6(1)(f) GDPR; the legitimate interest assessment is available on request.
- Understanding how servers find Defendr (the optional setup answer "Where did you find Defendr?", stored per server
  and not assigned to any person): Art. 6(1)(f) GDPR; the answer is voluntary and can be left out.
- The overview of Defendr's actions and of the moderation, report and appeal events handled through it
  (section 3.9): Art. 6(1)(f) GDPR.
- Handling support tickets in the support server, with the stored transcript and the replies from the website
  (section 11): Art. 6(1)(b) GDPR where you use Defendr under the terms of service, otherwise, and for the messages of
  other people in the thread, Art. 6(1)(f) GDPR. Our legitimate interest is answering requests completely and
  traceably, in Discord and on the website.
- Answering direct messages to Defendr (section 3.11): Art. 6(1)(f) GDPR.
- Providing and protecting the website and the status page, logs for troubleshooting and attack defence
  (sections 12.1, 12.2 and 12.7): Art. 6(1)(f) GDPR. Our legitimate interest is a secure, available and working
  website.
- Sign-in with Discord, the personal area, server administration and your personal settings
  (sections 12.3, 12.5 and 12.6): Art. 6(1)(b) GDPR; you use these features at your request under the terms of
  service.
- Your profile picture and your servers' icons from Discord on the pages after you sign in, and on the pages of your
  support tickets the profile pictures of the other people who wrote in the ticket (section 12.9): Art. 6(1)(f) GDPR.
  Our legitimate interest is showing you your account, your servers and the people in the ticket with the pictures you
  know from Discord, so that you recognise them at a glance.
- The sign-in history of your account (section 12.4): Art. 6(1)(f) GDPR. Our legitimate interest is that you and we
  can trace the sign-ins and sign-outs of your account and recognise sign-ins by someone else.
- The log of actions on the website (section 12.6): Art. 6(1)(f) GDPR. Our legitimate interest is being able to show
  who started or changed what through the website (accountability, Art. 5(2) GDPR).
- Answering e-mail and handling reports of security vulnerabilities (section 12.8): Art. 6(1)(f) GDPR; for requests
  about your rights Art. 6(1)(c) GDPR.
- Thanking you in public with your name or pseudonym for a reported vulnerability (section 12.8): Art. 6(1)(a) GDPR
  (your consent, which you can withdraw at any time).

## 5. Recipients

<!-- anchor: processors -->

Discord Inc. (platform; on the pages of the website after you sign in also when profile pictures and server icons
load, section 12.9; for a reply from the website Discord receives the text with your name and the address of your
profile picture, section 11.5), the moderators of the server concerned (their own server data only), ZAP-Hosting GmbH, Hafenweg 8, 48155 Münster (DE, rented server in a data centre in Frankfurt am Main that runs Defendr and the website and holds the database (section 12.1)); Cloudflare, Inc. (US, delivering and protecting the website (network, encrypted tunnel to our server, attack protection, analytics and security logs), running the status page and forwarding e-mail sent to the @defendr.live addresses (section 12)); Google Ireland Limited (Gmail) (EU/US, the mailbox e-mail to our addresses arrives in; Google processes it under its own terms as a controller of its own, not as our processor (section 12.8)); Google Ireland Ltd. (Web Risk) (EU/US, URL lookups against the Google Web Risk list; only if enabled).

The recipients of the overview of Defendr's actions (section 3.9) are the operator and the Defendr support team; it
holds no message content.

As a processor (Art. 28 GDPR), Cloudflare acts only on our instructions and under the data processing agreement.

## 6. Transfers to third countries

Discord (USA) – using Discord is subject to Discord's own privacy policy. Discord Inc. also processes data in the United States. If you open the website, Cloudflare, Inc. (USA) processes the data of the request (section 12) in its worldwide network, also in the USA. If you e-mail us, your message and your e-mail address are forwarded by Cloudflare, Inc. and stored in our mailbox at Gmail; Google stores and processes them also in the USA (Google LLC). Both companies are certified under the EU-US Data Privacy Framework (adequacy decision, Art. 45 GDPR); for Cloudflare, the standard contractual clauses in the data processing agreement apply in addition (Art. 46(2)(c) GDPR). There are no other transfers to third countries; a recipient marked "only if enabled" receives data only once we switch the feature on.

## 7. Retention

<!-- anchor: retention -->

| Data class | Retention |
| --- | --- |
| Temporary personal web-export copies and one-use delivery state | At most 15 minutes of access; keys removed immediately on completion or revocation; encrypted copies removed later in bounded cleanup batches |
| Website access logs (time, path template, status, duration, random request ID; no addresses or content) | 14 days, earlier when the storage budget is full; a stopped web server's logs are deleted by a daily task, up to one day later |
| Website event log (server errors by page and error type, missing texts, failures and refusals between the website and Defendr, failed sign-ins by reason, counts of access-log records dropped, and of access-log files deleted early with the minute their records start; no person, address, URL, cookie, content or session) | 14 days, earlier beyond 4 MiB (the oldest first); a stopped web server's log is deleted by a daily task, up to one day later |
| Website tunnel log on our server (cloudflared): only errors that stop the connector itself (log level fatal) and warnings about its own connection to Cloudflare (transport log level warn); no requests, requested addresses or IP addresses of visitors | deleted by hand by the operator, not automatically after a fixed period |
| E-mails to the @defendr.live addresses (contact@, privacy@, security@, including vulnerability reports; Gmail mailbox) | deleted once no longer needed for the request, at the latest three years after the request is closed, unless a legal duty requires longer |
| Website sessions and encrypted OAuth access tokens | 7 days without activity; at most 30 days |
| Website security events (sign-in, sign-out, sign out everywhere, ending one other session, a sign-in Defendr undid after Discord had confirmed it; device category and time; no addresses) | 365 days |
| Receipts of website actions (route, state, result code, times; the request and its idempotency key only as hashes) | 365 days after the action finished |
| Website and account preferences (language, whether Defendr messages follow it, inbox read marker, whether the note on ticket replies was seen, theme, accent, density, motion) | until the account data is deleted (no time limit); removed on request |
| Security score history per server (weekly score and part scores, no user IDs) | indefinite (aggregates); with the server's data after Defendr leaves |
| Message content during scanning | Seconds (memory only) |
| Detection records (ids, type, action; no message content) | 1825 days |
| Moderation cases (+ events) | 1825 days (owner-set, identical in every server) |
| Message excerpts (opt-in per server) | at most 1095 days, never longer than the case |
| Uploaded evidence (staff uploads on Safety Records and cases) | 1095 days; record evidence with the record; legal hold suspends deletion; nothing a member attaches is stored |
| Reports and co-reporter links | accepted: 1825 days after decision; rejected/spam: 365 days; pending: auto-closed after 90 days |
| Reporter reputation | 1825 days after last report |
| False-positive signals (moderator id, case) | 1095 days |
| Review votes and staff threads | with the reviewed item |
| Appeals (incl. recommendations) | 1825 days after decision or lapse |
| Support tickets (form text and thread messages sealed; the private thread in the support server) and ticket bans | 1825 days after closing (row, thread and stored messages, also when the thread was deleted by hand before); a ticket thread left without its record (after a failed creation or a restore from a backup) is deleted 1825 days after it was created (possibly locked and archived before then) — because no record links it to a member, the team deletes it by hand on an erasure request; ticket bans until lifted |
| Direct-message conversations with Defendr (user ID, the post in the staff channel, time of the last message, muted or not; never the text) | 1825 days after the last message; within an hour of an erasure |
| Data subject requests; processing restrictions | 1825 days (accountability; content minimized and sealed); restrictions 1825 days after lifting |
| Active network listing | no automatic expiry; re-review reminder after 12 months (a status change always needs a staff decision) |
| Imported listings awaiting review | until reviewed; reminder after 6 months |
| Closed Safety Records (revoked/rejected/expired) | 1095 days |
| Member flags: hijacked account / raid cohort / network hint shown | 72 hours / 7 days / 30 days |
| Member flag: pending verification | at least 24 hours, as long as the server's kick-unverified delay + 1 hour |
| Member flags: join-gate quarantine role / suspect role applied by Defendr | while the role is held; 30 days after leaving |
| Raid cohorts (metadata only) | 365 days |
| Incidents | 1825 days |
| Anti-nuke role strips / structure snapshots / deleted entities (2.1) | 30 / 7 / 14 days |
| Lockdown records | 1095 days after end |
| Verification challenges | 24 hours |
| Interactive UI state (sealed) | ≤ 24 hours |
| Pending messages (outbox) | content wiped when sent or given up; rows 7 days (sent) / 30 days (failed) |
| Config revisions; preset and migration card decisions | last 100, max 1 year; decisions 90 days |
| Action log: team access to records and evidence, and each website action (user ID, action, server, time, outcome, receipt and request ID) | 1825 days; kept on erasure (accountability) |
| Staff membership | 1825 days after deactivation |
| Application logs (no content) | 90 days |
| Overview of Defendr's actions (section 3.9): ids, action and event types, counts and times of Defendr's actions and of the moderation, report and appeal events handled through it (moderator and team member ids included), the names Discord showed for the server, the channel, the member and the moderator or team member at that moment, and the listed threat value a link or invite Defendr detected matched; never message content | kept until the operator deletes it |
| Error events (redacted) | 365 days |
| Statistics aggregates (no user IDs): counts per day, server and metric, incl. per reason code and per detection family | indefinite |
| Setup answer "Where did you find Defendr?" (per server, optional; not assigned to a person) | with the server's configuration: 90 days after Defendr leaves (or immediately if configured) |
| All guild data after Defendr leaves | 90 days (or immediately if configured); cancelled by re-invite |
| Local backups | 14 daily / 8 weekly / 6 monthly |
| Free-text history files from Defendr 1 | not carried over; deleted 30 days after Defendr 1 is shut down, its encrypted archive after 90 days |

Deletion inside backups happens through their rotation; the maximum backup retention is in the table.

## 8. Your rights

<!-- anchor: rights -->

You have the right of access (Art. 15 GDPR), rectification (Art. 16), erasure (Art. 17), restriction of processing
(Art. 18), data portability (Art. 20) and objection (Art. 21). In Discord you use them on the My data page of /defendr
(Export, Delete my data, Object, Correct, Restrict; directly: /defendr page:mydata), on the website in the personal
area "My Defendr" with the same functions, or by e-mail to privacy@defendr.live. The export is machine-readable.
You can have a decision reviewed (/appeal, on the website under "My Defendr"). You can also lodge a complaint with a
supervisory authority (Der Landesbeauftragte für den Datenschutz Niedersachsen, Prinzenstraße 5, 30159 Hannover, Deutschland).

**Right to object (Art. 21 GDPR):** where we process your data on the basis of legitimate interests (Art. 6(1)(f)
GDPR), you can object at any time on grounds relating to your particular situation. We then no longer process the data
unless we can demonstrate compelling legitimate grounds which override your interests, rights and freedoms, or the
processing serves the establishment, exercise or defence of legal claims. You object with /defendr › My data › Object,
in the personal area of the website or by e-mail to privacy@defendr.live.

Support tickets (section 11) are part of the export together with their transcript and are deleted with an erasure;
a ticket ban is kept (section 11.7). An erasure of your data also ends all your website sessions.

## 9. Automated decisions

Server operators decide how Defendr reacts to a detected threat. Defendr limits actions by
how reliable the evidence is (for example, never a ban on an external list alone).

Network records never trigger an automated action: entries from external lists and all
other network records only show moderators a warning, and the moderators decide themselves whether to act. Every decision can be reviewed with /appeal: a server's moderators decide about its own
cases, the Defendr team about network-wide records.

Defendr only sends a direct message when an action concerns you, when you started a flow yourself
(appeal, report, data subject request), when you wrote to Defendr and the Defendr team answers you, or – if you own a
server – once per incident when Defendr cannot show an anti-nuke alarm in your server (who did what and when, and a
button to restore deleted channels and roles) – never as advertising or a welcome.

When a network record about you becomes active, Defendr sends you one direct message, but only if you share a server
with Defendr, in that server's Defendr language. It states the reason, what the record means and how to appeal. If such
a record is later removed because ScammerAlert withdrew or deleted the entry, you get one short message about the
removal; no such message is sent when Defendr stops taking over a list as a whole. Defendr stores only whether and when
these messages were sent, refused or could not be delivered. A record that rests only on the ScammerAlert list is
appealed at ScammerAlert; while it is active you can also appeal it to the Defendr team with /appeal, and a person
at Defendr decides. Your data subject rights against Defendr (/defendr › My data) remain.

The website makes no decisions of its own: Defendr checks every action there by the same rules as in Discord.

## 10. Security

Encryption of stored sensitive data, access control and access logging, regular backups. For the website in addition:
encrypted connections only (HTTPS); session cookies bound to exactly one address, not readable by scripts and sent only
over HTTPS; the server stores only a hash of the session identifier; Discord access tokens encrypted; protection
against forged requests from other sites; no third-party content on the public pages, and after you sign in only
profile pictures and server icons from Discord (section 12.9). The website has no access to
the database; it asks Defendr through a signed interface that is reachable only inside the server.

## 11. Support tickets in the support server

<!-- anchor: support -->

11.1 Who and what. When you open a ticket in the `#contact-staff` channel of the Defendr & Checkout support server or on
the website under "My Defendr", we process: your Discord user ID, the topic you picked, the subject, the description
and the other fields of the form (stored encrypted), the server the summary in section 11.2 is about, the times of
opening and of the last activity, the private thread (in Discord it can be seen by you, Defendr's support staff, the
server's team role and whoever may manage threads in that channel), the transcript of its messages (section 11.4; on
the website only you, Defendr's support staff and the operator of Defendr see it, everyone else in the thread reads it
in Discord), who closed or reopened the ticket, and ticket bans (who set one and when). Purpose: answering your
request, in Discord and on the website, and troubleshooting. Legal basis: Art. 6(1)(b) GDPR where you use Defendr under
the terms of service, otherwise Art. 6(1)(f) GDPR.

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

<!-- anchor: support-transcript -->

11.4 Transcript. Defendr stores every message in the thread of your ticket encrypted as the ticket's transcript, so
that you and the support team can also read and answer the ticket on the website. It stores the text, of attachments
only the name, size, type, for pictures their width and height, and whether the attachment is marked as a spoiler (the
files themselves stay in Discord and open there), who wrote the message (Discord user ID, display name, username and
the profile picture identifier at that time), when it was written and last edited, whether it was written in Discord or
on the website, which message it replies to, and how many embeds, stickers, polls and forwarded messages it contains
(only the number, not their content). Of the posts Defendr itself puts into the thread (such as the summary of
section 11.2 or a status line) it stores only their type. When a message is edited, the new version replaces the stored one.
When it is deleted in Discord, Defendr deletes its content from the transcript too; only an empty placeholder stays in
its place. This happens right away while Defendr is running. If a message is edited or deleted while Defendr is briefly
not running (for example during an update), Defendr checks the newest 100 messages of every open ticket at its next
start; for older messages and for closed tickets, the last stored version then stays in the transcript. Ticket threads that already existed when this feature started are copied once
from Discord with their earlier messages; the same applies to them. Defendr does not store messages in the other
channels of the support server. As on every server Defendr protects, all messages are also checked for threats in
memory for a moment (section 3.1). Defendr closes a ticket automatically after seven days without activity (tickets of
the data-access-or-deletion topic are exempt; a person closes them once the request has been answered). The team can
reopen a ticket as long as the thread exists.

11.5 Reading and answering on the website. Under "My Defendr" you can read the transcript of your tickets and answer
them. The website never shows you more than Discord: you see a ticket as long as you are on the support server; if the
ticket is closed or you are timed out on the support server right now, you can read it but not answer; a thread that
was deleted in Discord is no longer shown on the website. While a ticket page is open, it checks for new messages about
every ten seconds. Before your reply is sent, Defendr checks it for dangerous links, like every message in Discord. Then
it appears in the thread in Discord, sent through a Defendr webhook under the name "display name (@username)" and with
your profile picture; for that Discord receives the text, this name and the address of your profile picture. A small
line "via the website" under the reply names your account without notifying you, and mentions in your reply notify
nobody. The name parts "Defendr", "Team", "Staff" and "Mod" are reserved for the Defendr team: if your display name
contains one of them, Defendr uses your username, and if that contains one too, the name "Member". If Defendr cannot
use a webhook in the channel, Defendr posts your reply into the thread itself, with your name, the line "via the
website" and your profile picture as a small image. You can delete replies you wrote on the website there while the
ticket is open. Defendr's support staff and the operator read and answer tickets on the website in the same way.

11.6 Retention. The ticket, the thread and the transcript are deleted
5 years after the ticket was closed (table in section 7). An open
ticket has no expiry date. If a ticket thread is deleted by hand in Discord, the stored transcript is kept until the
ticket's retention ends (5 years after closing). A ticket ban lasts
until the team lifts it.
A ticket thread left without its record (after a failed creation or a restore from a backup) is deleted
5 years after it was created; until then Defendr may lock and archive
it if nobody wrote in it. Because no record links it to a member, the team deletes it by hand on an erasure request.

11.7 Your rights. Your tickets are part of your export (/defendr › My data › Export), including the subject, the
description, the form fields and the transcript: your own messages in full, the answers of the support team with the
sender "staff" (without the name of the person who answered), and of other people's messages only their number. This also applies to a ticket whose thread
was deleted in Discord. A ticket ban appears in the export without the person who set it. An erasure (/defendr › My
data › Delete my data) deletes your tickets with their transcripts and their threads – an open ticket is ended by it
too; a ticket ban is kept (protection of others). If you wrote in another person's ticket, an erasure removes your user
ID and your name from that ticket's transcript; the text stays as part of the ticket, as it does in the thread in
Discord. The fastest way to make a request about your data is the My data page of /defendr
(/defendr page:mydata): it records the request and its deadline. A request you make in a ticket of the
data-access-or-deletion topic is handled just the same; the one-month deadline (Art. 12(3) GDPR) runs from the opening
of the ticket.

## 12. Website

<!-- anchor: website -->

12.1 Opening the website. When you open a page of defendr.live, app.defendr.live or status.defendr.live, your browser
sends technically necessary information: your IP address, the time, the address requested, the browser identifier
(user agent), preferred languages and, where applicable, the page you came from. All requests pass through the network
of Cloudflare, Inc. (processor, sections 5 and 6), which sets up the encrypted connection and protects the website
against attacks and overload. Cloudflare forwards requests to defendr.live and app.defendr.live through an encrypted
tunnel to our server; the status page runs entirely at Cloudflare (section 12.7). We rent our server from ZAP-Hosting
GmbH (Hafenweg 8, 48155 Münster, Germany, section 5); it is located in a data centre in Germany (Frankfurt am Main).

Our web server uses your IP address only to limit sign-ins and sign-outs per sender, and never writes it to files or a
database. For sign-ins, it keeps it in memory only (shortened to the network for IPv6), at the longest until one minute
after the last sign-in attempt from that network. For this purpose it passes Defendr only a check value made with a
secret key, which cannot be turned back into the address; Defendr, too, keeps it in memory only. For sign-outs, the web
server keeps only such a check value in memory, never the address itself, and at the longest until one minute after the
last sign-out from that sender. The web server creates the secret key anew every time it starts.

Cloudflare records requests with the IP address, time, address requested, browser identifier and, where applicable,
the protection rule that fired (for example a block or rate-limiting rule or a browser check) in analytics and
security logs that we can view in our Cloudflare account in order to recognise attacks and lift wrong blocks;
Cloudflare deletes them after 31 days. We have not set up any forwarding of these logs to other storage (Logpush). If
it suspects an attack, Cloudflare can show a browser check before a page; if your browser passes it, Cloudflare sets a
technically necessary cookie for it (`cf_clearance`, section 13). Beyond that, Cloudflare processes connection data
only as far as needed to operate and secure its network, under the data processing agreement. Legal basis:
Art. 6(1)(f) GDPR (a secure and available website).

12.2 Logs on our server. Our web server keeps an access log. An entry in it holds only the time, a path template, the
HTTP status, the duration and a random request ID. These access logs contain no IP addresses or IP hashes, no URL
parameters, no cookies, no credentials and no request contents; server IDs, other variable path values and unknown
paths are replaced with fixed placeholders, only the language stays. On very busy days or in a sudden flood of
requests, further requests are no longer recorded one by one but only counted. Purpose: finding errors and recognising
attacks. A running web server deletes entries older than 14 days when it starts and every
minute after that. Only when the storage set aside for these logs is full are older entries deleted earlier, the oldest
first. The logs of a stopped web server (for example the previous version after an update, or the preview) are deleted
after the same period by a separate task once a day, so entries there can be up to one day older.

Our web server also keeps an event log. It records server errors by page and type of error, texts missing in a
language, failures and refusals of the connection between the website and Defendr, failed sign-ins with their reason
only, how many entries the access log dropped, and when it deleted older entries early (with the minute from which the
deleted entries started). An entry in it never holds a person, an IP address, an address requested, URL parameters,
cookies, content or a session. Equal events of one minute are counted together in one entry. Purpose: finding errors
and recognising attacks. Its entries are deleted after the same 14 days and in the same
way as those of the access log; the event log takes at most 4 MiB, and when it is full, the oldest entries go first.

The encrypted tunnel to Cloudflare is run on our server by Cloudflare's program "cloudflared". It writes a log of its
own on our server, but only with errors that stop the program itself (log level "fatal") and warnings about its own
connection to Cloudflare (transport log level "warn"); addresses requested, other details of requests and IP addresses
of visitors are not in it. We use this log only to find connection errors. It is currently not deleted automatically
after a fixed period.

The web server writes no other log; its other output is discarded. The program that starts and watches it notes in its
own service log only when the web server started and ended, with the time and the exit code and without any details of
visitors.

12.3 Sign-in with Discord. Signing in is voluntary. Without it you can use all public pages and use Defendr fully in
Discord; only the personal area and the server administration of the website require a sign-in. You sign in through
Discord (OAuth2); Discord shows you beforehand what it passes on to Defendr, and we ask for two permissions only:
"identify" and "guilds". Through them we receive your Discord user ID, your user or display name, the identifier of
your avatar, the language setting of your Discord account, whether two-factor authentication is on, a time-limited
access permission from Discord (access token) and the list of your servers with your permissions there. We do not
receive your e-mail address or your password. With your avatar identifier and the details of your servers the website
shows you your profile picture and your servers' icons; your browser loads these pictures directly from Discord
(section 12.9). We store one session: user ID, display name, avatar identifier,
language, two-factor yes/no, the device category desktop or mobile (derived once at sign-in from the browser hint
"Sec-CH-UA-Mobile"; if your browser does not send it, desktop is recorded; we do not store the browser identifier
itself), times, a hash of the session identifier and the access token (encrypted). We do not store a refresh token.
We do not store your server list permanently; we fetch it with the access token when needed and keep it in memory for
at most five minutes, to show you the servers you can manage and to refuse at once a request about a server that is not
on it. The list never grants access: whether you may see or change something is checked by Defendr on every request
against the current data in Discord. The session ends after 7 days without activity,
after 30 days at the latest, and with an erasure of your data. If you sign out, it
ends as soon as Defendr confirms the sign-out. If Defendr cannot confirm it, this browser is signed out all the same and
the page tells you so; the session then ends once it has not been used for 7 days, or
when you sign in again and choose "Sign out everywhere". You can withdraw Defendr's access to your Discord account at
any time in Discord under Settings › Authorized Apps; then also end your sessions in the personal area or sign out so
that the session ends too.

12.4 Sign-in history. For your account we store when you signed in and out, when you signed out everywhere and when you
ended one other session, each with the time and, where known, the device category of section 12.3, but without an IP
address, without the browser identifier and without a location. We store a failed sign-in with your account in one
case only: when Discord had already confirmed you and Defendr then undid the sign-in because the session could not be
set up. If Discord refuses a sign-in or it fails before it is known who is signing in, only an anonymous count by
reason is kept, in the event log of section 12.2 and, where Defendr was already asked, in Defendr's own log, never with
a person. If you cancel on
Discord's consent screen, no failed sign-in is recorded for it. The history is part of your export (section 8); in the personal area you also see on which devices
you are signed in right now and can sign them out. The entries are deleted automatically after
365 days, and with an erasure of your data.

12.5 Personal settings. Your choice of language, colour scheme, accent colour, density and motion is kept in cookies
in your browser (section 13). If you save them while signed in under "Preferences", we store them, together with your
choice whether Defendr's direct messages follow the language of the website, with Defendr under your Discord ID; at
your next sign-in on another device they then apply there too. We also store up to which entry you have marked your
inbox in the personal area as read, and whether you have seen the note that your replies to a ticket appear in Discord
under your name (section 11.5). You can change the settings at any time. We keep the stored settings without a
fixed period, until you ask us to erase your data, so that they apply again on your next visit; an erasure deletes
them. We do not store when you last used them; the settings record only when you last saved them, and every save is in
the log of section 12.6 with its time and which settings changed (without the values). Revoking Defendr's access in
Discord under "Authorized Apps" (section 12.3) does not delete them; ask for erasure instead.

12.6 What you do on the website. Defendr handles reports, appeals, support tickets, requests about your rights,
exports and changes to server settings just as when you do them in Discord (sections 3.2 to 3.6, 8 and 11); the same
limits, rights and retention apply. For actions that start or change something we additionally keep a receipt
(reference number, type of action, server concerned, times, status and result; the request itself only as a check
value, a hash) so that a double click does not do anything twice and you can see the state. The receipt itself is
deleted 365 days after the action finished, earlier with an erasure of your data.
In addition, we record every action on the website that starts, changes or exports something in our action log:
your user ID, the type of action, what it concerns (such as the server, a case or a ticket), the time, the result, the
receipt and request ID and short reference details such as the revision number of changed server settings; for your
personal settings only which ones you changed, never the values. An action Defendr carries out later gets one entry
when it is accepted and one when it finishes. When you send or delete a reply in a ticket (section 11.5), the entry
names the ticket number, the type and the time, never the text; we keep no receipt for it. When Defendr's support
staff answer or act on the website, this is recorded in the action log in the same way. The entry serves accountability (Art. 6(1)(f) GDPR, Art. 5(2) GDPR), is
kept for 1825 days, is part of your export and is kept when your data is erased. Changes
you make to a server through the website appear, as in Discord, with your user ID in the server's history and log
channel, there with the note "via the website". A link you enter in the link checker is checked as with /check in
Discord and not stored. An export you request on the website can be downloaded only in the same session and only once,
for at most 15 minutes; the encrypted copy is deleted afterwards.

12.7 Status page. status.defendr.live shows only the operating state of Defendr and the website. It runs at Cloudflare
(Cloudflare Workers), not on our server, sets no cookies and stores no data about you; opening it is covered by
section 12.1.

12.8 E-mail. If you write to contact@defendr.live, privacy@defendr.live or security@defendr.live, Cloudflare
accepts the e-mail for our domain (Cloudflare Email Routing) and forwards it to our mailbox at Gmail, a service of
Google Ireland Limited (Gordon House, Barrow Street, Dublin 4, Ireland); Google thus receives your e-mail and also
stores it in the United States (sections 5 and 6). We process your e-mail address, the content and the technical
details of the e-mail to answer you. We delete e-mails as soon as they are no longer needed for handling them, at the
latest three years after the request is closed, unless a legal duty requires longer storage. We handle reports of
security vulnerabilities sent to security@defendr.live in order to check and fix the vulnerability (Art. 6(1)(f)
GDPR). We thank you for it in public with your name or pseudonym, for example in the changelog of the security update,
only if you consent (Art. 6(1)(a) GDPR). You can withdraw your consent at any time by e-mail to
security@defendr.live; we then remove the mention as far as we can. The withdrawal does not affect the lawfulness
of the mention until then.

12.9 No analytics, no advertising; pictures from Discord only after you sign in. The website uses no analytics or
statistics services, no tracking pixels, no advertising and no social media plugins, and our pages contain no captcha;
only Cloudflare may put an automatic browser check in front of a page if an attack is suspected (sections 12.1 and 13).
Fonts, scripts and our own images come from our own server; the only pictures from elsewhere are the Discord pictures
described below. The website does not embed videos or Discord widgets, and the public pages load nothing from Discord.

On the pages after you sign in (app.defendr.live) the website shows your profile picture and your servers' icons as
you know them from Discord, and on the pages of your support tickets the profile pictures of the people who wrote in
the ticket. Your browser loads these pictures directly from Discord's content delivery network (cdn.discordapp.com, run
for Discord by Cloudflare). Discord Inc. then receives your IP address, the browser identifier (user agent), the time
and the address of the picture, which contains your user ID, the server's ID or the user ID of the person in the
picture. For another person's profile picture, Discord thus learns that their picture was loaded from your IP address.
Your browser sends no referrer with these requests, and it sends and accepts no cookies for them. Discord processes these
data as a controller of its own under its own privacy policy, also in the USA (sections 5 and 6). Legal basis:
Art. 6(1)(f) GDPR (section 4).

Links to other sites, such as Discord (invite, sign-in, support server) or GitHub (previous versions of these texts), take you to
their pages, where their own privacy policies apply; our pages do not pass on where you came from.

## 13. Cookies and browser storage

<!-- anchor: cookies -->

The website stores only information in your browser that is strictly necessary for the service you explicitly asked
for (Section 25(2) no. 2 TDDDG): the sign-in and the settings you choose yourself. No consent is needed for that, which
is why there is no cookie banner. There are no tracking, advertising or analytics cookies. Our own cookies apply only
to exactly the address that sets them (defendr.live or app.defendr.live) and are sent only over HTTPS. You can delete
cookies in your browser at any time; you are then signed out and your settings return to their defaults.

| Name                           | Kind                                                             | Content                                                                                                         | Purpose                                                                                                               | Retention                                                                            |
| ------------------------------ | ---------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| `__Host-sid`                   | cookie (app.defendr.live, not readable by scripts)               | a random session identifier with a check value of the website (the server stores only a hash of the identifier) | keeps you signed in after you sign in                                                                                 | until you sign out; at most 30 days (the session ends after 7 days without activity) |
| `__Host-oauth`                 | cookie (app.defendr.live, not readable by scripts)               | sealed sign-in flow (random anti-forgery value, PKCE verifier, language, start time)                            | protects the Discord sign-in against forgery and replay                                                               | 10 minutes; deleted after the sign-in                                                |
| `__Host-lang`                  | cookie                                                           | the language you picked yourself (for example "de")                                                             | shows the website in the language you picked                                                                          | 1 year or until you change it                                                        |
| `__Host-theme`                 | cookie                                                           | your choice of light, dark or follow the system                                                                 | shows the website in the colour scheme you picked                                                                     | 1 year or until you change it                                                        |
| `__Host-motion`                | cookie                                                           | your motion choice (reduced, follow the system or full)                                                         | turns animations off or on as you chose                                                                               | 1 year or until you change it                                                        |
| `__Host-accent`                | cookie                                                           | your accent colour (signal green, grape, lagoon or graphite)                                                    | shows the website in the accent colour you picked                                                                     | 1 year or until you change it                                                        |
| `__Host-density`               | cookie                                                           | your density choice (normal or compact)                                                                         | shows lists and tables as dense as you chose                                                                          | 1 year or until you change it                                                        |
| `defendr.setup.v1.<Server-ID>` | browser session storage (app.defendr.live), one entry per server | your not yet saved answers in a server's setup wizard                                                           | so that reloading the page does not discard your answers; nothing goes to Defendr before you press "Check and finish" | until the setup is saved, you press "Cancel setup" or you close the tab              |

Cloudflare may set its own cookies to protect the website, which are strictly necessary as well, but only if we have
switched the protection feature concerned on:

| Name           | When                                                 | Purpose                                         | Retention                                                  |
| -------------- | ---------------------------------------------------- | ----------------------------------------------- | ---------------------------------------------------------- |
| `__cf_bm`      | Cloudflare's bot protection switched on              | protecting the website against bots and attacks | 30 minutes                                                 |
| `cf_clearance` | your browser had to pass a Cloudflare security check | spares you the check on every page view         | as set in Cloudflare, 30 minutes by default                |
| `_cfuvid`      | request limits per visitor switched on               | fair request limits per visitor                 | until you close the browser                                |
| `cf_chl_*`     | Cloudflare is showing you a security check right now | runs the security check                         | only during the check, at most until you close the browser |

## 14. Changes

Versions: https://github.com/FunnyBuddys/defendr-legal/tags. The current English text is at https://defendr.live/en/privacy. We announce significant changes in
advance in the changelog (/defendr › Changelog) and on the website.
