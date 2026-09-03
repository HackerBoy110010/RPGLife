# Life RPG

Dein Leben als Pixel-RPG. Gewohnheiten werden zu Dailies mit Streaks, Aufgaben zu Quests mit XP, und dein Fortschritt landet als Level, Skills und Gold auf dem Homescreen-Widget. Komplett offline, kein Account, keine Tracker – deine Daten gehören dir.

**Download:** [Neueste Version (Releases)](https://github.com/HackerBoy110010/RPGLife/releases) – `LifeRPG.apk` herunterladen, öffnen, installieren. Android fragt einmalig nach der Erlaubnis für Apps außerhalb des Play Store. Updates einfach drüber installieren – Spielstand und Einstellungen bleiben erhalten.

---

## Funktionen

### Quests und Gewohnheiten

- **Quests:** einmalige Aufgaben mit XP aus Dauer x Anstrengung
- **Dailies:** tägliche Gewohnheiten mit Streak-Zahl und bis zu +50% Streak-Bonus
- **Tagesquests:** jeden Tag wird pro Kategorie eine Daily zur Tagesquest mit doppelten XP – oben angepinnt, mit eigenem Badge
- **Quest-Ketten:** Quests können Voraussetzungen haben und bleiben so lange gesperrt, bis die vorherige erledigt ist
- **Custom-XP:** optional eigene XP-Werte pro Quest, Unterquest und Challenge statt automatischer Berechnung
- **Vorlagen:** 90 fertige Tagesquest-Vorschläge (9 pro Skill) zum Anklicken
- **Zufalls-Quests:** täglich 2 überraschende Aufgaben mit Bonus-XP, neu würfeln per Reroll (täglich gratis, Nachschub kaufbar)

### Fortschritt und Belohnung

- **XP und Level:** Gesamtlevel mit Level-Boni in Gold
- **10 Skills:** jeder Fortschritt zählt auf den passenden Skill mit eigenem Skill-Level
- **Softcap:** volle XP bis 160 pro Skill und Tag, danach gedrosselt – Dranbleiben schlägt Grinden (abschaltbar)
- **Challenges:** Wochenpensum mit Check-ins, 7x pro Woche bedeutet bei einem verpassten Tag Neustart
- **Projekte:** große Ziele mit Unterquests und Abschlussbonus
- **Shop:** eigene Belohnungen mit selbst gewähltem Preis und Freischalt-Bedingung (Level, Skill, Quest oder Challenge)
- **Errungenschaften:** vier Stufen, darunter über ein Dutzend Geheimerfolge

### Widgets

- Drei Homescreen-Widgets: **Pixel**, **Nothing** und **Custom**
- **Widget-Designer:** eigenes Design mit Farben (HSV-Picker + Palette), Deckkraft-Schaltern, Rahmen, Schrift- und Symbol-Stil – die Vorschau zeigt exakt das fertige Widget (gleicher Renderer), Übernehmen lädt es auf den Homescreen
- **Profi-Modus:** jedes Element einzeln in Farbe, Größe, Deckkraft, Stil und Symbol
- Runde Ecken: der Rahmen ist die äußere Begrenzung, dahinter scheint der Hintergrund durch – sauber auf jedem Launcher
- Widgets aktualisieren sich automatisch mit jedem Fortschritt

### Sync und Daten

- **Geräte-Sync:** Spielstand zwischen Geräten abgleichen – wahlweise über **WebDAV** (Koofr, Nextcloud, HiDrive u. a.) oder **Google Drive** (unsichtbarer App-Bereich deines Accounts)
- **Merge statt Überschreiben:** Streaks werden vereint, Zähler konservativ zusammengeführt, Löschungen bleiben Löschungen – kein Datenverlust bei Parallel-Nutzung
- **Offline-first:** die App funktioniert immer und überall ohne Netz, Sync ist reine Ergänzung
- **Backup/Import:** kompletter Spielstand als Text zum Wegspeichern

### Updates

- **Update-Prüfung bei jedem App-Öffnen** gegen dieses Repository (Repository ist voreingestellt, eigenes möglich)
- **Benachrichtigung** sobald ein neues Release verfügbar ist – einmalig pro Version
- Download-Button direkt in den Einstellungen, Installation drüber ohne Datenverlust

### Darüber hinaus

- **Themes:** Pixel, Nothing Dark, Nothing Light (an Nothing OS angelehnt)
- **Nachrichten-Archiv:** alle Meldungen zum Nachlesen, mit Zähler-Badge
- **App-Sperre:** optional per PIN oder Fingerabdruck (Abhak-Schutz)
- **Erinnerungen:** tägliche Benachrichtigung um 18 Uhr bei offenen Quests und gefährdeten Streaks
- **Feedback:** Vorschläge und Probleme direkt aus der App einreichen
- **Sortierung:** Dailies nach Streak, Skill, Name oder Neuheit; Kategorien einklappbar

---

## Versionsverlauf

Neue Funktionen werden hier pro Version ergänzt. Ältere Änderungen vor 4.34 sind zusammengefasst.

| Version | Neu |
|---|---|
| **4.49** | Update-Check robuster: Clone-URLs mit `.git` und vollständige GitHub-Links werden automatisch bereinigt; konkretere Fehlermeldung bei Problemen |
| **4.48** | Update-Prüfung bei **jedem** App-Öffnen (inkl. Rückkehr aus dem Hintergrund, gedrosselt) und **System-Benachrichtigung** bei neuem Release (einmalig pro Version) |
| **4.47** | Standard-Repository voreingestellt – Update-Check läuft ohne jegliche Konfiguration |
| **4.46** | **Update-System über GitHub Releases:** Repository eintragbar, tägliche Prüfung, Download-Button in den Einstellungen |
| **4.45** | Kontrast-Systematik: Schrift auf Akzent-Farben folgt einer eigenen Variable – Nachrichten-Zähler und Tab-Beschriftungen jetzt dunkel auf Gold statt weiß |
| **4.44** | Tagesquest-Badge sitzt immer als eigene Zeile ganz vorne in der Karte – identisch auf jedem Gerät und Format |
| **4.43** | Deterministische Zeilenausrichtung in Überschriften, Titeln und Meta-Zeilen (unabhängig von Gerät, Schriftzoom und Querformat) |
| **4.42** | Layout-Auffrischung nach Geräte-Drehung (WebView-Reflow) und feste Zeilenhöhen in Quest-Karten |
| **4.41** | Tagesquest-Badge lesbar gemacht (dunkle Schrift auf Gold) und Meta-Reihe flex-zentriert |
| **4.40** | HUD-Münze und statische Icons wechseln korrekt zum Theme-Sprite (Nothing-Symbole im Nothing-Stil) |
| **4.39** | Feedback-Formular für Vorschläge und Probleme direkt in den Einstellungen |
| **4.38** | Runde Ecken: Rahmen als letzte Begrenzung des Widgets, transparente Ecken auf jedem Launcher |
| **4.35 – 4.37** | Widget-Designer komplett neu: ein Canvas-Renderer für Vorschau UND Widget (identisch), Layout-Engine ohne Überlappung, Entwurfs-Modus mit Übernehmen, Sprites als Data-URIs |
| **4.34** | **Geräte-Sync** über WebDAV und Google Drive mit Merge-Engine (Streak-Vereinigung, Tombstones, Gold-Ableitung), Sync-Tab im Backup-Modal |
| **< 4.34** | Quests, Dailies, Streaks, XP/Level/Skills, Tagesquests, Challenges, Projekte, Zufalls-Quests, Shop, Errungenschaften, Widgets, Themes, Nachrichten-Archiv, PIN-Sperre, Backup/Import |

---

## Datenschutz

Die App speichert alles ausschließlich lokal auf dem Gerät – bzw. im von dir gewählten Sync-Speicher. Keine Tracker, keine Werbung, keine Konten, keine Serverbetreiber. Der Update-Check ruft einmalig die GitHub-API auf, um die neueste Version zu ermitteln; dabei wird keine personenkoppelbare Information übertragen.

## Feedback

Vorschläge und Probleme können direkt in der App eingereicht werden: Einstellungen -> Vorschläge und Probleme einreichen. Alternativ gern als Issue in diesem Repository.
