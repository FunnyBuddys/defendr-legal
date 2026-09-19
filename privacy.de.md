> ENTWURF – anwaltliche Prüfung erforderlich / DRAFT – requires legal review

# Datenschutzerklärung für Defendr

Version 2026-09-19 · gültig ab 2026-09-19

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

3.5 Meldungen (auch als Mitmeldender), Einsprüche und Anfragen zu deinen Rechten: Inhalte und Dateien, die du selbst
übermittelst.

3.6 Server-Einstellungen: Rollen- und Kanal-IDs, IDs der Admins und Moderatoren, die Einstellungen ändern oder
Entscheidungen treffen.

3.7 Keine IP-Adressen, keine Geräte-Daten, keine Profile, kein Training von KI-Modellen.

3.8 Die vollständige Liste aller Datenkategorien mit ihrer Speicherdauer steht in Abschnitt 7. Sie wird aus demselben
Verzeichnis erzeugt, aus dem die Löschjobs ihre Fristen lesen.

## 4. Zwecke und Rechtsgrundlagen

<!-- anchor: purposes -->

- Schutz von Discord-Communities vor Betrug, Schadsoftware und Missbrauch: Art. 6 Abs. 1 lit. f DSGVO.
- Bearbeitung von Einsprüchen und Betroffenenanfragen: Art. 6 Abs. 1 lit. c und f DSGVO.
- Netzwerkweite Sicherheitseinträge: Art. 6 Abs. 1 lit. f DSGVO; Interessenabwägung verfügbar auf Anfrage.

[Prüfhinweis Anwalt: Art. 10 DSGVO, Art. 22 DSGVO, gemeinsame Verantwortlichkeit mit Server-Betreibern (Art. 26)]

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
| Hochgeladene Nachweise (Meldungen, Einsprüche, Berichtigungsanfragen) | 1095 Tage; Nachweise zu Meldungen 1095 Tage nach der Entscheidung; Nachweise zu Sicherheitseinträgen mit dem Eintrag; eine rechtliche Aufbewahrungspflicht setzt die Löschung aus | Löschung + Dateilöschung (Schlüsselvernichtung) |
| Meldungen und Mitmeldende | angenommen: 1825 Tage nach der Entscheidung; abgelehnt/Spam: 365 Tage; offen: automatisch geschlossen nach 90 Tagen | Löschung |
| Verlässlichkeit meldender Personen | 1825 Tage nach der letzten Meldung | Löschung |
| Fehlalarm-Signale (Moderator-ID, Fall) | 1095 Tage | Löschung |
| Prüfstimmen und Team-Threads | mit dem geprüften Eintrag | Löschung (samt Thread) |
| Einsprüche (samt Empfehlungen) | 1825 Tage nach der Entscheidung oder dem Fristablauf | Löschung |
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
| Fehlerereignisse (bereinigt) | 365 Tage | Löschung |
| Statistik-Kennzahlen (ohne Nutzer-IDs): Zählwerte pro Tag, Server und Kennzahl, auch je Begründungscode und je Erkennungsfamilie | unbegrenzt | — |
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

## 11. Änderungen

Versionen: https://github.com/FunnyBuddys/defendr-legal/tags. Die jeweils geltende Fassung steht unter https://github.com/FunnyBuddys/defendr-legal/blob/main/privacy.de.md.
