# Datenschutzerklärung für Defendr

Version 2026-09-25 · gültig ab 2026-09-25

## 1. Verantwortlicher

<!-- anchor: contact -->

Samuel Sakli, Wegsfeld 42, 30455 Hannover, Deutschland, E-Mail: support@seismicdrop.com. Kontakt in Discord: /defendr support.

## 2. Was ist Defendr?

<!-- anchor: summary -->

Defendr ist ein Sicherheits-Bot für Discord-Server. Er erkennt Phishing-Links, Schadsoftware-Links, betrügerische
Bilder, QR-Codes zur Übernahme von Discord-Konten, Spam, Raids und übernommene Konten. Defendr läuft ausschließlich in
Discord. Es gibt keine Website, kein Web-Dashboard und keine Anmeldung außerhalb von Discord.

## 3. Welche Daten wir verarbeiten

<!-- anchor: data -->

3.1 Nachrichteninhalte (Text, Einbettungen, Anhänge, weitergeleitete Nachrichten, Umfragen) werden kurzzeitig im
Arbeitsspeicher geprüft und nicht gespeichert. Ausnahme nur, wenn ein Server dies ausdrücklich
einschaltet (standardmäßig aus): Bei Nachrichten, gegen die Defendr vorgeht, wird ein gekürzter, entschärfter Auszug
gespeichert (verschlüsselt, Löschung spätestens nach 1095 Tagen, früher mit dem
Moderationsfall).

3.2 Moderationsfälle und Erkennungen: Discord-Nutzer-ID, Grund-Code, Maßnahme, Zeitpunkt, Server-ID.

