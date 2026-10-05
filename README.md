<!--
author:   TGM - Grundlagen der Informatik
email:    office@tgm.ac.at
version:  1.0.0
language: de
narrator: Deutsch Female
comment:  Hardware-Grundlagen, Internetrecherche, Fake-News-Check, Cloud & Backup
          und Passwortmanager - gängige Suchmaschinen und geeignete Inhalte aus
          dem Internet suchen und auf Qualität prüfen.
mode:     Textbook
-->

# Datenorganisation und Internetrecherche

Informationen zu einem Thema findet man heute fast ausschließlich im Internet - leider auch sehr viel **Falschinformation**. Diese zu erkennen ist eine Kernkompetenz, die wir in diesem Kurs trainieren: an einer konkreten Hardware-Recherche (Notebook + Stand-PC um je 800 €), ergänzt durch Cloud-Speicher, Backup-Strategie und Passwortmanager.

## CPU, RAM, SSD - die drei Kennzahlen

Bevor du ein Gerät bewertest, musst du seine Spezifikationen lesen können.

| Komponente | Aufgabe | Einheit |
|---|---|---|
| **CPU** (Prozessor) | Führt Berechnungen/Befehle aus - das "Gehirn" des Rechners | Taktfrequenz in **GHz**, Kerne/Threads |
| **RAM** (Arbeitsspeicher) | Hält aktuell benötigte Daten/Programme bereit für schnellen Zugriff | Kapazität in **GB** |
| **SSD** (Massenspeicher) | Speichert Betriebssystem, Programme und Dateien dauerhaft | Kapazität in **GB/TB**, Geschwindigkeit in **MB/s** |

> [!tip] 💡 Merkregel
> CPU **rechnet**, RAM **merkt sich kurzfristig**, SSD **speichert dauerhaft**. Je mehr RAM, desto mehr Programme gleichzeitig ohne Ruckeln; je schneller die SSD, desto schneller starten Windows und Programme.

In welcher Einheit wird die **Taktfrequenz** einer CPU angegeben?

- [( )] MB/s
- [(X)] GHz
- [( )] Watt
- [( )] IOPS
***
**GHz (Gigahertz)** - sie beschreibt, wie viele Taktzyklen der Prozessor pro Sekunde ausführen kann.
***

Ordne jede Komponente ihrer passenden Einheit zu:

| Komponente |     Einheit      |
|------------|-------------------|
| CPU        | [->[ GB \| (GHz) \| Watt ]] |
| RAM        | [->[ (GB) \| GHz \| MB/s ]] |
| SSD        | [->[ GHz \| (GB/TB) \| Volt ]] |

### Anforderungen für leistungsintensive Software

Programme wie **Adobe Photoshop, After Effects, Premiere** oder **Autodesk Maya** stellen deutlich höhere Hardware-Anforderungen als Office-Anwendungen - sie verlangen viele CPU-Kerne, reichlich RAM und oft eine dedizierte Grafikkarte (GPU) mit eigenem Videospeicher (VRAM).

Welche Komponenten sind für Videoschnitt/3D-Rendering besonders wichtig? (Mehrfachauswahl möglich)

- [[X]] Dedizierte Grafikkarte (GPU) mit viel VRAM
- [[X]] Ausreichend RAM (16 GB+)
- [[X]] Schnelle SSD für Projektdateien und Caches
- [[ ]] Ein möglichst kleines Display
- [[ ]] Ein optisches Laufwerk (DVD/Blu-ray)

- [ ] __Recherchiere__: Welche Mindest-Systemanforderungen geben Adobe bzw. Autodesk offiziell für *eine* der genannten Anwendungen an? Notiere Quelle + Werte in deinem Grafiz.

### Anschlüsse am Notebook

| Anschluss | Typischer Einsatz |
|---|---|
| USB-C / Thunderbolt | Laden, externe Displays, schnelle externe Laufwerke |
| USB-A | Maus, Tastatur, USB-Stick, ältere Peripherie |
| HDMI | Externer Monitor/Beamer |
| 3.5 mm Klinke | Kopfhörer/Headset ohne Bluetooth |
| microSD/SD-Kartenleser | Kamera-Speicherkarten direkt auslesen |
| RJ45 (LAN) | Stabiles, kabelgebundenes Netzwerk |

- [ ] __Notiere__, auf welche 2-3 dieser Anschlüsse du bei deiner Notebook-Wahl besonders Wert legst - und warum.

