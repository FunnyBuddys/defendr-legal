# Datenschutzerklärung für Defendr

Version 2026-10-24 · gültig ab 2026-10-24

## 1. Verantwortlicher

<!-- anchor: contact -->

Samuel Sakli, c/o Autorenglück #66851, Albert-Einstein-Straße 47, 02977 Hoyerswerda, Deutschland, E-Mail: contact@defendr.live. Für Fragen zum Datenschutz und für Anfragen zu
deinen Rechten: privacy@defendr.live. Kontakt in Discord: /defendr › Support. Einen Datenschutzbeauftragten haben
wir nicht benannt.

## 2. Was ist Defendr?

<!-- anchor: summary -->

Defendr ist ein Sicherheits-Bot für Discord-Server. Er erkennt Phishing-Links, Schadsoftware-Links, betrügerische
Bilder, QR-Codes zur Übernahme von Discord-Konten, Spam, Raids und übernommene Konten.

Zu Defendr gehört außerdem die Webseite defendr.live: öffentliche Informationsseiten, ein persönlicher Bereich („Mein
Defendr“) und eine Server-Verwaltung unter app.defendr.live, in die du dich mit deinem Discord-Konto anmeldest, sowie
eine Statusseite unter status.defendr.live. Die Webseite ist ein zweiter Weg zu denselben Funktionen: Du siehst und
darfst dort nur, was Defendr dir auch in Discord zeigt und erlaubt. Es gibt kein eigenes Defendr-Konto, kein Passwort
und keine Registrierung mit E-Mail-Adresse. Was die Webseite verarbeitet, steht in Abschnitt 12 und 13.

## 3. Welche Daten wir verarbeiten

<!-- anchor: data -->

3.1 Nachrichteninhalte (Text, Einbettungen, Anhänge, weitergeleitete Nachrichten, Umfragen) werden kurzzeitig im
Arbeitsspeicher geprüft und nicht gespeichert. Eine Ausnahme gilt, wenn ein Server dies
ausdrücklich einschaltet (standardmäßig aus): Bei Nachrichten, gegen die Defendr vorgeht, wird ein gekürzter,
entschärfter Auszug gespeichert (verschlüsselt, Löschung spätestens nach 1095 Tagen,
früher mit dem Moderationsfall). Eine zweite Ausnahme: Was du Defendr per Direktnachricht schreibst (Text, Dateinamen
und Links), bleibt in einem privaten Kanal des Defendr-Support-Servers, damit das Defendr-Team es lesen und dir
antworten kann – bis 1825 Tage nach der letzten Nachricht der Unterhaltung
oder bis zu deinem Löschantrag (siehe 3.11). Eine dritte Ausnahme gilt nur im Support-Server von Defendr: Die
Nachrichten in Support-Ticket-Threads (private Threads zwischen dir und dem Support-Team von Defendr) werden
verschlüsselt als Verlauf des Tickets gespeichert, damit du und das Team das Ticket auch auf der Webseite lesen und
beantworten könnt (siehe Abschnitt 11.4). Eine vierte Ausnahme: Meldet jemand eine Nachricht an das Defendr-Team,
speichert Defendr eine versiegelte Kopie dieser Nachricht, damit das Team die Meldung prüfen kann (siehe 3.16). Beim
Wortfilter prüft Discord die Nachrichten selbst (siehe 3.17).

3.2 Moderationsfälle und Erkennungen: Discord-Nutzer-ID, Grund-Code, Maßnahme, Zeitpunkt, Server-ID.