3.3 Beitritte: Nutzer-ID, Konto-Erstellungsdatum, Avatar vorhanden ja/nein, zeitlich begrenzte Markierungen
(z. B. „Verifizierung ausstehend") – für Raid-Erkennung, Zugangsregeln und Verifizierung.

3.4 Sicherheitseinträge (Safety Records) im Defendr-Netzwerk: Nutzer-ID, Grund-Code, Nachweise, Prüfstatus,
Ablaufdatum. Ungeprüfte Einträge werden Moderatoren nur als Hinweis angezeigt und lösen nie automatisch Maßnahmen aus.
Das Defendr-Team kann die Netzwerk-Einträge einer Person und die Zahl der Moderationsfälle pro Server nur mit
angegebenem Grund nachschlagen; jede solche Abfrage wird protokolliert, und solange eine Einschränkung der Verarbeitung
gilt, sieht das Team zu jedem Eintrag nur ID, Quelle und Status.

3.5 Meldungen (auch als Mitmeldender), Einsprüche und Anfragen zu deinen Rechten: der Text, den du selbst schreibst.
Dateien, die du mitschickst, werden nicht gespeichert: Ein gemeldetes Bild wird einmal beim Melden gehasht und statt
des Bildes wird nur der Hash behalten, von jedem anderen Anhang wird nur vermerkt, dass du ihn angeboten hast (wie
viele, und als was Discord sie ausgibt), damit die bearbeitende Person danach fragen kann.

3.6 Server-Einstellungen: Rollen- und Kanal-IDs, IDs der Admins und Moderatoren, die Einstellungen ändern oder
Entscheidungen treffen. Beantwortet ein Admin in `/setup` die freiwillige Frage „Wo hast du Defendr gefunden?", wird
eine von sechs festen Antworten (zum Beispiel „top.gg" oder „Freunde oder Bekannte") für den Server gespeichert und
keiner Person zugeordnet. Sie dient nur dazu, zu verstehen, wie Server Defendr finden, wird dem Defendr-Team nur als
Anzahl über alle Server gezeigt und zusammen mit der Server-Konfiguration gelöscht.

3.7 Keine IP-Adressen, keine Geräte-Daten, keine Profile, kein Training von KI-Modellen.

3.8 Die vollständige Liste aller Datenkategorien mit ihrer Speicherdauer steht in Abschnitt 7. Sie wird aus demselben
Verzeichnis erzeugt, aus dem die Löschjobs ihre Fristen lesen.

3.9 Aufsicht über den Bot selbst: Das Defendr-Team führt auf dem Defendr-Server einen privaten Kanal mit einem Eintrag
je Aktion, die Defendr auf irgendeinem Server ausgeführt hat, und je Moderations-, Melde- und Einspruchsvorgang, der über
Defendr abgewickelt wurde — Nutzer-, Server- und Kanal-IDs, einschließlich der ID des Moderators oder Teammitglieds, das
gehandelt hat, die Namen, die Discord in dem Moment dafür anzeigte (Servername, Kanalname, Anzeige- oder Nutzername des
Mitglieds und des Moderators oder Teammitglieds), die Art der Aktion oder des Vorgangs, Zählwerte und Zeiten und den
gelisteten Bedrohungswert, den ein erkannter Link oder eine erkannte Einladung getroffen hat (aus einer
Bedrohungsliste, nie was das Mitglied geschrieben hat); nie den Inhalt einer Nachricht, einer Notiz, einer Meldung oder
eines Einspruchs, nie wer wen gemeldet hat. Er existiert, damit das Team sieht, was der Bot über alle Server hinweg tut, und einen Fehler bemerkt
(berechtigtes Interesse, Abschnitt 4). Er wird aufbewahrt, bis das Team ihn löscht.

3.10 Support-Tickets im Support-Server: Nutzer-ID, Thema, Betreff, Beschreibung und Formularfelder (verschlüsselt),
der private Thread, wer das Ticket geschlossen oder wieder geöffnet hat, Ticket-Sperren. Was genau, wozu und wie
lange, steht in Abschnitt 11.

## 4. Zwecke und Rechtsgrundlagen

<!-- anchor: purposes -->

- Schutz von Discord-Communities vor Betrug, Schadsoftware und Missbrauch: Art. 6 Abs. 1 lit. f DSGVO.
- Bearbeitung von Einsprüchen und Betroffenenanfragen: Art. 6 Abs. 1 lit. c und f DSGVO.
- Netzwerkweite Sicherheitseinträge: Art. 6 Abs. 1 lit. f DSGVO; Interessenabwägung verfügbar auf Anfrage.
- Verstehen, wie Server Defendr finden (die freiwillige Setup-Antwort „Wo hast du Defendr gefunden?", pro Server
  gespeichert und keiner Person zugeordnet): Art. 6 Abs. 1 lit. f DSGVO; die Antwort ist freiwillig und kann
  ausgelassen werden.
- Aufsicht über Defendrs eigene Aktionen und über die darüber abgewickelten Moderations-, Melde- und
  Einspruchsvorgänge (Abschnitt 3.9): Art. 6 Abs. 1 lit. f DSGVO.
- Bearbeitung von Support-Tickets im Support-Server (Abschnitt 11): Art. 6 Abs. 1 lit. b DSGVO, soweit du Defendr
  nach den Nutzungsbedingungen nutzt, sonst Art. 6 Abs. 1 lit. f DSGVO.
  <!-- OD-17: anwaltliche Prüfung — Rechtsgrundlage der Support-Tickets (lit. b gegenüber Nutzern, lit. f sonst) -->

## 5. Empfänger

<!-- anchor: processors -->

Discord Inc. (Plattform), Moderatoren des jeweiligen Servers (nur eigene Serverdaten), Offsite-Backup-Anbieter (noch nicht festgelegt, OD-12) (EU, verschluesselte Offsite-Backups; nur wenn aktiviert (OD-12)); Google Ireland Ltd. (Web Risk) (EU/US, Abfrage einzelner URLs gegen die Google-Web-Risk-Liste; nur wenn aktiviert (OD-6)).

Der Betreiber führt Erkennungsdaten aus allen Servern, auf denen Defendr läuft, in
einem teaminternen Kanal auf dem Support-Server zusammen. Dieser Kanal enthält
**keine Nachrichteninhalte** – nur Server, Kanal, betroffene Nutzerkennung, die
ergriffene Maßnahme, den erkannten Indikator (entschärft dargestellt), technische
Prüfsummen und den Zeitpunkt. Zweck ist der Betrieb und die Missbrauchsabwehr über
alle Server hinweg; Zugriff haben ausschließlich der Betreiber und das Support-Team.

## 6. Übermittlung in Drittländer

Discord (USA) – die Nutzung von Discord unterliegt Discords eigener Datenschutzerklärung. Discord Inc. verarbeitet Daten auch in den USA. Weitere Uebermittlungen in Drittlaender finden nicht statt; Auftragsverarbeiter mit Standort EU/US werden erst eingesetzt, wenn die jeweilige Owner-Entscheidung sie freigibt.

## 7. Speicherdauer

<!-- anchor: retention -->

| Datenkategorie | Speicherdauer | Löschmechanismus |
| --- | --- | --- |
| Nachrichteninhalte während der Prüfung | Sekunden (nur im Arbeitsspeicher) | wird nicht gespeichert |
| Erkennungen (IDs, Typ, Maßnahme; keine Nachrichteninhalte) | 1825 Tage | `retention.purge` |
| Moderationsfälle (samt Ereignissen) | 1825 Tage (von Defendr festgelegt, in jedem Server gleich) | `retention.purge` |
| Nachrichtenauszüge (pro Server ausdrücklich eingeschaltet) | höchstens 1095 Tage, nie länger als der Fall | Löschung (verschlüsselt; Schlüsselvernichtung) |
| Hochgeladene Nachweise (vom Team zu Sicherheitseinträgen und Fällen hinterlegt) | 1095 Tage; Nachweise zu Sicherheitseinträgen mit dem Eintrag; eine rechtliche Aufbewahrungspflicht setzt die Löschung aus; was ein Mitglied mitschickt, wird nicht gespeichert | Löschung + Dateilöschung (Schlüsselvernichtung) |
| Meldungen und Mitmeldende | angenommen: 1825 Tage nach der Entscheidung; abgelehnt/Spam: 365 Tage; offen: automatisch geschlossen nach 90 Tagen | Löschung |
| Verlässlichkeit meldender Personen | 1825 Tage nach der letzten Meldung | Löschung |
| Fehlalarm-Signale (Moderator-ID, Fall) | 1095 Tage | Löschung |
| Prüfstimmen und Team-Threads | mit dem geprüften Eintrag | Löschung (samt Thread) |
| Einsprüche (samt Empfehlungen) | 1825 Tage nach der Entscheidung oder dem Fristablauf | Löschung |
| Support-Tickets (Formulartext verschlüsselt; der private Thread im Support-Server) und Ticket-Sperren | 1825 Tage nach dem Schließen (Eintrag und Thread); ein Ticket-Thread, der ohne seinen Eintrag zurückbleibt (nach einer fehlgeschlagenen Erstellung oder einer Wiederherstellung aus einer Sicherung), wird 1825 Tage nach seiner Erstellung gelöscht (bis dahin ggf. gesperrt und archiviert) – weil kein Eintrag ihn mit einem Mitglied verknüpft, löscht das Team ihn auf einen Löschantrag hin von Hand; Ticket-Sperren bis zur Aufhebung | `support.tickets` (zuerst der Thread, dann der Eintrag; ein Thread ohne Eintrag über die Merkliste des Jobs, `kv.support.orphans`); eine Sperre wird bei der Aufhebung gelöscht |
| Betroffenenanfragen; Verarbeitungseinschränkungen | 1825 Tage (Rechenschaftspflicht; Inhalte minimiert und verschlüsselt); Einschränkungen 1825 Tage nach der Aufhebung | Löschung |
| Aktiver netzwerkweiter Sicherheitseintrag | kein automatischer Ablauf; Erinnerung zur erneuten Prüfung nach 12 Monaten (eine Statusänderung erfordert immer eine Entscheidung des Teams) | Erinnerung zur erneuten Prüfung + Löschung 1095 Tage nach dem Abschluss |
| Importierte Einträge in Quarantäne (811 + 4) | bis zur Prüfung (reviewed); Erinnerung nach 6 Monaten (OD-7) | Prüfentscheidung |
| Abgeschlossene Sicherheitseinträge (aufgehoben/abgelehnt/abgelaufen) | 1095 Tage | Löschung |
| Mitglieds-Markierungen: übernommenes Konto / Raid-Gruppe / Hinweis angezeigt | 72 Stunden / 7 Tage / 30 Tage | `member-flags.expire` |
| Mitglieds-Markierung: Verifizierung ausstehend | mindestens 24 Stunden, so lange wie die Kick-Frist des Servers + 1 Stunde | `member-flags.expire` |
| Mitglieds-Markierungen: Quarantäne-Rolle der Zugangsregeln / von Defendr vergebene Verdachtsrolle | solange die Rolle besteht; 30 Tage nach dem Verlassen | Abgleich-Jobs + `member-flags.expire` |
| Raid-Gruppen (nur Metadaten) | 365 Tage | Löschung |
| Vorfälle | 1825 Tage | Löschung |
| Anti-Nuke: entzogene Rollen / Strukturabbilder / gelöschte Objekte (2.1) | 30 / 7 / 14 Tage | Löschung |
| Einträge zu Server-Sperren | 1095 Tage nach dem Ende | Löschung |
| Verifizierungs-Aufgaben | 24 Stunden | Löschung |
| Zustand interaktiver Ansichten (verschlüsselt) | höchstens 24 Stunden | `ui_state.purge` |
| Ausstehende Nachrichten (Postausgang) | Inhalt wird beim Versand oder beim Aufgeben gelöscht; Zeilen 7 Tage (gesendet) / 30 Tage (fehlgeschlagen) | Löschung |
| Einstellungs-Versionen; Entscheidungen zu Voreinstellungs- und Migrationskarten | letzte 100, höchstens 1 Jahr; Entscheidungen 90 Tage | Löschung |
| Protokoll der Team-Zugriffe (`ops_audit`, samt Einsicht in Nachweise) | 1825 Tage | Löschung |
| Team-Mitgliedschaft | 1825 Tage nach der Deaktivierung | Löschung |
| Anonyme Netzwerk-Signale (2.1) | 48 Stunden | Löschung |
| Premium-Berechtigungen (2.2) | 30 Tage nach dem Ende | Löschung |
| Anwendungsprotokolle (ohne Nachrichteninhalte) | 90 Tage | Rotation |
| Globaler Spiegel (#global-logs, Staff-Kanal): IDs, Aktions- und Vorgangsarten, Zählwerte und Zeiten der Aktionen von Defendr und der darüber abgewickelten Moderations-, Melde- und Einspruchsvorgänge (einschließlich Moderator- und Team-IDs), die Namen, die Discord in dem Moment für den Server, den Kanal, das Mitglied und den Moderator oder das Teammitglied anzeigte, und der gelistete Bedrohungswert, den ein erkannter Link oder eine erkannte Einladung getroffen hat; nie Nachrichteninhalte | bis der Betreiber ihn löscht (vom Betreiber festgelegte Speicherdauer, Entscheidung 2026-09) | Betreiber (Discord-Kanal) |
| Fehlerereignisse (bereinigt) | 365 Tage | Löschung |
| Statistik-Kennzahlen (ohne Nutzer-IDs): Zählwerte pro Tag, Server und Kennzahl, auch je Begründungscode und je Erkennungsfamilie | unbegrenzt | — |
| Setup-Antwort „Wo hast du Defendr gefunden?" (pro Server, freiwillig; keiner Person zugeordnet) | mit der Server-Konfiguration: 90 Tage nachdem Defendr den Server verlassen hat (oder sofort, wenn so eingestellt) | `guilds.purge` |
| Alle Serverdaten, nachdem Defendr den Server verlassen hat | 90 Tage (oder sofort, wenn so eingestellt); durch erneute Einladung aufgehoben | `guilds.purge` |
| Lokale Sicherungen | 14 täglich / 8 wöchentlich / 6 monatlich | Bereinigung |
| Auswärtige Sicherungen (verschlüsselt) | 14 täglich / 8 wöchentlich / 12 monatlich | restic forget/prune |
| Verlaufs-Dossiers aus Version 1 | nicht übernommen; bei der Abschaltung von Version 1 vernichtet (T+30 Tage, verschlüsseltes Archiv nach 90 Tagen vernichtet) | Runbook des Betreibers |

Löschungen innerhalb von Sicherungen erfolgen durch deren Rotation; die maximale Aufbewahrung der Sicherungen steht in
der Tabelle.

## 8. Deine Rechte

<!-- anchor: rights -->

Auskunft (/defendr mydata export), Löschung (/defendr mydata delete), Widerspruch (/defendr mydata object),
Berichtigung (/defendr mydata rectify), Einschränkung (/defendr mydata restrict), Überprüfung von Entscheidungen
(/appeal), Beschwerde bei einer Aufsichtsbehörde (Der Landesbeauftragte für den Datenschutz Niedersachsen, Prinzenstraße 5, 30159 Hannover, Deutschland).

Support-Tickets (Abschnitt 11) sind Teil des Exports und werden mit einer Löschung gelöscht; eine Ticket-Sperre bleibt
bestehen (Abschnitt 11.6).

## 9. Automatisierte Entscheidungen

Server-Betreiber legen fest, wie Defendr auf erkannte Bedrohungen reagiert. Defendr begrenzt
Maßnahmen nach der Verlässlichkeit des Nachweises (z. B. nie Bann allein aufgrund externer Listen).

Netzwerkweite Einträge wirken nie ohne menschliche Prüfung. Jede Entscheidung kann mit
/appeal überprüft werden: Über Fälle eines Servers entscheiden dessen Moderatoren, über netzwerkweite Einträge das
Defendr-Team.

Direktnachrichten schickt Defendr nur, wenn eine Maßnahme dich betrifft oder wenn du selbst
einen Vorgang gestartet hast (Einspruch, Meldung, Betroffenenanfrage) – nie als Werbung oder Begrüßung.

## 10. Sicherheit

Verschlüsselung gespeicherter sensibler Daten, Zugriffsbeschränkung, Protokollierung von Mitarbeiterzugriffen,
regelmäßige Backups.

## 11. Support-Tickets im Support-Server

<!-- anchor: support -->

11.1 Wer und was. Wenn du im Kanal `#contact-staff` des Support-Servers von Defendr und Checkout ein Ticket öffnest,
verarbeiten wir: deine Discord-Nutzer-ID, das gewählte Thema, Betreff, Beschreibung und die weiteren Felder des
Formulars (verschlüsselt gespeichert), den Server, um den es in der Übersicht in Abschnitt 11.2 geht, die Zeitpunkte
des Öffnens und der letzten Aktivität, den privaten Thread mit seinen Nachrichten (er bleibt auf Discord; sehen können
ihn du, das Support-Team von Defendr, die Team-Rolle des Servers und wer in dem Kanal Threads verwalten darf), wer das
Ticket geschlossen oder wieder geöffnet hat, sowie Ticket-Sperren (wer sie gesetzt hat und wann). Zweck: die
Beantwortung deiner Anfrage und die Fehlersuche. Rechtsgrundlage: Art. 6 Abs. 1 lit. b DSGVO, soweit du Defendr nach
den Nutzungsbedingungen nutzt, sonst Art. 6 Abs. 1 lit. f DSGVO.

11.2 Was der Thread dem Team automatisch zeigt. Beim Öffnen stellt Defendr in den Thread nur das, was du selbst schon
über dich sehen kannst: deine eigenen Moderationsfälle, netzwerkweiten Einträge, Einsprüche und Betroffenenanfragen,
eine Einschränkung der Verarbeitung, die für dich gilt, und das Ergebnis der Prüfung eines Links, den du ins Formular
geschrieben hast. Bei Themen zu einem Server zeigt es die Einrichtungsübersicht eines Servers, den du verwaltest: des
Servers, den du auswählst, oder des einzigen, den Defendr bestätigen kann. Daten anderer Personen zeigt es nie. Alles
darüber hinaus ist eine Abfrage durch das Team, wie in Abschnitt 3.4 beschrieben.

11.3 Checkout-Themen. Defendr und Checkout sind zwei getrennte Bots mit getrennten Daten; beide betreibt der in
Abschnitt 1 genannte Verantwortliche auf demselben Rechner. Für die beiden Checkout-Themen (Einrichtung, Fehler) liest
Defendr aus den Dateien des Checkout-Bots die Checkout-Konfiguration des Servers, den du auswählst, deine eigenen
Zeiterfassungswerte in diesem Server und Summenwerte dieses Servers (Anzahl erfasster Personen und Sitzungen, keine
Werte einzelner anderer Personen) – nur lesend. Das Ergebnis erscheint nur im privaten Thread; Defendr speichert davon
nichts.

11.4 Kein Transkript. Defendr legt keine Abschrift des Threads an und wertet für das Ticket nur den Zeitpunkt der
neuesten Nachricht aus, um ein Ticket nach sieben Tagen ohne Aktivität automatisch zu schließen (Tickets zum Thema
Datenauskunft oder Löschung ausgenommen; sie schließt eine Person, sobald die Anfrage beantwortet ist). Wie auf jedem
Server, den Defendr schützt, werden Nachrichten im Thread kurz im Arbeitsspeicher geprüft und nicht gespeichert
(Abschnitt 3.1). Das Team kann ein Ticket wieder öffnen, solange der Thread besteht.

11.5 Speicherdauer. Ticket und Thread werden fünf Jahre nach dem Schließen des Tickets gelöscht (Tabelle in
Abschnitt 7). Ein offenes Ticket hat kein Ablaufdatum. Eine Ticket-Sperre gilt, bis das Team sie aufhebt. Ein
Ticket-Thread, der ohne seinen Eintrag zurückbleibt (nach einer fehlgeschlagenen Erstellung oder einer
Wiederherstellung aus einer Sicherung), wird fünf Jahre nach seiner Erstellung gelöscht; bis dahin kann Defendr ihn
sperren und archivieren, wenn niemand darin geschrieben hat. Weil kein Eintrag ihn mit einem Mitglied verknüpft, löscht
das Team ihn auf einen Löschantrag hin von Hand.

11.6 Deine Rechte. Deine Tickets sind Teil deines Exports (/defendr mydata export), samt Betreff, Beschreibung und
Formularfeldern; die Nachrichten im Thread stehen nur auf Discord und bleiben für dich sichtbar, solange der Thread
besteht. Eine Ticket-Sperre erscheint im Export ohne die Person, die sie gesetzt hat. Eine Löschung
(/defendr mydata delete) löscht deine Tickets und ihre Threads – auch ein offenes Ticket wird dadurch beendet; eine
Ticket-Sperre bleibt bestehen (Schutz anderer). Am schnellsten stellst du eine Anfrage zu deinen Daten mit
/defendr mydata: Sie hält die Anfrage und ihre Frist fest. Eine Anfrage, die du in einem Ticket zum Thema
Datenauskunft oder Löschung stellst, behandeln wir genauso; die Frist von einem Monat (Art. 12 Abs. 3 DSGVO) läuft ab
dem Öffnen des Tickets.

<!-- OD-17: anwaltliche Prüfung — 11.3: Zweckänderung (Art. 6 Abs. 4) beim lesenden Zugriff auf Checkout-Daten, Hinweis in Checkouts Datenschutzerklärung, veralteter Checkout-Inhaber; 11.6: ein Ticket zum Thema Datenauskunft oder Löschung ist eine eingegangene Betroffenenanfrage, Fristbeginn mit dem Öffnen des Tickets; Rechte an Ticket-Sperren nach Löschung -->

## 12. Änderungen

Versionen: https://github.com/FunnyBuddys/defendr-legal/tags. Die jeweils geltende Fassung steht unter https://github.com/FunnyBuddys/defendr-legal/blob/main/privacy.de.md.