## Recherche-Auftrag: Notebook & Stand-PC

> [!IMPORTANT]
> Finde ein **Notebook** und einen **Stand-PC**, Budget jeweils **800 €**, deren Leistung zu einer 5-jährigen IT-Ausbildung passt.

- [ ] __Notebook__ - passendes Gerät um ca. 800 € finden (CPU/RAM/SSD/Anschlüsse prüfen)
- [ ] __Stand-PC__ - passendes Gerät um ca. 800 € finden, vergleichbare Zielsetzung
- [ ] __Screenshots__ je Gerät mit sichtbarer Leistungsübersicht
- [ ] __URLs__ zu beiden Produktseiten notieren
- [ ] __Quellen__ der Recherche dokumentieren

Fasse am Ende alles - Screenshots, URLs, Quellen - als **ein PDF** zusammen (siehe [Abgabe](#abgabe)).

## Internetrecherche & Falschinformation

Suchmaschinen liefern **Treffer**, keine automatische **Garantie für Richtigkeit**. Wer im Internet recherchiert, braucht eine Methode, um Inhalte auf Qualität zu prüfen - sonst verbreitet man ungewollt Fake News weiter.

### Checkliste: Quelle prüfen

Bringe die Schritte eines sinnvollen Fakten-Checks in eine plausible Reihenfolge (von zuerst bis zuletzt):

<!-- data-show-partial-solution -->
Schritt 1: [[ Autor/Impressum der Seite identifizieren | Überschrift glauben und sofort teilen | Mit einer zweiten, unabhängigen Quelle vergleichen | Datum der Veröffentlichung prüfen ]]

Schritt 2: [[ Datum der Veröffentlichung prüfen | Autor/Impressum der Seite identifizieren | Überschrift glauben und sofort teilen | Mit einer zweiten, unabhängigen Quelle vergleichen ]]

Schritt 3: [[ Mit einer zweiten, unabhängigen Quelle vergleichen | Datum der Veröffentlichung prüfen | Autor/Impressum der Seite identifizieren | Überschrift glauben und sofort teilen ]]

> [!NOTE]
> Es gibt nicht *die eine* richtige Reihenfolge - entscheidend ist, dass Autor, Datum und eine Gegenprobe mit einer zweiten Quelle **vor** dem Teilen passieren, nicht danach.

### Woran erkennt man Falschinformation? [^quelle]

[^quelle]: Vgl. "7 Tipps gegen Fake News", jugendportal, [online](https://www.jugendportal.at/factorfake/fake-news-erkennen) (zuletzt besucht 2022-08-08).

- [[X]] Reißerische Überschrift, die starke Emotionen auslösen soll
- [[X]] Kein erkennbarer Autor oder Impressum
- [[X]] Inhalt wird von keiner anderen seriösen Quelle bestätigt
- [[X]] Schlechte Quellenangaben oder gar keine
- [[ ]] Der Artikel ist länger als 500 Wörter
- [[ ]] Die Seite verwendet HTTPS

**Warum ist es so wichtig, bei Informationen die Quelle anzugeben?**

So kann jede:r die Aussage selbst nachprüfen, einordnen und von Meinung/Werbung unterscheiden - ohne Quelle ist eine Aussage nicht überprüfbar und damit wissenschaftlich/journalistisch wertlos.

Ist dir schon einmal Falschinformation (Fake News) untergekommen? Woran hast du sie erkannt?

    [[___   ___]]

- [ ] __Recherchiere__ ein konkretes, selbst gefundenes Beispiel für Fake News oder stark irreführende Inhalte - mit Link und kurzer Begründung, warum es unseriös ist.

## Cloud-Speicher & Backup

**Cloud-Speicher** ist Speicherplatz auf fremden Servern im Internet, auf den du über eine Internetverbindung von jedem Gerät zugreifst (z. B. Google Drive, OneDrive, iCloud, Dropbox, Nextcloud).

Bewerte folgende Aussagen zu Cloud-Speicher:

    [(stimmt)(stimmt nicht)]
    [                       ] Man kann von mehreren Geräten gleichzeitig auf die Daten zugreifen.
    [                       ] Ohne Internetverbindung ist der Zugriff grundsätzlich uneingeschränkt möglich.
    [                       ] Der Anbieter trägt Mitverantwortung für Datensicherheit und -verfügbarkeit.
    [                       ] Cloud-Speicher ersetzt automatisch ein eigenes Backup.

Was sind Vor- und Nachteile von Cloud-Speicher?

| Vorteile | Nachteile |
|---|---|
| Zugriff von überall, geräteübergreifend | Abhängigkeit von Internetverbindung |
| Automatische Synchronisation/Versionierung | Abhängigkeit vom Anbieter (Ausfall, Preisänderung) |
| Einfaches Teilen mit anderen | Datenschutz/Speicherort oft im Ausland |
| Schutz vor lokalem Geräteverlust (Diebstahl, Defekt) | Laufende Kosten ab einer gewissen Größe |

> [!WARNING]
> Cloud-Speicher ist **kein Ersatz** für ein echtes Backup, solange nicht mehrere **Versionen** und ein **vom Original unabhängiger Speicherort** vorhanden sind. Wird eine Datei in der Cloud gelöscht/verschlüsselt (z. B. durch Ransomware) und sofort synchronisiert, ist sie überall weg.

Nutzt du selbst Cloud-Speicher? Wenn ja, welche(n)?

    [[___]]

Was ist deine aktuelle **Backup-Strategie**?

    [[___   ___]]

Welche Daten würdest du **unwiederbringlich verlieren**, wenn dein Laptop jetzt sofort kaputt oder gestohlen wäre?

    [[___   ___]]

## Passwortmanager

In deiner IT-Karriere sammelst du hunderte Logins. Ein **Passwortmanager** speichert sie verschlüsselt hinter einem einzigen Master-Passwort und kann für jeden Dienst ein eigenes, langes Passwort generieren.

| Passwortmanager | Kostenlose Version | Besonderheit |
|---|:---:|---|
| [Bitwarden](https://bitwarden.com/pricing/) | ✅ | Open Source, sehr beliebt |
| [1Password](https://1password.com/de/pricing#personal) | ❌ (Trial) | Starke UX, Family-Pläne |
| [KeePass](https://keepass.info/) | ✅ | Lokale Datenbank, keine Cloud nötig |
| [LastPass](https://www.lastpass.com/de/pricing) | ✅ (eingeschränkt) | Bekannt, aber Sicherheitsvorfälle in der Vergangenheit |
| [Dashlane](https://www.dashlane.com/de/pricing) | ✅ (eingeschränkt) | Eingebautes VPN in höheren Plänen |
| [Proton Pass](https://proton.me/pass/pricing) | ✅ | Von Proton (ProtonMail), E2E-verschlüsselt |

> [!tip] 💡 Vor der Installation
> - [Verbraucherzentrale: Starke Passwörter](https://www.verbraucherzentrale.de/wissen/digitale-welt/datenschutz/starke-passwoerter-so-gehts-11672) lesen
> - Browser-Extension installieren
> - Mit dem Handy synchronisieren
> - Passwort-Generator nutzen: pro Login ein eigenes, **mind. 30 Zeichen** langes Passwort

- [ ] __Installiere__ einen Passwortmanager (falls noch keiner vorhanden) und vergleiche mindestens zwei Optionen aus der Tabelle.

Für welchen Passwortmanager hast du dich entschieden? Warum?

    [[___   ___]]

## Abgabe

Alle Rechercheergebnisse (Notebook, Stand-PC, Beispiel für Falschinformation, Antworten, Quellen) werden in **einem Grafiz** zusammengefasst, eingescannt und als **ein PDF** auf Moodle hochgeladen.

- [ ] Screenshot Notebook (mit Leistungsübersicht) + URL
- [ ] Screenshot Stand-PC (mit Leistungsübersicht) + URL
- [ ] Beantwortete Fragestellungen inkl. Quellenangaben
- [ ] Gewählter Passwortmanager + Begründung

Zum Scannen/Erstellen des PDFs:

- Microsoft Office Lens: [Android](https://play.google.com/store/apps/details?id=com.microsoft.office.officelens&hl=de_AT&gl=US) | [iPhone](https://apps.apple.com/at/app/microsoft-office-lens-pdf-scan/id975925059)
- Online PDF Editor: [pdfFiller](https://www.pdffiller.com/de/)

Im anschließenden **Abgabegespräch** werden kurze Kontrollfragen zum Verständnis gestellt.

------

**Version** *20241029v2* - Quelle Fake-News-Tipps: siehe Fußnote oben; "Internet Recherche" [online](https://elearning.tgm.ac.at/pluginfile.php/11014/mod_folder/content/0/Internet%20Recherche.pdf)