3.3 Beitritte: Nutzer-ID, Konto-Erstellungsdatum, Avatar vorhanden ja/nein, zeitlich begrenzte Markierungen
(z. B. „Verifizierung ausstehend") – für Raid-Erkennung, Zugangsregeln und Verifizierung.

3.4 Sicherheitseinträge (Safety Records) im Defendr-Netzwerk: Nutzer-ID, Grund-Code, Nachweise, Prüfstatus, Ablaufdatum.
Einträge aus externen Listen und Einträge, die noch auf ihre Prüfung warten, werden Moderatoren nur als Warnung
angezeigt und lösen von sich aus nie eine automatische Maßnahme aus. Dazu gehören die Einträge, die Defendr automatisch
aus den ScammerAlert-Community-Listen übernimmt: Seit Version 2.0.9 werden sie automatisch zu aktiven
Netzwerk-Einträgen, außer der Betreiber hat das abgeschaltet oder eine Sicherheitsgrenze hält sie zurück. Sie sind mit
der Liste gekennzeichnet, aus der sie stammen („bekannte Betrugskonten“, „Vorsicht“ oder, bei älteren Einträgen, „Liste
nicht erfasst“), und als externe Liste. Die Karte, die Moderatoren beim Beitritt einer solchen Person auf ihren Server bekommen, zeigt außerdem den
Grund, den ScammerAlert für den Eintrag angibt, aber nur in einem Protokollkanal, den nicht alle auf dem Server sehen
können. Sie werden automatisch zurückgenommen, sobald ScammerAlert den Eintrag durchstreicht oder löscht. Hat ein Mensch
bei Defendr einen früheren Eintrag über dich geschlossen (etwa nach einem Einspruch), wird ein neuer ScammerAlert-Eintrag
über dich nicht von selbst aktiv. Ein Server kann diese Warnungen abschalten. Ein Moderator, der eine solche Warnung
sieht, kann selbst entscheiden, deshalb etwas zu unternehmen; das ist seine eigene Entscheidung und wird als sein Fall
festgehalten. Das Defendr-Team schlägt die Netzwerk-Einträge einer Person und die Zahl der Moderationsfälle pro Server
nach, um Meldungen, Einsprüche und Anfragen zu bearbeiten. Der Betreiber von Defendr kann einen Netzwerk-Eintrag auch
selbst aktivieren, aufgrund seiner eigenen Einschätzung oder der Meldungen der ScammerAlert-Community-Liste, auch ohne
Nachweise. Ein solcher Eintrag ist überall, wo er angezeigt wird, als Entscheidung
des Inhabers gekennzeichnet; Defendr speichert, wann und von wem entschieden wurde und wie viele Nachweise der Eintrag
zu diesem Zeitpunkt hatte. Er bleibt für Moderatoren ein Hinweis und löst nie eine automatische Maßnahme aus. Ein so
ohne Nachweise entschiedener Eintrag, der auf der ScammerAlert-Liste beruht, wird automatisch entfernt, wenn
ScammerAlert den Eintrag streicht.

3.5 Meldungen (auch als Mitmeldender), Einsprüche und Anfragen zu deinen Rechten: der Text, den du selbst schreibst.
Dateien, die du mitschickst, werden nicht gespeichert, mit einer Ausnahme: Bilder, die du einer Meldung an das
Defendr-Team anhängst, behält Defendr als neu erzeugte Kopie ohne Metadaten (siehe 3.16). Ein gemeldetes Bild wird
einmal beim Melden gehasht und der Hash behalten; von jedem anderen Anhang wird nur vermerkt, dass du ihn angeboten
hast (wie viele, als was Discord sie ausgibt und wie groß), damit die bearbeitende Person danach fragen kann. Bei Meldungen an
die Moderatoren eines Servers, bei Einsprüchen und bei Anfragen zu deinen Rechten speichert Defendr keine Bilder.

3.6 Server-Einstellungen: Rollen- und Kanal-IDs, IDs der Admins und Moderatoren, die Einstellungen ändern oder
Entscheidungen treffen. Beantwortet ein Admin in `/setup` die freiwillige Frage „Wo hast du Defendr gefunden?", wird
eine von sechs festen Antworten (zum Beispiel „top.gg" oder „Freunde oder Bekannte") für den Server gespeichert und
keiner Person zugeordnet. Sie dient nur dazu, zu verstehen, wie Server Defendr finden, wird dem Defendr-Team nur als
Anzahl über alle Server gezeigt und zusammen mit der Server-Konfiguration gelöscht.

3.7 Defendr speichert keine IP-Adressen in seiner Datenbank, erstellt keine Gerätefingerabdrücke
und keine verhaltensbezogenen Profile und trainiert keine KI-Modelle. Beim Aufruf der Webseite wird deine IP-Adresse
technisch verarbeitet: Unser Webserver hält sie nur kurz im Arbeitsspeicher, und Cloudflare als unser
Auftragsverarbeiter hält sie in Analyse- und Sicherheitsprotokollen fest. Auf den Seiten nach der Anmeldung erhält
auch Discord sie, wenn dein Browser dort Profilbilder und Server-Symbole von Discord lädt. Was dabei genau geschieht,
steht in Abschnitt 12.

3.8 Die vollständige Liste aller Datenkategorien mit ihrer Speicherdauer steht in Abschnitt 7. Sie wird automatisch aus
denselben Einstellungen erzeugt, nach denen Defendr die Daten löscht.

3.9 Übersicht über die Aktionen von Defendr: Das Defendr-Team führt auf dem Defendr-Server einen privaten Kanal mit einem Eintrag
je Aktion, die Defendr auf irgendeinem Server ausgeführt hat, und je Moderations-, Melde- und Einspruchsvorgang, der über
Defendr abgewickelt wurde — Nutzer-, Server- und Kanal-IDs, einschließlich der ID des Moderators oder Teammitglieds, das
gehandelt hat, die Namen, die Discord in dem Moment dafür anzeigte (Servername, Kanalname, Anzeige- oder Nutzername des
Mitglieds und des Moderators oder Teammitglieds), die Art der Aktion oder des Vorgangs, Zählwerte und Zeiten und den
gelisteten Bedrohungswert, den ein erkannter Link oder eine erkannte Einladung getroffen hat (aus einer
Bedrohungsliste, nie was das Mitglied geschrieben hat); nie den Inhalt einer Nachricht, einer Notiz, einer Meldung oder
eines Einspruchs, nie wer wen gemeldet hat. Er existiert, damit das Team sieht, was Defendr über alle Server hinweg tut,
und Fehler schnell beheben kann (berechtigtes Interesse, Abschnitt 4). Er wird aufbewahrt, bis das Team ihn löscht.

3.10 Support-Tickets im Support-Server: Nutzer-ID, Thema, Betreff, Beschreibung und Formularfelder (verschlüsselt),
der private Thread und der Verlauf seiner Nachrichten (Text verschlüsselt; von Anhängen nur Name, Größe, Typ, Bildmaße
und die Spoiler-Markierung; wer eine Nachricht mit welchem Discord-Namen und Profilbild geschrieben hat, wann sie
geschrieben oder geändert wurde, ob in Discord oder auf der Webseite, und auf welche Nachricht sie antwortet), Antworten,
die über die Webseite gesendet wurden, wer das Ticket geschlossen oder wieder geöffnet hat, Ticket-Sperren. Was genau,
wozu und wie lange, steht in Abschnitt 11.

3.11 Direktnachrichten an Defendr: Wenn du Defendr eine Direktnachricht schickst, sieht das Defendr-Team sie (Text,
Dateinamen und Links, Zeitpunkt) in einem privaten Kanal des Support-Servers, damit es dir antworten kann; Antworten
erreichen dich als Direktnachricht von Defendr. Defendr selbst speichert nur, dass es eine Unterhaltung gibt (deine
Nutzer-ID, den Beitrag in diesem Kanal, den Zeitpunkt der letzten Nachricht und ob das Team sie stummgeschaltet hat),
nie den Text deiner Nachrichten oder der Antworten. Die Unterhaltung (Beitrag und Eintrag) wird
1825 Tage nach der letzten Nachricht gelöscht; mit /defendr › Meine Daten ›
Meine Daten löschen wird sie innerhalb einer Stunde gelöscht, /defendr › Meine Daten › Exportieren zeigt sie an.
Rechtsgrundlage: Art. 6 Abs. 1 lit. f DSGVO (Beantwortung von Anfragen an uns).

3.12 Webseite: Aufruf der Seiten, Protokolle, Anmeldung mit Discord, Profilbilder und Server-Symbole von Discord nach
der Anmeldung (auf den Seiten deiner Support-Tickets auch die Profilbilder der anderen Personen im Ticket), Sitzungen,
Anmeldeverlauf, persönliche Einstellungen und was du dort tust, etwa deine Support-Tickets lesen und beantworten.
Einzelheiten stehen in Abschnitt 11 und 12, Cookies und Speicher im Browser in Abschnitt 13.

<!-- anchor: web-risk -->

3.13 Linkprüfung mit Google Web Risk: Auf Servern, die Web Risk nutzen (in den Einstellungen „Empfohlen“ und „Streng“
von Anfang an eingeschaltet; Server, die eine dieser Einstellungen schon nutzen, bekommen es mit diesem Update
eingeschaltet; jeder Server kann es in seinen Einstellungen ausschalten), fragt Defendr bei Google Web Risk
nach einem Link aus einer Nachricht, den Defendrs eigene Listen noch nicht kennen. Auf Servern, die auch Kurzlinks
auflösen (3.14), gehört dazu das Ziel, zu dem ein Kurzlink aus der Nachricht führt. Dafür sendet Defendrs Server an
Google nur den Link ohne den Teil nach „?“ oder „#“ (Schema, Adresse und Pfad), und Google sieht die IP-Adresse
unseres Servers. Den Text der Nachricht, deine Nutzer-ID und die IDs des Servers, des Kanals oder der Nachricht sendet
Defendr nie. Google antwortet, ob der Link auf seiner Liste gefährlicher Webseiten steht (Phishing, Schadsoftware,
unerwünschte Software). Steht er dort, behandelt Defendr den Link wie jeden anderen gefährlichen Link, und die
Einstellungen des Servers entscheiden, was geschieht (zum Beispiel wird die Nachricht gelöscht); wie bei jedem anderen
gefährlichen Link nennt der Eintrag dazu, was Defendr getan hat, den Link ohne den Teil nach „?“ oder „#“, unklickbar
gemacht (beim Ziel eines Kurzlinks nur die Namen der beiden Webseiten, ebenfalls unklickbar gemacht). Der Hinweis „Advisory provided by Google“ zeigt, woher die Warnung kommt. Defendr speichert die Antwort unter
einem Hashwert des Links, nie den Link selbst: einen Treffer so lange, wie Google angibt, höchstens 24 Stunden, eine
Antwort ohne Treffer 1 Stunde. Für die Tagesgrenze zählt Defendr die Abfragen pro Server und insgesamt für den
laufenden Tag und, nur im Arbeitsspeicher, die Abfragen pro Webseiten-Adresse unter einem Hashwert. Google Cloud EMEA
Limited arbeitet dabei als unser Auftragsverarbeiter (Art. 28 DSGVO) und verwendet die Links nur, um die Anfrage zu
beantworten (Abschnitt 5 und 6).

<!-- anchor: shortener-unfurl -->

3.14 Auflösen von Kurzlinks: Auf Servern, die das eingeschaltet haben (in der Einstellung „Streng“ von Anfang an
eingeschaltet), stellt Defendr fest, wohin ein Kurzlink dieser Dienste führt: bit.ly, cutt.ly, rebrand.ly, ow.ly, rb.gy, buff.ly, lnkd.in, t.co, goo.gl, forms.gle, we.tl, qrco.de. Defendrs Server
fragt den Kurzlink-Dienst nach dem Ziel (zuerst mit einer HEAD-Anfrage, wenn nötig danach mit einer GET-Anfrage) und
folgt höchstens fünf Weiterleitungen innerhalb dieser Dienste; das Ziel selbst ruft er nie auf. Der Dienst erhält den
Kurzlink, wie er gepostet wurde, die IP-Adresse unseres Servers und den Programmnamen „DefendrBot/2“ mit der
Adresse unserer Webseite; keine Cookies und keine Nutzer-, Server-, Kanal- oder Nachrichten-IDs. Der Dienst kann die
Anfrage wie einen Klick zählen. Defendr prüft das Ziel gegen seine Listen und, auf Servern, die Web Risk nutzen, mit Google Web Risk
(3.13); ein bekanntes gefährliches Ziel wird wie der
gefährliche Link selbst behandelt, und warnt der Kurzlink-Dienst selbst vor dem Link (wie X), behandelt Defendr ihn für
diese Nachricht genauso. Damit jeder Server das Ziel mit seinen eigenen Listen prüfen kann, behält Defendr das Ergebnis
mit dem Ziel bis zu einer Stunde im Arbeitsspeicher, oder 10 Minuten, wenn der Dienst in dem Moment nicht antworten
konnte oder mit einem Fehler antwortete; in seiner Datenbank speichert es für dieselbe Zeit nur einen Hashwert des
Kurzlinks und, wenn der Dienst gewarnt hat, einen Hashwert des Hostnamens des Ziels. Zum Schutz der Dienste zählt
Defendr die Anfragen des laufenden Tages insgesamt und, nur im Arbeitsspeicher, die aufgelösten Kurzlinks pro Server
für den laufenden Tag sowie pro Verfasser und pro Nachricht für etwa zehn Minuten. Jeder Dienst
verarbeitet die Anfrage als eigener Verantwortlicher nach seiner eigenen Datenschutzerklärung (Abschnitt 5 und 6).

<!-- anchor: network-signals -->

3.15 Anonyme Netzwerk-Signale: Stoppt Defendr ein übernommenes Konto, das in kurzer Zeit denselben Betrug postet, oder
schreibt jemand in den Fallenkanal eines Servers, notiert Defendr ein anonymes Signal, außer der Server hat das in
seinen Einstellungen ausgeschaltet (von Anfang an eingeschaltet). Das Signal enthält nur Hashwerte, die mit einem
geheimen Schlüssel gebildet werden, der Defendrs Server nie verlässt: einen eines Fingerabdrucks der Nachricht (nicht
des Textes), je einen jeder Webseiten-Adresse aus der Nachricht, die auf keiner Freigabeliste steht (höchstens fünf),
und einen des Servers mit
einem Schlüssel, der jeden Monat wechselt. Es enthält keine Nutzer-ID, keine Nachrichten-ID, keine Server-ID, keinen
Text und keine Webseiten-Adresse im Klartext und wird nach 48 Stunden gelöscht. Kommt
dieselbe Webseiten-Adresse innerhalb von sechs Stunden von mindestens drei Servern, prüft eine Person bei Defendr sie;
bis dahin markiert sie nur passende Links für diese Prüfung und löst in keinem Server eine Maßnahme aus. Ein Signal
handelt nie von selbst. Nichts vom Signal selbst verlässt Defendrs Server.

<!-- anchor: report-capture -->

3.16 Meldungen an das Defendr-Team: Meldest du eine Nachricht über „Report“ im Menü der Nachricht (Apps › Report) an
das Defendr-Team, speichert Defendr eine Kopie der Nachricht, so wie du sie in diesem Moment siehst. So kann das Team
die Meldung sicher prüfen und entscheiden, auch wenn die Nachricht später bearbeitet oder gelöscht wird oder in einer
Direktnachricht steht. Discord übermittelt die Nachricht dafür beim Klick auf „Report“ an Defendr; Defendr liest nichts
nach. Die Kopie enthält den Text (bis 4.000 Zeichen), die Links darin (bei Links hinter einem anderen Text auch diesen
Text), die Liste der Anhänge (Name, Typ, Größe, Bildmaße und Spoiler-Markierung, nicht die Dateien selbst), den
sichtbaren Text von Einbettungen und Link-Vorschauen, bei einer weitergeleiteten Nachricht deren Inhalt, die Namen von
Stickern, den Text einer Umfrage, die Zahl der Erwähnungen (und ob alle erwähnt wurden), den Nutzer- und Anzeigenamen der Person, die die Nachricht
geschrieben hat, zu diesem Zeitpunkt und ob es ein Bot oder Webhook war, die Zeitpunkte der Nachricht und die IDs der
Nachricht, des Kanals, des Servers und der Person. Bis du das Meldeformular abschickst, liegt die Kopie versiegelt
bereit und ist höchstens 15 Minuten verwendbar. Brichst du ab oder schickst du die Meldung stattdessen an die
Moderatoren des Servers, wird sie nicht verwendet und spätestens nach einer halben Stunde gelöscht. Melden mehrere Personen dieselbe Nachricht, wird sie
einmal gespeichert; wurde sie inzwischen bearbeitet, zusätzlich die neue Fassung (höchstens fünf Fassungen je Meldung).
Bei Meldungen an die Moderatoren eines Servers speichert Defendr keine Kopie.

Bilder, die du einer Meldung an das Defendr-Team anhängst (PNG, JPEG, GIF oder WebP, bis zu drei, je bis 8 MB),
speichert Defendr nicht im Original, sondern als neu erzeugte Kopie im Format WebP: höchstens 1600 Pixel an der
längsten Seite, bei bewegten Bildern nur das erste Bild, ohne Metadaten wie Kamera, Aufnahmeort oder Aufnahmezeit. Dazu
speichert Defendr Typ, Größe und eine Prüfsumme der Kopie, den Zeitpunkt und dass das Bild von dir kommt. Das Original
verarbeitet Defendr nur kurz im Arbeitsspeicher und holt es nur bei Discord ab, wo du es hochgeladen hast. Andere
Dateien (etwa PDFs oder Videos) werden nicht gespeichert, nur ihr Typ und ihre Größe. Ebenso wenig gespeichert wird ein
Bild, das zu groß ist, das einem bekannten Bild mit sensiblem Inhalt entspricht oder das ankommt, während die
Bildverarbeitung voll ausgelastet ist.

Kopie und Bilder sind verschlüsselt gespeichert, jedes Bild mit einem eigenen Schlüssel. Sehen können sie nur
Mitglieder des Defendr-Teams, die Meldungen prüfen, in Discord und auf der Webseite; jede Ansicht wird festgehalten.
Server-Moderatoren, andere Melder und die Öffentlichkeit sehen sie nicht, und Defendr gibt sie an niemanden weiter. Sie
dienen nur der Prüfung der Meldung und dem Nachweis der Entscheidung, nicht für automatische Entscheidungen,
Erkennungsregeln oder Profile. Defendr löscht sie 90 Tage nach der
Entscheidung über die Meldung oder schon 180 Tage nach der Meldung, wenn
dieser Tag früher kommt. Eine offene Meldung, auch eine, die das Team schon prüft, schließt Defendr nach
90 Tagen. Die Löschung erledigt eine tägliche Aufgabe, höchstens einen Tag nach diesem
Tag. Länger bleiben sie nur, solange wir
sie wegen einer rechtlichen Pflicht oder für Rechtsansprüche aufbewahren müssen (etwa für die Anfrage einer Behörde),
oder solange die Verarbeitung auf Verlangen eingeschränkt ist; in diesem Fall werden sie nicht mehr angezeigt.

Deine Rechte dazu: Hast du die gemeldete Nachricht geschrieben, steht sie in deinem Export (/defendr › Meine Daten ›
Exportieren), mit ihrem Inhalt und ihren Zeitpunkten, aber ohne Angaben zur Meldung (etwa wann oder wo gemeldet wurde),
damit niemand, der meldet, dadurch erkennbar wird. Verlangst du die Löschung, prüft das Defendr-Team den Antrag. Ist er
bewilligt, wird die Kopie innerhalb eines Tages gelöscht, wenn über die Meldung schon entschieden ist, sonst innerhalb
eines Tages nach der Entscheidung. Hast du gemeldet, nennt dein
Export deine Meldungen und zu jedem angehängten Bild, ob es gespeichert wurde, mit Typ, Größe und Zeitpunkt; eine Kopie
deiner gespeicherten Bilder schicken wir dir auf Anfrage an privacy@defendr.live. Verlangst du die Löschung deiner
Daten, löscht Defendr deine Bilder sofort: Sie lassen sich nicht mehr öffnen, und ihre gespeicherten Dateien
sind innerhalb von zwei Tagen entfernt. Die Kopie der gemeldeten Nachricht bleibt bis zu ihrer Frist, denn sie
gehört zu den Daten der Person, die sie geschrieben hat. Rechtsgrundlage: Art. 6 Abs. 1 lit. f DSGVO (Abschnitt 4).

<!-- anchor: word-filter -->

3.17 Wortfilter: Auf Servern, die den Wortfilter eingeschaltet haben (für neue Server mit der Einstellung „Streng“ von
Anfang an eingeschaltet; jeder Server kann ihn ein- und ausschalten), legt Defendr im Server eigene AutoMod-Regeln von
Discord an („Defendr · …“). Sie enthalten Wörter aus den Bereichen, die der Server gewählt hat (Hassrede, sexuelle
Inhalte, Schimpfwörter), und die eigenen Wörter des Servers; ist Englisch eine der Sprachen des Filters, nutzt eine
weitere Regel Discords eigene Wortlisten für diese Bereiche. Die Prüfung selbst übernimmt Discord: Discord vergleicht
jede gesendete oder bearbeitete Nachricht mit diesen Regeln und hält eine passende Nachricht zurück, bevor jemand sie
sieht. Discord verarbeitet die Nachricht dabei als Anbieter von AutoMod nach seiner eigenen Datenschutzerklärung.

Zu jeder zurückgehaltenen Nachricht schickt Discord Defendr eine Meldung mit der Server-, Kanal- und Nutzer-ID, der
Regel, dem passenden Wort der Regel und dem Text der Nachricht. Den von Discord markierten passenden Teil verwirft
Defendr sofort. Den Text nutzt Defendr im Arbeitsspeicher, um eine Nachricht, die mehrere Regeln trifft, nur einmal zu
zählen (als Hashwert, drei Sekunden lang). Gespeichert wird er nur, wenn der Server Auszüge eingeschaltet hat (3.1): dann
als gekürzter, entschärfter Auszug von höchstens 300 Zeichen im Moderationsfall. Zu jeder zurückgehaltenen Nachricht
legt Defendr einen Moderationsfall an (Nutzer-ID, Kanal, Grund-Code, Bereich, Wortliste und Sprache; bei einem Wort, das nur auf Discords
eigener Wortliste steht, statt des Bereichs „ein Wort auf Discords eigener Liste“; das Wort der Regel
nur entschärft und nur mit eingeschalteten Auszügen), gegen den das Mitglied Einspruch einlegen kann (/appeal). Hält
Discord von derselben Person innerhalb von zehn Minuten drei Nachrichten zurück, schaltet Defendr sie für zehn Minuten
stumm (Timeout), außer der Server hat das ausgeschaltet; dafür zählt Defendr die gespeicherten Fälle und merkt sich nur
im Arbeitsspeicher und höchstens zehn Minuten, wann es zuletzt so gehandelt hat. Die Fälle werden wie alle
Moderationsfälle gelöscht (Abschnitt 7).

Für seine Regeln speichert Defendr je Server nur ihre Kennung, ihren Zustand und Prüfwerte, keine Nutzerdaten. Die
Einstellungen des Filters, auch die eigenen Wörter des Servers, gehören zur Server-Konfiguration und werden mit ihr
gelöscht. Die Daten des Wortfilters dienen nur ihm: nicht für Netzwerk-Einträge oder Signale, und Defendr gibt nichts
davon weiter außer an AutoMod von Discord und an den Server selbst.

## 4. Zwecke und Rechtsgrundlagen

<!-- anchor: purposes -->

- Schutz von Discord-Communities vor Betrug, Schadsoftware und Missbrauch: Art. 6 Abs. 1 lit. f DSGVO.
- Bearbeitung von Einsprüchen und Betroffenenanfragen: Art. 6 Abs. 1 lit. c und f DSGVO.
- Netzwerkweite Sicherheitseinträge: Art. 6 Abs. 1 lit. f DSGVO; Interessenabwägung verfügbar auf Anfrage.
- Verstehen, wie Server Defendr finden (die freiwillige Setup-Antwort „Wo hast du Defendr gefunden?", pro Server
  gespeichert und keiner Person zugeordnet): Art. 6 Abs. 1 lit. f DSGVO; die Antwort ist freiwillig und kann
  ausgelassen werden.
- Übersicht über die Aktionen von Defendr und über die darüber abgewickelten Moderations-, Melde- und
  Einspruchsvorgänge (Abschnitt 3.9): Art. 6 Abs. 1 lit. f DSGVO.
- Bearbeitung von Support-Tickets im Support-Server, mit dem gespeicherten Verlauf und den Antworten über die Webseite
  (Abschnitt 11): Art. 6 Abs. 1 lit. b DSGVO, soweit du Defendr nach den Nutzungsbedingungen nutzt, sonst und für die
  Nachrichten anderer Personen im Thread Art. 6 Abs. 1 lit. f DSGVO. Unser berechtigtes Interesse ist, Anfragen
  vollständig und nachvollziehbar zu beantworten, in Discord und auf der Webseite.
- Beantwortung von Direktnachrichten an Defendr (Abschnitt 3.11): Art. 6 Abs. 1 lit. f DSGVO.
- Bereitstellung und Absicherung der Webseite und der Statusseite, Protokolle zur Fehlersuche und Angriffsabwehr
  (Abschnitt 12.1, 12.2 und 12.7): Art. 6 Abs. 1 lit. f DSGVO. Unser berechtigtes Interesse ist eine sichere,
  erreichbare und fehlerfreie Webseite.
- Anmeldung mit Discord, persönlicher Bereich, Server-Verwaltung und deine persönlichen Einstellungen
  (Abschnitt 12.3, 12.5 und 12.6): Art. 6 Abs. 1 lit. b DSGVO; du nutzt diese Funktionen auf deinen Wunsch nach den
  Nutzungsbedingungen.
- Dein Profilbild und die Symbole deiner Server von Discord auf den Seiten nach der Anmeldung, auf den Seiten deiner
  Support-Tickets auch die Profilbilder der anderen Personen, die im Ticket geschrieben haben (Abschnitt 12.9): Art. 6
  Abs. 1 lit. f DSGVO. Unser berechtigtes Interesse ist, dir dein Konto, deine Server und die Personen im Ticket mit
  den Bildern zu zeigen, die du aus Discord kennst, damit du sie auf einen Blick wiedererkennst.
- Anmeldeverlauf deines Kontos (Abschnitt 12.4): Art. 6 Abs. 1 lit. f DSGVO. Unser berechtigtes Interesse ist, dass
  du und wir Anmeldungen und Abmeldungen deines Kontos nachvollziehen und fremde Anmeldungen erkennen können.
- Protokoll der Aktionen auf der Webseite (Abschnitt 12.6): Art. 6 Abs. 1 lit. f DSGVO. Unser berechtigtes Interesse
  ist, nachweisen zu können, wer über die Webseite was ausgelöst oder geändert hat (Rechenschaftspflicht, Art. 5
  Abs. 2 DSGVO).
- Beantwortung von E-Mails und Bearbeitung von Meldungen zu Sicherheitslücken (Abschnitt 12.8): Art. 6 Abs. 1 lit. f
  DSGVO; bei Anfragen zu deinen Rechten Art. 6 Abs. 1 lit. c DSGVO.
- Öffentlicher Dank für eine gemeldete Sicherheitslücke mit deinem Namen oder Pseudonym (Abschnitt 12.8): Art. 6
  Abs. 1 lit. a DSGVO (deine Einwilligung, jederzeit widerruflich).
- Linkprüfung mit Google Web Risk, Auflösen von Kurzlinks und anonyme Netzwerk-Signale (Abschnitt 3.13 bis 3.15):
  Art. 6 Abs. 1 lit. f DSGVO. Unser berechtigtes Interesse und das der Server ist, Phishing- und Schadsoftware-Links
  schnell zu erkennen, auch neue und solche hinter einem Kurzlink, und eine Betrugswelle zu bemerken, die mehrere
  Server zugleich trifft.
- Kopie gemeldeter Nachrichten und Bilder bei Meldungen an das Defendr-Team (Abschnitt 3.16): Art. 6 Abs. 1 lit. f
  DSGVO. Unser berechtigtes Interesse und das der Nutzer der Server ist, Meldungen über Betrug, Phishing und
  Schadsoftware zuverlässig zu prüfen, auch wenn die Nachricht inzwischen bearbeitet oder gelöscht wurde, und jede
  Entscheidung belegen zu können.
- Wortfilter (Abschnitt 3.17): Art. 6 Abs. 1 lit. f DSGVO. Unser berechtigtes Interesse und das des Servers ist,
  Hassrede, sexuelle Inhalte und Schimpfwörter nach den Regeln des Servers zurückzuhalten und jede Maßnahme
  überprüfbar zu machen.

## 5. Empfänger

<!-- anchor: processors -->

Discord Inc. (Plattform; auf den Seiten der Webseite nach der Anmeldung auch beim Laden von Profilbildern und
Server-Symbolen, Abschnitt 12.9; bei einer Antwort über die Webseite erhält Discord den Text mit deinem Namen und der
Adresse deines Profilbilds, Abschnitt 11.5), Moderatoren des jeweiligen Servers (nur eigene Serverdaten), ZAP-Hosting GmbH, Hafenweg 8, 48155 Münster (DE, gemieteter Server im Rechenzentrum Frankfurt am Main, auf dem Defendr und die Webseite laufen und die Datenbank liegt (Abschnitt 12.1)); Cloudflare, Inc. (US, Auslieferung und Schutz der Webseite (Netzwerk, verschlüsselter Tunnel zu unserem Server, Angriffsabwehr, Analyse- und Sicherheitsprotokolle), Betrieb der Statusseite und Weiterleitung von E-Mails an die Adressen @defendr.live (Abschnitt 12)); Google Ireland Limited (Gmail) (EU/US, Postfach, in dem E-Mails an unsere Adressen ankommen; Google verarbeitet sie nach eigenen Bedingungen als eigener Verantwortlicher, nicht als unser Auftragsverarbeiter (Abschnitt 12.8)); Google Cloud EMEA Limited, Dublin (Google Web Risk) (EU/US, Prüfung unbekannter Links gegen die Liste gefährlicher Webseiten von Google, für die Server, die Web Risk nutzen; Google arbeitet dabei als unser Auftragsverarbeiter (Abschnitt 3.13)).

Empfänger der Übersicht über die Aktionen von Defendr (Abschnitt 3.9) sind der Betreiber und das Support-Team von
Defendr; sie enthält keine Nachrichteninhalte.

Auf den Servern, die Kurzlinks auflösen, erhält der Betreiber des Kurzlink-Dienstes den Kurzlink und die IP-Adresse
unseres Servers (Abschnitt 3.14): Bitly (bit.ly), Cutt.ly (cutt.ly), Rebrandly (rebrand.ly, rb.gy), Hootsuite
(ow.ly), Buffer (buff.ly), LinkedIn (lnkd.in), X (t.co), Google (goo.gl, forms.gle), WeTransfer (we.tl) und QR Code
Generator (qrco.de). Jeder von ihnen verarbeitet die Anfrage als eigener Verantwortlicher.

Als Auftragsverarbeiter (Art. 28 DSGVO) arbeiten Cloudflare und Google Cloud EMEA Limited nur nach unserer Weisung und
auf Grundlage ihrer Bedingungen zur Auftragsverarbeitung.

## 6. Übermittlung in Drittländer

Discord (USA) – die Nutzung von Discord unterliegt Discords eigener Datenschutzerklärung. Discord Inc. verarbeitet Daten auch in den USA. Rufst du die Webseite auf, verarbeitet Cloudflare, Inc. (USA) die Daten des Aufrufs (Abschnitt 12) in ihrem weltweiten Netzwerk, auch in den USA. Schreibst du uns eine E-Mail, werden deine Nachricht und deine E-Mail-Adresse über Cloudflare, Inc. weitergeleitet und in unserem Postfach bei Gmail gespeichert; Google speichert und verarbeitet sie auch in den USA (Google LLC). Beide Unternehmen sind nach dem EU-US Data Privacy Framework zertifiziert (Angemessenheitsbeschluss, Art. 45 DSGVO); für Cloudflare gelten ergänzend die Standardvertragsklauseln im Auftragsverarbeitungsvertrag (Art. 46 Abs. 2 lit. c DSGVO). Für die Linkprüfung mit Google Web Risk (Abschnitt 3.13) setzt unser Auftragsverarbeiter Google Cloud EMEA Limited auch Google LLC (USA) ein; Google LLC ist nach dem EU-US Data Privacy Framework zertifiziert, und die Bedingungen von Google Cloud zur Auftragsverarbeitung enthalten ergänzend die Standardvertragsklauseln (Art. 46 Abs. 2 lit. c DSGVO). Löst Defendr einen Kurzlink auf (Abschnitt 3.14), erhält der Betreiber des Kurzlink-Dienstes die Anfrage. Für die Betreiber in den USA (Bitly, Inc.; Buffer, Inc.; LinkedIn Corporation; X Corp.; Google LLC) stützt sich die Übermittlung auf ihre Zertifizierung nach dem EU-US Data Privacy Framework, für Hootsuite Inc. (Kanada) auf den Angemessenheitsbeschluss für Kanada (jeweils Art. 45 DSGVO). Weitere Übermittlungen in Drittländer finden nicht statt.

## 7. Speicherdauer

<!-- anchor: retention -->

| Datenkategorie | Speicherdauer |
| --- | --- |
| Vorübergehende persönliche Web-Exportkopien und Status des einmaligen Downloads | Zugriff höchstens 15 Minuten; Schlüssel bei Abschluss oder Widerruf sofort entfernt; verschlüsselte Kopien anschließend in begrenzten Bereinigungsschritten gelöscht |
| Zugriffsprotokolle der Webseite (Zeit, Pfadvorlage, Status, Dauer, zufällige Anfrage-ID; ohne Adressen oder Inhalte) | 14 Tage, früher, wenn der Speicherplatz für die Protokolle voll ist; die Protokolle eines angehaltenen Webservers löscht eine tägliche Aufgabe, bis zu einen Tag später |
| Ereignisprotokoll der Webseite (Serverfehler nach Seite und Fehlerart, fehlende Texte, Ausfälle und Ablehnungen zwischen Webseite und Defendr, fehlgeschlagene Anmeldungen nach Grund, Zahl der verworfenen Einträge und der vorzeitig gelöschten Dateien des Zugriffsprotokolls mit der Minute, ab der ihre Einträge beginnen; keine Person, Adresse, URL, Cookies, Inhalte oder Sitzung) | 14 Tage, früher über 4 MiB (die ältesten zuerst); das Protokoll eines angehaltenen Webservers löscht eine tägliche Aufgabe, bis zu einen Tag später |
| Tunnel-Protokoll auf unserem Server (cloudflared): nur Fehler, die den Verbinder selbst beenden (Protokollstufe fatal), und Warnungen zu seiner eigenen Verbindung zu Cloudflare (Transport-Protokollstufe warn); keine Anfragen, aufgerufenen Adressen oder IP-Adressen von Besuchern | 14 Tage, gelöscht durch eine tägliche Aufgabe, spätestens einen Tag später |
| E-Mails an die Adressen @defendr.live (contact@, privacy@, security@, auch Meldungen zu Sicherheitslücken; Postfach bei Gmail) | sobald für die Anfrage nicht mehr gebraucht, spätestens drei Jahre nach Abschluss der Anfrage, außer eine gesetzliche Pflicht verlangt länger |
| Web-Sitzungen und verschlüsselte Discord-Zugangstoken | 7 Tage ohne Aktivität; höchstens 30 Tage |
| Sicherheitsereignisse der Webseite (Anmeldung, Abmeldung, Abmeldung überall, Beenden einer einzelnen anderen Sitzung, eine von Defendr rückgängig gemachte Anmeldung, die Discord schon bestätigt hatte, das Ende aller Sitzungen, wenn ein Zugangsrecht zu einem geschützten Bereich endet; Gerätekategorie und Zeitpunkt; ohne Adressen) | 365 Tage |
| Belege für Aktionen auf der Webseite (Aktion, Status, Ergebniscode, Zeitpunkte; die Anfrage und ihr Schlüssel gegen doppelte Ausführung nur als Hashes) | 365 Tage nach dem Abschluss der Aktion |
| Einstellungen der Webseite und des Kontos (Sprache, ob Nachrichten von Defendr ihr folgen, Lesemarke des Postfachs, ob der Hinweis zu Ticket-Antworten gesehen wurde, Farbschema, Akzent, Dichte, Bewegung) | bis zur Löschung der Kontodaten (ohne feste Frist); auf Wunsch entfernt |
| Verlauf des Sicherheitswerts je Server (wöchentlicher Wert und Teilwerte, keine Nutzer-IDs) | unbegrenzt (Kennzahlen); mit den Serverdaten, nachdem Defendr den Server verlassen hat |
| Nachrichteninhalte während der Prüfung | Sekunden (nur im Arbeitsspeicher) |
| Erkennungen (IDs, Typ, Maßnahme und der erkannte Link oder die erkannte Adresse, unklickbar gemacht; kein Nachrichtentext) | 1825 Tage |
| Moderationsfälle (samt Ereignissen) | 1825 Tage (von Defendr festgelegt, in jedem Server gleich) |
| Nachrichtenauszüge (pro Server ausdrücklich eingeschaltet) | höchstens 1095 Tage, nie länger als der Fall |
| Hochgeladene Nachweise (vom Team zu Sicherheitseinträgen und Fällen hinterlegt) | 1095 Tage; Nachweise zu Sicherheitseinträgen mit dem Eintrag; eine rechtliche Aufbewahrungspflicht setzt die Löschung aus; was ein Mitglied mitschickt, wird nur als neu erzeugte Bildkopie für das Defendr-Team gespeichert (nächste Zeile) |
| Meldungen an das Defendr-Team: die versiegelte Kopie der gemeldeten Nachricht (Text, Links, Liste der Anhänge, Text von Einbettungen, Namen der Person, die sie geschrieben hat, zu diesem Zeitpunkt) und neu erzeugte Kopien der Bilder, die der Melder angehängt hat (WebP ohne Metadaten) | 90 Tage nach der Entscheidung oder 180 Tage nach der Meldung, wenn das früher ist; gelöscht durch eine tägliche Aufgabe, spätestens einen Tag später; eine rechtliche Aufbewahrungspflicht setzt die Löschung aus |
| Meldungen und Mitmeldende | angenommen: 1825 Tage nach der Entscheidung; abgelehnt/Spam: 365 Tage; offen (auch während der Prüfung): automatisch geschlossen nach 90 Tagen |
| Verlässlichkeit meldender Personen | 1825 Tage nach der letzten Meldung |
| Fehlalarm-Signale (Moderator-ID, Fall) | 1095 Tage |
| Prüfstimmen und Team-Threads | mit dem geprüften Eintrag |
| Einsprüche (samt Empfehlungen) | 1825 Tage nach der Entscheidung oder dem Fristablauf |
| Support-Tickets (Formulartext und Thread-Nachrichten verschlüsselt; der private Thread im Support-Server) und Ticket-Sperren | 1825 Tage nach dem Schließen (Eintrag, Thread und gespeicherte Nachrichten, auch wenn der Thread vorher von Hand gelöscht wurde); ein Ticket-Thread, der ohne seinen Eintrag zurückbleibt (nach einer fehlgeschlagenen Erstellung oder einer Wiederherstellung aus einer Sicherung), wird 1825 Tage nach seiner Erstellung gelöscht (bis dahin ggf. gesperrt und archiviert) – weil kein Eintrag ihn mit einem Mitglied verknüpft, löscht das Team ihn auf einen Löschantrag hin von Hand; Ticket-Sperren bis zur Aufhebung |
| Unterhaltungen per Direktnachricht mit Defendr (Nutzer-ID, der Beitrag im Team-Kanal, Zeitpunkt der letzten Nachricht, stummgeschaltet ja/nein; nie der Text) | 1825 Tage nach der letzten Nachricht; innerhalb einer Stunde nach einer Löschung |
| Betroffenenanfragen; Verarbeitungseinschränkungen | 1825 Tage (Rechenschaftspflicht; Inhalte minimiert und verschlüsselt); Einschränkungen 1825 Tage nach der Aufhebung |
| Aktiver netzwerkweiter Sicherheitseintrag | kein automatischer Ablauf; Erinnerung zur erneuten Prüfung nach 12 Monaten (eine Statusänderung erfordert immer eine Entscheidung des Teams) |
| Importierte Einträge, die auf ihre Prüfung warten | bis zur Prüfung; Erinnerung nach 6 Monaten |
| Abgeschlossene Sicherheitseinträge (aufgehoben/abgelehnt/abgelaufen) | 1095 Tage |
| Mitglieds-Markierungen: übernommenes Konto / Raid-Gruppe / Hinweis angezeigt | 72 Stunden / 7 Tage / 30 Tage |
| Mitglieds-Markierung: Verifizierung ausstehend | mindestens 24 Stunden, so lange wie die Kick-Frist des Servers + 1 Stunde |
| Mitglieds-Markierungen: Quarantäne-Rolle der Zugangsregeln / von Defendr vergebene Verdachtsrolle | solange die Rolle besteht; 30 Tage nach dem Verlassen |
| Raid-Gruppen (nur Metadaten) | 365 Tage |
| Vorfälle | 1825 Tage |
| Anti-Nuke: entzogene Rollen / Strukturabbilder / gelöschte Objekte (2.1) | 30 / 7 / 14 Tage |
| Einträge zu Server-Sperren | 1095 Tage nach dem Ende |
| Verifizierungs-Aufgaben | 24 Stunden |
| Zustand interaktiver Ansichten (verschlüsselt) | höchstens 24 Stunden |
| Ausstehende Nachrichten (Postausgang) | Inhalt wird beim Versand oder beim Aufgeben gelöscht; Zeilen 7 Tage (gesendet) / 30 Tage (fehlgeschlagen) |
| Einstellungs-Versionen; Entscheidungen zu Voreinstellungs- und Migrationskarten | letzte 100, höchstens 1 Jahr; Entscheidungen 90 Tage |
| Aktionsprotokoll: Zugriffe des Teams auf Einträge und Nachweise und jede Aktion auf der Webseite (Nutzer-ID, Aktion, Server, Zeitpunkt, Ergebnis, Beleg- und Anfrage-ID) | 1825 Tage; bleibt bei einer Löschung bestehen (Rechenschaftspflicht) |
| Team-Mitgliedschaft | 1825 Tage nach der Deaktivierung |
| Anonyme Netzwerk-Signale (nur Hashwerte mit geheimem Schlüssel; keine Nutzer-, Nachrichten- oder Server-ID, kein Text) | 48 Stunden |
| Ergebnisse der Linkprüfung (Web Risk und Kurzlinks): ein Hashwert des geprüften Links, die Antwort und bei einem Kurzlink ein Hashwert des Hostnamens des Ziels; kein Link, keine Nutzer-, Nachrichten- oder Server-ID | höchstens 24 Stunden; eine Antwort von Web Risk ohne Treffer und ein Kurzlink höchstens 1 Stunde; ein Kurzlink, auf den der Dienst in dem Moment nicht antworten konnte oder mit einem Fehler antwortete, 10 Minuten |
| Tageszähler der Linkprüfung (Web-Risk-Abfragen pro Server und insgesamt, Kurzlink-Anfragen insgesamt) | bis der Zähler des nächsten Tages ihn ersetzt |
| Anwendungsprotokolle (ohne Nachrichteninhalte) | 90 Tage |
| Übersicht über die Aktionen von Defendr (Abschnitt 3.9): IDs, Aktions- und Vorgangsarten, Zählwerte und Zeiten der Aktionen von Defendr und der darüber abgewickelten Moderations-, Melde- und Einspruchsvorgänge (einschließlich Moderator- und Team-IDs), die Namen, die Discord in dem Moment für den Server, den Kanal, das Mitglied und den Moderator oder das Teammitglied anzeigte, und der gelistete Bedrohungswert, den ein erkannter Link oder eine erkannte Einladung getroffen hat; nie Nachrichteninhalte | bis der Betreiber sie löscht |
| Fehlerereignisse (bereinigt) | 365 Tage |
| Statistik-Kennzahlen (ohne Nutzer-IDs): Zählwerte pro Tag, Server und Kennzahl, auch je Begründungscode und je Erkennungsfamilie | unbegrenzt |
| Setup-Antwort „Wo hast du Defendr gefunden?" (pro Server, freiwillig; keiner Person zugeordnet) | mit der Server-Konfiguration: 90 Tage nachdem Defendr den Server verlassen hat (oder sofort, wenn so eingestellt) |
| Alle Serverdaten, nachdem Defendr den Server verlassen hat | 90 Tage (oder sofort, wenn so eingestellt); durch erneute Einladung aufgehoben |
| Lokale Sicherungen | 14 täglich / 8 wöchentlich / 6 monatlich |
| Verlaufsakten aus Defendr 1 (Freitext) | nicht übernommen; gelöscht 30 Tage nach der Abschaltung von Defendr 1, das verschlüsselte Archiv nach 90 Tagen |

Löschungen innerhalb von Sicherungen erfolgen durch deren Rotation; die maximale Aufbewahrung der Sicherungen steht in
der Tabelle.

## 8. Deine Rechte

<!-- anchor: rights -->

Du hast das Recht auf Auskunft (Art. 15 DSGVO), Berichtigung (Art. 16), Löschung (Art. 17), Einschränkung der
Verarbeitung (Art. 18), Datenübertragbarkeit (Art. 20) und Widerspruch (Art. 21). In Discord nutzt du sie auf der Seite
Meine Daten von /defendr (Exportieren, Meine Daten löschen, Widersprechen, Berichtigen, Einschränken; direkt: /defendr
page:mydata), auf der Webseite im persönlichen Bereich unter „Mein Defendr“ mit denselben Funktionen, oder per E-Mail an
privacy@defendr.live. Der Export ist maschinenlesbar. Entscheidungen kannst du überprüfen lassen (/appeal, auf der
Webseite unter „Mein Defendr“). Du kannst dich außerdem bei einer Aufsichtsbehörde beschweren (Der Landesbeauftragte für den Datenschutz Niedersachsen,
Prinzenstraße 5, 30159 Hannover, Deutschland).

**Widerspruchsrecht (Art. 21 DSGVO):** Soweit wir deine Daten aufgrund berechtigter Interessen verarbeiten (Art. 6
Abs. 1 lit. f DSGVO), kannst du aus Gründen, die sich aus deiner besonderen Situation ergeben, jederzeit widersprechen.
Wir verarbeiten die Daten dann nicht mehr, es sei denn, wir können zwingende schutzwürdige Gründe nachweisen, die deine
Interessen, Rechte und Freiheiten überwiegen, oder die Verarbeitung dient der Geltendmachung, Ausübung oder
Verteidigung von Rechtsansprüchen. Den Widerspruch erklärst du mit /defendr › Meine Daten › Widersprechen, im
persönlichen Bereich der Webseite oder per E-Mail an privacy@defendr.live.

Support-Tickets (Abschnitt 11) sind samt ihrem Verlauf Teil des Exports und werden mit einer Löschung gelöscht; eine
Ticket-Sperre bleibt bestehen (Abschnitt 11.7). Was für die Kopie einer gemeldeten Nachricht und für Bilder in Meldungen
an das Defendr-Team gilt, steht in Abschnitt 3.16. Eine Löschung deiner Daten beendet auch alle deine Sitzungen auf der Webseite.

## 9. Automatisierte Entscheidungen

Server-Betreiber legen fest, wie Defendr auf erkannte Bedrohungen reagiert. Defendr begrenzt
Maßnahmen nach der Verlässlichkeit des Nachweises (z. B. nie Bann allein aufgrund externer Listen).

Netzwerkweite Einträge lösen nie eine automatische Maßnahme aus: Einträge aus externen
Listen und auch alle anderen Netzwerk-Einträge zeigen Moderatoren nur eine Warnung, und die Moderatoren entscheiden
selbst, ob sie etwas unternehmen. Jede Entscheidung kann mit /appeal überprüft
werden: Über Fälle eines Servers entscheiden dessen Moderatoren, über netzwerkweite Einträge das Defendr-Team.

Direktnachrichten schickt Defendr nur, wenn eine Maßnahme dich betrifft, wenn du selbst einen
Vorgang gestartet hast (Einspruch, Meldung, Betroffenenanfrage), wenn du Defendr geschrieben hast und das Defendr-Team
dir antwortet, oder – wenn dir ein Server gehört – einmal pro Vorfall, wenn Defendr einen Anti-Nuke-Alarm nicht in
deinem Server zeigen kann (wer wann was getan hat, und ein Knopf zum Wiederherstellen gelöschter Kanäle und Rollen) –
nie als Werbung oder Begrüßung.

Wird ein Netzwerk-Eintrag über dich aktiv, schickt dir Defendr eine Direktnachricht, aber nur, wenn du einen Server mit
Defendr teilst, und zwar in der Defendr-Sprache dieses Servers. Sie nennt den Grund, die Bedeutung des Eintrags und den
Weg zum Einspruch. Wird ein solcher Eintrag später entfernt, weil ScammerAlert ihn zurückgezogen oder gelöscht hat,
bekommst du eine kurze Nachricht über die Entfernung; keine solche Nachricht gibt es, wenn Defendr eine Liste insgesamt
nicht mehr übernimmt. Defendr speichert nur, ob und wann diese Nachrichten gesendet, abgelehnt oder nicht zustellbar
waren. Gegen einen Eintrag, der nur auf der ScammerAlert-Liste beruht, legst du Einspruch bei ScammerAlert ein; solange
er aktiv ist, kannst du mit /appeal auch beim Defendr-Team Einspruch einlegen, und ein Mensch bei Defendr
entscheidet. Deine Betroffenenrechte gegenüber Defendr (/defendr › Meine Daten) bleiben bestehen.

Beim Wortfilter (Abschnitt 3.17) hält Discord Nachrichten nach den Regeln zurück, die der Server eingeschaltet hat;
den Timeout von zehn Minuten nach drei zurückgehaltenen Nachrichten führt Defendr automatisch aus, wenn der Server ihn
nicht ausgeschaltet hat. Gegen jeden dieser Fälle kannst du Einspruch einlegen (/appeal); wird ein Timeout aufgehoben,
endet er sofort.

Die Webseite trifft keine eigenen Entscheidungen: Jede Aktion dort prüft Defendr nach denselben Regeln wie in Discord.

## 10. Sicherheit

Verschlüsselung gespeicherter sensibler Daten, Zugriffskontrolle und Protokollierung der Zugriffe, regelmäßige
Backups. Für die Webseite zusätzlich: Verbindungen nur verschlüsselt (HTTPS), Sitzungs-Cookies nur für genau eine
Adresse, nicht per Skript lesbar und nur über HTTPS gesendet; der Server speichert nur einen Hash der Sitzungskennung;
Discord-Zugangstoken verschlüsselt; Schutz gegen gefälschte Anfragen von fremden Seiten; auf den öffentlichen Seiten
keine Inhalte von Dritten, nach der Anmeldung nur Profilbilder und Server-Symbole von Discord (Abschnitt 12.9). Die
Webseite hat keinen Zugriff auf die Datenbank; sie fragt Defendr über eine signierte,
nur intern erreichbare Schnittstelle.

## 11. Support-Tickets im Support-Server

<!-- anchor: support -->

11.1 Wer und was. Wenn du im Kanal `#contact-staff` des Support-Servers von Defendr und Checkout oder auf der Webseite
unter „Mein Defendr“ ein Ticket öffnest, verarbeiten wir: deine Discord-Nutzer-ID, das gewählte Thema, Betreff,
Beschreibung und die weiteren Felder des Formulars (verschlüsselt gespeichert), den Server, um den es in der Übersicht
in Abschnitt 11.2 geht, die Zeitpunkte des Öffnens und der letzten Aktivität, den privaten Thread (in Discord sehen
ihn du, das Support-Team von Defendr, die Team-Rolle des Servers und wer in dem Kanal Threads verwalten darf), den
Verlauf seiner Nachrichten (Abschnitt 11.4; auf der Webseite sehen ihn nur du, das Support-Team von Defendr und der
Betreiber von Defendr, alle anderen im Thread lesen ihn in Discord), wer das Ticket geschlossen oder wieder geöffnet hat,
sowie Ticket-Sperren (wer sie gesetzt hat und wann). Zweck: die Beantwortung deiner Anfrage, in Discord und auf der
Webseite, und die Fehlersuche. Rechtsgrundlage: Art. 6 Abs. 1 lit. b DSGVO, soweit du Defendr nach den
Nutzungsbedingungen nutzt, sonst Art. 6 Abs. 1 lit. f DSGVO.

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

<!-- anchor: support-transcript -->

11.4 Verlauf (Transkript). Defendr speichert jede Nachricht im Thread deines Tickets verschlüsselt als Verlauf des
Tickets, damit du und das Support-Team das Ticket auch auf der Webseite lesen und beantworten könnt. Gespeichert werden
der Text, von Anhängen nur Name, Größe, Typ, bei Bildern Breite und Höhe und ob der Anhang als Spoiler markiert ist (die
Dateien selbst bleiben in Discord und lassen sich dort öffnen), wer die Nachricht geschrieben hat (Discord-Nutzer-ID,
Anzeige- und Nutzername und die Kennung des Profilbilds zu diesem Zeitpunkt), wann sie geschrieben und zuletzt geändert
wurde, ob sie in Discord oder auf der Webseite geschrieben wurde, auf welche Nachricht sie antwortet und wie viele
Einbettungen, Sticker, Umfragen und weitergeleitete Nachrichten sie enthält (nur die Zahl, nicht deren Inhalt). Von
Beiträgen, die Defendr selbst in den Thread stellt (etwa die Übersicht aus Abschnitt 11.2 oder eine Statuszeile),
speichert Defendr nur ihre Art. Wird eine Nachricht bearbeitet, ersetzt die neue Fassung die gespeicherte. Wird sie in
Discord gelöscht, löscht Defendr ihren Inhalt auch aus dem Verlauf; an ihrer Stelle bleibt nur ein leerer Platzhalter.
Das geschieht sofort, während Defendr läuft. Wird eine Nachricht bearbeitet oder gelöscht, während Defendr kurz nicht
läuft (etwa während eines Updates), gleicht Defendr beim nächsten Start die neuesten 100 Nachrichten jedes offenen
Tickets ab; bei älteren Nachrichten und bei geschlossenen Tickets bleibt in diesem Fall die zuletzt gespeicherte Fassung
im Verlauf. Ticket-Threads, die es schon gab, als diese Funktion startete, übernimmt Defendr einmalig mit
ihren bisherigen Nachrichten aus Discord; für sie gilt dasselbe. Nachrichten in anderen Kanälen des Support-Servers
speichert Defendr nicht. Wie auf jedem Server, den Defendr schützt, werden alle Nachrichten außerdem kurz im
Arbeitsspeicher auf Gefahren geprüft (Abschnitt 3.1). Ein Ticket ohne Aktivität schließt Defendr nach sieben Tagen
automatisch (Tickets zum Thema Datenauskunft oder Löschung ausgenommen; sie schließt eine Person, sobald die Anfrage
beantwortet ist). Das Team kann ein Ticket wieder öffnen, solange der Thread besteht.

11.5 Lesen und Antworten auf der Webseite. Unter „Mein Defendr“ kannst du den Verlauf deiner Tickets lesen und darauf
antworten. Die Webseite zeigt dir dabei nie mehr als Discord: Du siehst ein Ticket, solange du auf dem Support-Server
bist; ist das Ticket geschlossen oder bist du auf dem Support-Server gerade stummgeschaltet (Timeout), kannst du es
lesen, aber nicht antworten; einen Thread, der in Discord gelöscht wurde, zeigt die Webseite nicht mehr an. Solange eine
Ticket-Seite offen ist, fragt sie etwa alle zehn Sekunden nach neuen Nachrichten. Deine Antwort prüft Defendr vor dem
Senden auf gefährliche Links, wie jede Nachricht in Discord. Danach erscheint sie im Thread in Discord, gesendet über
einen Webhook von Defendr unter dem Namen „Anzeigename (@Nutzername)“ und mit deinem Profilbild; Discord erhält dafür
den Text, diesen Namen und die Adresse deines Profilbilds. Eine kleine Zeile „via the website“ („über die Webseite“)
unter der Antwort nennt dein Konto, ohne dich zu benachrichtigen, und Erwähnungen in deiner Antwort benachrichtigen
niemanden. Die Namensbestandteile „Defendr“, „Team“, „Staff“ und „Mod“ stehen nur dem Defendr-Team zu: Enthält dein
Anzeigename einen davon, nutzt Defendr deinen Nutzernamen, und enthält auch dieser einen, den Namen „Member“. Kann
Defendr in dem Kanal keinen Webhook nutzen, stellt Defendr deine Antwort selbst in den Thread, mit deinem Namen, der
Zeile „via the website“ und deinem Profilbild als kleinem Bild. Antworten, die du auf der Webseite geschrieben hast,
kannst du dort löschen, solange das Ticket offen ist. Das Support-Team von Defendr und der Betreiber lesen und
beantworten Tickets auf der Webseite auf dieselbe Weise.

11.6 Speicherdauer. Ticket, Thread und Verlauf werden 5 Jahre nach dem
Schließen des Tickets gelöscht (Tabelle in Abschnitt 7). Ein offenes Ticket hat kein Ablaufdatum. Wird ein Ticket-Thread
in Discord von Hand gelöscht, bleibt der gespeicherte Verlauf erhalten, bis die Speicherdauer des Tickets endet
(5 Jahre nach dem Schließen). Eine Ticket-Sperre gilt, bis das Team sie
aufhebt. Ein Ticket-Thread, der ohne seinen Eintrag zurückbleibt (nach einer fehlgeschlagenen Erstellung
oder einer Wiederherstellung aus einer Sicherung), wird 5 Jahre nach
seiner Erstellung gelöscht; bis dahin kann Defendr ihn sperren und archivieren, wenn niemand darin geschrieben hat.
Weil kein Eintrag ihn mit einem Mitglied verknüpft, löscht das Team ihn auf einen Löschantrag hin von Hand.

11.7 Deine Rechte. Deine Tickets sind Teil deines Exports (/defendr › Meine Daten › Exportieren), samt Betreff,
Beschreibung, Formularfeldern und Verlauf: deine eigenen Nachrichten vollständig, die Antworten des Support-Teams mit
dem Absender „staff“ (ohne den Namen der Person, die geantwortet hat) und von Nachrichten anderer Personen nur ihre Anzahl. Das gilt auch für ein Ticket, dessen
Thread in Discord gelöscht wurde. Eine Ticket-Sperre erscheint im Export ohne die Person, die sie gesetzt hat. Eine
Löschung (/defendr › Meine Daten › Meine Daten löschen) löscht deine Tickets samt Verlauf und ihre Threads – auch ein
offenes Ticket wird dadurch beendet; eine Ticket-Sperre bleibt bestehen (Schutz anderer). Hast du im Ticket einer
anderen Person geschrieben, entfernt eine Löschung deine Nutzer-ID und deinen Namen aus dem Verlauf dieses Tickets; der
Text bleibt als Teil des Tickets erhalten, wie auch im Thread in Discord. Am schnellsten stellst du eine Anfrage zu deinen
Daten auf der Seite Meine Daten von /defendr (/defendr page:mydata): Sie hält die Anfrage und ihre Frist fest. Eine
Anfrage, die du in einem Ticket zum Thema Datenauskunft oder Löschung stellst, behandeln wir genauso; die Frist von
einem Monat (Art. 12 Abs. 3 DSGVO) läuft ab dem Öffnen des Tickets.

## 12. Webseite

<!-- anchor: website -->

12.1 Aufruf der Webseite. Wenn du eine Seite von defendr.live, app.defendr.live oder status.defendr.live aufrufst,
sendet dein Browser technisch nötige Angaben: deine IP-Adresse, den Zeitpunkt, die aufgerufene Adresse, die
Browser-Kennung (User-Agent), bevorzugte Sprachen und gegebenenfalls die Seite, von der du kommst. Alle Anfragen laufen
über das Netzwerk der Cloudflare, Inc. (Auftragsverarbeiter, Abschnitt 5 und 6), das die verschlüsselte Verbindung
herstellt und die Webseite vor Angriffen und Überlastung schützt. Anfragen an defendr.live und app.defendr.live leitet
Cloudflare durch einen verschlüsselten Tunnel an unseren Server weiter; die Statusseite läuft ganz bei Cloudflare
(Abschnitt 12.7). Unseren Server mieten wir bei der ZAP-Hosting GmbH (Hafenweg 8, 48155 Münster, Deutschland, Abschnitt 5); er
steht in einem Rechenzentrum in Deutschland (Frankfurt am Main).

Unser Webserver nutzt deine IP-Adresse nur, um Anmeldungen und Abmeldungen je Absender zu begrenzen, und schreibt sie
weder in Dateien noch in eine Datenbank. Für Anmeldungen gilt: Er hält sie dafür nur im Arbeitsspeicher (bei IPv6
gekürzt auf das Netz), längstens bis eine Minute nach dem letzten Anmeldeversuch aus diesem Netz. An Defendr gibt er
für diesen Zweck nur einen mit einem geheimen Schlüssel gebildeten Prüfwert weiter, der sich nicht auf die Adresse
zurückrechnen lässt; auch Defendr hält ihn nur im Arbeitsspeicher. Für Abmeldungen hält der Webserver nur einen solchen
Prüfwert im Arbeitsspeicher, nie die Adresse selbst, und längstens bis eine Minute nach der letzten Abmeldung von diesem
Absender. Den geheimen Schlüssel bildet der Webserver bei jedem Start neu.

Cloudflare hält Aufrufe mit IP-Adresse, Zeitpunkt, aufgerufener Adresse, Browser-Kennung und gegebenenfalls der
ausgelösten Schutzregel (zum Beispiel einer Sperr- oder Begrenzungsregel oder einer Browserprüfung) in Analyse- und
Sicherheitsprotokollen fest, die wir in unserem Cloudflare-Konto einsehen können, um Angriffe zu erkennen und
Fehlsperren aufzuheben; Cloudflare löscht sie nach 31 Tagen. Eine Weiterleitung dieser Protokolle an andere
Speicherorte (Logpush) haben wir nicht eingerichtet. Bei Verdacht auf einen Angriff kann Cloudflare vor einer Seite
eine Browserprüfung zeigen; besteht dein Browser sie, setzt Cloudflare dafür ein technisch notwendiges Cookie
(`cf_clearance`, Abschnitt 13). Darüber hinaus verarbeitet Cloudflare Verbindungsdaten nur, soweit es für den Betrieb
und die Sicherheit ihres Netzwerks nötig ist, nach dem Vertrag zur Auftragsverarbeitung. Rechtsgrundlage: Art. 6
Abs. 1 lit. f DSGVO (sichere und erreichbare Webseite).

12.2 Protokolle auf unserem Server. Unser Webserver führt ein Zugriffsprotokoll. Ein Eintrag darin enthält nur
Zeitpunkt, Pfadvorlage, HTTP-Status, Dauer und eine zufällige Anfrage-ID. Diese Zugriffsprotokolle enthalten keine
IP-Adressen oder IP-Hashes, keine URL-Parameter, keine Cookies, keine Zugangsdaten und keine Anfrageinhalte; Server-IDs,
andere veränderliche Pfadteile und unbekannte Pfade werden durch feste Platzhalter ersetzt, nur die Sprache bleibt
stehen. An sehr vollen Tagen oder bei einer plötzlichen Flut von Anfragen werden weitere Anfragen nicht mehr einzeln
festgehalten, sondern nur gezählt. Zweck: Fehler finden und Angriffe erkennen. Ein laufender Webserver löscht Einträge,
die älter als 14 Tage sind, beim Start und danach jede Minute. Nur wenn der dafür
vorgesehene Speicherplatz voll ist, werden ältere Einträge schon früher gelöscht, die ältesten zuerst. Die Protokolle
eines angehaltenen Webservers (zum Beispiel der vorherigen Version nach einem Update oder der Vorschau) löscht eine
eigene Aufgabe einmal am Tag nach derselben Frist; dort können Einträge deshalb bis zu einen Tag älter werden.

Außerdem führt der Webserver ein Ereignisprotokoll. Es hält fest: Serverfehler nach Seite und Fehlerart, Texte, die in
einer Sprache fehlen, Ausfälle und Ablehnungen der Verbindung zwischen der Webseite und Defendr, fehlgeschlagene
Anmeldungen nur mit ihrem Grund, wie viele Einträge das Zugriffsprotokoll verworfen hat und wann es ältere Einträge
vorzeitig gelöscht hat (mit der Minute, ab der die gelöschten Einträge begannen). Ein Eintrag darin enthält nie eine
Person, eine IP-Adresse, eine aufgerufene Adresse, URL-Parameter, Cookies, Inhalte oder eine Sitzung. Gleiche
Ereignisse einer Minute werden in einem Eintrag zusammen gezählt. Zweck: Fehler finden und Angriffe erkennen. Seine
Einträge werden nach denselben 14 Tagen und auf dieselbe Weise gelöscht wie die des
Zugriffsprotokolls; das Ereignisprotokoll belegt höchstens 4 MiB, und ist es voll, gehen die ältesten Einträge zuerst.

Den verschlüsselten Tunnel zu Cloudflare betreibt auf unserem Server das Programm „cloudflared“ von Cloudflare. Es
schreibt ein eigenes Protokoll auf unseren Server, darin aber nur Fehler, die das Programm selbst beenden
(Protokollstufe „fatal“), und Warnungen zu seiner eigenen Verbindung zu Cloudflare (Transport-Protokollstufe „warn“);
aufgerufene Adressen, andere Angaben zu Anfragen und IP-Adressen von Besuchern stehen darin nicht. Wir nutzen dieses
Protokoll nur, um Verbindungsfehler zu finden. Seine Einträge löscht eine tägliche Aufgabe nach
14 Tagen, spätestens einen Tag später.

Andere Protokolle schreibt der Webserver nicht; seine übrigen Ausgaben werden verworfen. Das Programm, das ihn startet
und überwacht, notiert in seinem eigenen Dienstprotokoll nur, wann der Webserver gestartet und beendet wurde, mit
Zeitpunkt und Exit-Code und ohne Angaben zu Besuchern.

12.3 Anmeldung mit Discord. Die Anmeldung ist freiwillig. Ohne sie kannst du alle öffentlichen Seiten nutzen und
Defendr vollständig in Discord bedienen; nur den persönlichen Bereich und die Server-Verwaltung der Webseite gibt es
ausschließlich mit Anmeldung. Du meldest dich über Discord an (OAuth2); Discord zeigt dir vorher, welche Angaben es an
Defendr weitergibt, und wir fragen nur zwei Berechtigungen an: „identify“ und „guilds“. Wir erhalten dadurch deine
Discord-Nutzer-ID, deinen Nutzer- bzw. Anzeigenamen, die Kennung deines Avatars, die Spracheinstellung deines
Discord-Kontos, ob die Zwei-Faktor-Authentifizierung aktiv ist, eine befristete Zugangsberechtigung von Discord
(Zugangstoken) und die Liste deiner Server mit deinen Rechten dort. Deine E-Mail-Adresse und dein Passwort erhalten wir
nicht. Mit der Kennung deines Avatars und den Angaben zu deinen Servern zeigt dir die Webseite dein Profilbild und die
Symbole deiner Server; dein Browser lädt diese Bilder direkt von Discord (Abschnitt 12.9). Gespeichert wird eine Sitzung: Nutzer-ID, Anzeigename, Avatar-Kennung, Sprache, Zwei-Faktor ja/nein, die
Gerätekategorie Desktop oder Mobil (einmal beim Anmelden aus dem Browser-Hinweis „Sec-CH-UA-Mobile“ abgeleitet;
sendet dein Browser ihn nicht, gilt Desktop; die Browser-Kennung selbst speichern wir nicht), Zeitpunkte, ein Hash der
Sitzungskennung und das Zugangstoken (verschlüsselt). Ein Erneuerungstoken speichern wir nicht. Deine Serverliste
speichern wir nicht dauerhaft; wir rufen sie bei Bedarf mit dem Zugangstoken ab und halten sie höchstens fünf Minuten
im Arbeitsspeicher, um dir die Server zu zeigen, die du verwalten kannst, und um eine Anfrage zu einem Server, der nicht
in ihr steht, sofort abzulehnen. Zugriff gibt die Liste nie: Ob du etwas sehen oder ändern darfst, prüft Defendr bei
jeder Anfrage neu anhand der aktuellen Daten in Discord. Die Sitzung endet nach 7 Tagen
ohne Aktivität, spätestens nach 30 Tagen, und mit einer Löschung deiner Daten.
Meldest du dich ab, endet sie, sobald Defendr die Abmeldung bestätigt. Kann Defendr sie nicht bestätigen, ist dieser
Browser trotzdem abgemeldet, und die Seite sagt dir das; die Sitzung endet dann, wenn sie
7 Tage nicht mehr genutzt wurde, oder wenn du dich wieder anmeldest und „Überall
abmelden“ wählst. Den Zugriff von Defendr auf dein Discord-Konto kannst du jederzeit in Discord unter Einstellungen ›
Autorisierte Apps widerrufen; beende dann zusätzlich deine Sitzungen im persönlichen Bereich oder melde dich ab, damit
auch die Sitzung endet.

12.4 Anmeldeverlauf. Zu deinem Konto speichern wir, wann du dich angemeldet und abgemeldet hast, wann du dich auf allen
Geräten abgemeldet hast und wann du eine einzelne andere Sitzung beendet hast, jeweils mit dem Zeitpunkt und, soweit
bekannt, der Gerätekategorie aus Abschnitt 12.3, aber ohne IP-Adresse, ohne Browser-Kennung und ohne Standort. Eine
fehlgeschlagene Anmeldung speichern wir zu deinem Konto nur in einem Fall: wenn Discord dich schon bestätigt hatte und
Defendr die Anmeldung danach rückgängig gemacht hat, weil die Sitzung nicht zustande kam. Lehnt Discord eine Anmeldung
ab oder scheitert sie, bevor bekannt ist, wer sich anmeldet, bleibt davon nur eine anonyme Zählung nach dem Grund, im
Ereignisprotokoll aus Abschnitt 12.2 und, wenn Defendr schon gefragt wurde, im eigenen Protokoll von Defendr, nie mit
einer Person. Brichst du die Anmeldung auf der Bestätigungsseite von Discord ab, halten wir dazu keine fehlgeschlagene
Anmeldung fest. Endet ein Zugangsrecht, das du für einen geschützten Bereich der Webseite hattest, enden alle deine
Sitzungen auf der Webseite, und der Verlauf hält fest, wann das war. Der Verlauf ist Teil deines Exports (Abschnitt 8);
im persönlichen Bereich siehst du außerdem, auf welchen Geräten du gerade angemeldet bist, und kannst sie abmelden. Die
Einträge werden nach 365 Tagen automatisch gelöscht und mit einer Löschung deiner
Daten.

12.5 Persönliche Einstellungen. Deine Wahl von Sprache, Farbschema, Akzentfarbe, Dichte und Bewegung steht in Cookies
in deinem Browser (Abschnitt 13). Speicherst du sie angemeldet unter „Meine Einstellungen“, legen wir sie zusammen mit
deiner Wahl, ob Direktnachrichten von Defendr der Sprache der Webseite folgen, bei Defendr zu deiner Discord-ID ab; bei
deiner nächsten Anmeldung auf einem anderen Gerät gelten sie dann auch dort. Außerdem speichern wir, bis zu welchem
Eintrag du dein Postfach im persönlichen Bereich als gelesen markiert hast, und ob du den Hinweis gesehen hast, dass
deine Antworten auf ein Ticket in Discord unter deinem Namen erscheinen (Abschnitt 11.5). Du kannst die Einstellungen
jederzeit ändern. Die gespeicherten Einstellungen bewahren wir ohne feste Frist auf, bis du die Löschung deiner Daten verlangst,
damit sie beim nächsten Besuch wieder gelten; eine Löschung entfernt sie. Wann du sie zuletzt genutzt hast, speichern
wir nicht; bei den Einstellungen steht nur, wann du sie zuletzt gespeichert hast, und jedes Speichern steht mit dem
Zeitpunkt und den geänderten Einstellungen (ohne die Werte) im Protokoll aus Abschnitt 12.6. Entziehst du Defendr in
Discord unter „Autorisierte Apps“ den Zugriff (Abschnitt 12.3), bleiben sie bestehen; dafür verlangst du die Löschung.

12.6 Was du auf der Webseite tust. Meldungen, Einsprüche, Support-Tickets, Anfragen zu deinen Rechten, Exporte und
Änderungen an Server-Einstellungen verarbeitet Defendr genauso, wie wenn du sie in Discord erledigst (Abschnitt 3.2
bis 3.6, 8 und 11); dafür gelten dieselben Grenzen, Rechte und Löschfristen. Zu Aktionen, die etwas auslösen oder
ändern, speichern wir zusätzlich einen Beleg (Vorgangsnummer, Art der Aktion, betroffener Server, Zeitpunkte, Status
und Ergebnis; die Anfrage selbst nur als Prüfwert, einen Hash), damit ein doppelter Klick nichts doppelt ausführt und
du den Stand sehen kannst. Der Beleg selbst wird 365 Tage nach dem Abschluss der
Aktion gelöscht, mit einer Löschung deiner Daten früher. Zusätzlich halten wir jede Aktion auf der Webseite, die etwas
auslöst, ändert oder exportiert, in unserem Aktionsprotokoll fest: deine Nutzer-ID, die Art der Aktion, worauf sie sich
bezieht (etwa den Server, einen Fall oder ein Ticket), den Zeitpunkt, das Ergebnis, die Beleg- und die Anfrage-ID und
kurze Bezugsangaben wie die Versionsnummer geänderter Server-Einstellungen; bei deinen persönlichen Einstellungen nur,
welche du geändert hast, nie die Werte. Eine Aktion, die Defendr erst später ausführt, bekommt einen Eintrag bei der
Annahme und einen beim Abschluss. Sendest oder löschst du eine Antwort in einem Ticket (Abschnitt 11.5), nennt der
Eintrag die Ticketnummer, die Art und den Zeitpunkt, nie den Text; einen Beleg legen wir dafür nicht an. Antwortet oder handelt das Support-Team von Defendr über die Webseite, wird das ebenso im
Aktionsprotokoll festgehalten. Der Eintrag dient der Nachvollziehbarkeit (Art. 6 Abs. 1 lit. f DSGVO, Art. 5 Abs. 2
DSGVO), wird 1825 Tage aufbewahrt, ist Teil deines Exports und bleibt bei einer Löschung deiner
Daten bestehen. Änderungen, die du über die Webseite an einem Server vornimmst,
stehen wie in Discord mit deiner Nutzer-ID im Verlauf und im Log-Kanal des Servers, dort mit dem Hinweis „über die
Webseite“. Ein Link, den du im Link-Prüfer eingibst, wird wie mit /check in Discord geprüft und nicht gespeichert.
Einen Export, den du über die Webseite anforderst, kannst du nur in derselben Sitzung und nur einmal herunterladen,
höchstens 15 Minuten lang; die verschlüsselte Kopie wird danach gelöscht.

12.7 Statusseite. status.defendr.live zeigt nur den Betriebszustand von Defendr und der Webseite. Sie läuft bei
Cloudflare (Cloudflare Workers), nicht auf unserem Server, setzt keine Cookies und speichert keine Daten über dich;
für den Aufruf gilt Abschnitt 12.1.

12.8 E-Mail. Schreibst du an contact@defendr.live, privacy@defendr.live oder security@defendr.live, nimmt
Cloudflare die E-Mail für unsere Domain an (Cloudflare Email Routing) und leitet sie an unser Postfach bei Gmail
weiter, einem Dienst der Google Ireland Limited (Gordon House, Barrow Street, Dublin 4, Irland); Google ist damit
Empfänger deiner E-Mail und speichert sie auch in den USA (Abschnitt 5 und 6). Wir verarbeiten deine E-Mail-Adresse,
den Inhalt und die technischen Angaben der E-Mail, um dir zu antworten. Wir löschen E-Mails, sobald sie für die
Bearbeitung nicht mehr gebraucht werden, spätestens drei Jahre nach Abschluss der Anfrage, außer eine gesetzliche
Pflicht verlangt eine längere Aufbewahrung. Meldungen zu Sicherheitslücken an security@defendr.live bearbeiten
wir, um die Lücke zu prüfen und zu beheben (Art. 6 Abs. 1 lit. f DSGVO). Öffentlich danken wir dir dafür mit Namen
oder Pseudonym, zum Beispiel im Changelog des Sicherheits-Updates, nur wenn du einwilligst (Art. 6 Abs. 1 lit. a
DSGVO). Du kannst die Einwilligung jederzeit mit einer E-Mail an security@defendr.live widerrufen; wir entfernen
die Nennung dann, soweit wir das können. Der Widerruf berührt nicht die Rechtmäßigkeit der Nennung bis dahin.

12.9 Keine Analyse, keine Werbung; Bilder von Discord nur nach der Anmeldung. Die Webseite nutzt keine Analyse- oder
Statistikdienste, keine Zählpixel, keine Werbung und keine Social-Media-Plugins, und unsere Seiten enthalten kein
Captcha; nur Cloudflare kann bei Verdacht auf einen Angriff eine automatische Browserprüfung vorschalten (Abschnitt 12.1
und 13). Schriften, Skripte und unsere eigenen Bilder kommen von unserem eigenen Server; die einzigen Bilder von
anderswo sind die unten beschriebenen Bilder von Discord. Videos oder Discord-Widgets bindet die Webseite nicht ein, und
die öffentlichen Seiten laden nichts von Discord.

Auf den Seiten nach der Anmeldung (app.defendr.live) zeigt die Webseite dein Profilbild und die Symbole deiner Server,
wie du sie aus Discord kennst, und auf den Seiten deiner Support-Tickets die Profilbilder der Personen, die im Ticket
geschrieben haben. Dein Browser lädt diese Bilder direkt aus dem Content-Delivery-Netzwerk von Discord
(cdn.discordapp.com, das Cloudflare für Discord betreibt). Discord Inc. erhält dabei deine IP-Adresse, die
Browser-Kennung (User-Agent), den Zeitpunkt und die Adresse des Bildes, in der deine Nutzer-ID, die ID des Servers oder
die Nutzer-ID der Person auf dem Bild steht. Beim Profilbild einer anderen Person erfährt Discord so, dass ihr Bild von
deiner IP-Adresse aus geladen wurde. Eine Herkunftsadresse sendet dein Browser dabei nicht, und für diese Anfragen sendet er keine Cookies und nimmt
keine an. Discord verarbeitet diese Daten als eigener Verantwortlicher nach seiner eigenen Datenschutzerklärung, auch
in den USA (Abschnitt 5 und 6). Rechtsgrundlage: Art. 6 Abs. 1 lit. f DSGVO (Abschnitt 4).

Links zu fremden Seiten, etwa zu Discord (Einladung, Anmeldung, Support-Server) oder zu GitHub
(frühere Fassungen dieser Texte), führen dich auf deren Seiten, wo deren eigene Datenschutzerklärungen gelten; unsere
Seiten geben dabei keine Herkunftsadresse weiter.

## 13. Cookies und Speicher im Browser

<!-- anchor: cookies -->

Die Webseite speichert nur Angaben in deinem Browser, die für den von dir ausdrücklich gewünschten Dienst unbedingt
erforderlich sind (§ 25 Abs. 2 Nr. 2 TDDDG): die Anmeldung und die Einstellungen, die du selbst wählst. Dafür ist keine
Einwilligung nötig, deshalb gibt es kein Cookie-Banner. Tracking-, Werbe- oder Analyse-Cookies gibt es nicht. Unsere
eigenen Cookies gelten jeweils nur für genau die Adresse, die sie setzt (defendr.live oder app.defendr.live), und
werden nur über HTTPS gesendet. Du kannst Cookies in deinem Browser jederzeit löschen; danach bist du abgemeldet und
deine Einstellungen gelten wieder in der Grundform.

| Name                           | Art                                                                     | Inhalt                                                                                                           | Zweck                                                                                                                              | Speicherdauer                                                                                     |
| ------------------------------ | ----------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| `__Host-sid`                   | Cookie (app.defendr.live, nicht per Skript lesbar)                      | eine zufällige Sitzungskennung mit einem Prüfwert der Webseite (der Server speichert nur einen Hash der Kennung) | hält dich nach der Anmeldung angemeldet                                                                                            | bis zur Abmeldung; höchstens 30 Tage (Sitzung endet nach 7 Tagen ohne Aktivität)                  |
| `__Host-oauth`                 | Cookie (app.defendr.live, nicht per Skript lesbar)                      | versiegelter Anmeldevorgang (Zufallswert gegen Fälschung, PKCE-Prüfwert, Sprache, Startzeit)                     | schützt die Anmeldung mit Discord gegen Fälschung und Wiederholung                                                                 | 10 Minuten; wird nach der Anmeldung gelöscht                                                      |
| `__Host-lang`                  | Cookie                                                                  | die Sprache, die du selbst gewählt hast (z. B. „de“)                                                             | zeigt die Webseite in deiner gewählten Sprache                                                                                     | 1 Jahr oder bis du sie änderst                                                                    |
| `__Host-theme`                 | Cookie                                                                  | deine Wahl hell, dunkel oder wie das System                                                                      | zeigt die Webseite im gewählten Farbschema                                                                                         | 1 Jahr oder bis du sie änderst                                                                    |
| `__Host-motion`                | Cookie                                                                  | deine Wahl für Bewegung (reduziert, wie das System oder voll)                                                    | schaltet Animationen ab oder zu, wie du es gewählt hast                                                                            | 1 Jahr oder bis du sie änderst                                                                    |
| `__Host-accent`                | Cookie                                                                  | deine Akzentfarbe (Signalgrün, Grape, Lagoon oder Graphite)                                                      | zeigt die Webseite in der gewählten Akzentfarbe                                                                                    | 1 Jahr oder bis du sie änderst                                                                    |
| `__Host-density`               | Cookie                                                                  | deine Wahl der Dichte (normal oder kompakt)                                                                      | zeigt Listen und Tabellen so dicht, wie du es gewählt hast                                                                         | 1 Jahr oder bis du sie änderst                                                                    |
| `defendr.setup.v1.<Server-ID>` | Sitzungsspeicher des Browsers (app.defendr.live), ein Eintrag je Server | deine noch nicht gespeicherten Antworten im Einrichtungsassistenten eines Servers                                | damit ein Neuladen der Seite deine Antworten nicht verwirft; an Defendr geht nichts, bevor du auf „Prüfen und abschließen“ drückst | bis die Einrichtung gespeichert ist, du auf „Einrichtung abbrechen“ drückst oder den Tab schließt |

Cloudflare kann zum Schutz der Webseite eigene, ebenfalls unbedingt erforderliche Cookies setzen, aber nur, wenn wir
die jeweilige Schutzfunktion eingeschaltet haben:

| Name           | Wann                                                                | Zweck                                                  | Speicherdauer                                                  |
| -------------- | ------------------------------------------------------------------- | ------------------------------------------------------ | -------------------------------------------------------------- |
| `__cf_bm`      | Bot-Schutz von Cloudflare eingeschaltet                             | Schutz der Webseite vor Bots und Angriffen             | 30 Minuten                                                     |
| `cf_clearance` | dein Browser musste eine Sicherheitsprüfung von Cloudflare bestehen | erspart dir die erneute Prüfung bei jedem Seitenaufruf | wie in Cloudflare eingestellt, standardmäßig 30 Minuten        |
| `_cfuvid`      | Begrenzung der Anfragen je Besucher eingeschaltet                   | faire Begrenzung der Anfragen je Besucher              | bis du den Browser schließt                                    |
| `cf_chl_*`     | Cloudflare zeigt dir gerade eine Sicherheitsprüfung                 | führt die Sicherheitsprüfung durch                     | nur während der Prüfung, höchstens bis du den Browser schließt |

## 14. Änderungen

Versionen: https://github.com/FunnyBuddys/defendr-legal/tags. Die jeweils geltende Fassung steht unter https://defendr.live/de/privacy. Wesentliche Änderungen
kündigen wir im Changelog (/defendr › Changelog) und auf der Webseite an, spätestens an dem Tag, an dem sie gelten.
