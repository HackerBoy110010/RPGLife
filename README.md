# Life RPG

Dein Leben als Pixel-RPG. Gewohnheiten werden zu Dailies mit Streaks, Aufgaben zu Quests mit XP, und dein Fortschritt landet als Level, Skills und Gold auf dem Homescreen-Widget. Komplett offline, kein Account, keine Tracker - deine Daten gehoeren dir.

**Download:** [Neueste Version (Releases)](https://github.com/HackerBoy110010/RPGLife/releases) - `LifeRPG.apk` herunterladen, oeffnen, installieren. Android fragt einmalig nach der Erlaubnis fuer Apps ausserhalb des Play Store. Updates einfach drueber installieren - Spielstand und Einstellungen bleiben erhalten.

---

## Funktionen

### Quests und Gewohnheiten
- **Quests:** einmalige Aufgaben mit XP aus Dauer x Anstrengung
- **Dailies:** taegliche Gewohnheiten mit Streak-Zahl und bis zu +50% Streak-Bonus
- **Tagesquests:** jeden Tag wird pro Kategorie eine Daily zur Tagesquest mit doppelten XP - oben angepinnt, mit eigenem Badge
- **Quest-Ketten:** Quests koennen Voraussetzungen haben und bleiben so lange gesperrt, bis die vorherige erledigt ist
- **Custom-XP:** optional eigene XP-Werte pro Quest, Unterquest und Challenge statt automatischer Berechnung
- **Vorlagen:** 90 fertige Tagesquest-Vorschlaege (9 pro Skill) zum Anklicken
- **Zufalls-Quests:** taeglich 2 ueberraschende Aufgaben mit Bonus-XP, neu wuerfeln per Reroll (taeglich gratis, Nachschub kaufbar)

### Fortschritt und Belohnung
- **XP und Level:** Gesamtlevel mit Level-Boni in Gold
- **10 Skills:** jeder Fortschritt zaehlt auf den passenden Skill mit eigenem Skill-Level
- **Softcap:** volle XP bis 160 pro Skill und Tag, danach gedrosselt - Dranbleiben schlaegt Grinden (abschaltbar)
- **Challenges:** Wochenpensum mit Check-ins, 7x pro Woche bedeutet bei einem verpassten Tag Neustart
- **Projekte:** grosse Ziele mit Unterquests und Abschlussbonus
- **Shop:** eigene Belohnungen mit selbst gewaehltem Preis und Freischalt-Bedingung (Level, Skill, Quest oder Challenge)
- **Errungenschaften:** vier Stufen, darunter ueber ein Dutzend Geheimerfolge

### Widgets
- Drei Homescreen-Widgets: **Pixel**, **Nothing** und **Custom**
- **Widget-Designer:** eigenes Design mit Farben (HSV-Picker + Palette), Deckkraft-Schaltern, Rahmen, Schrift- und Symbol-Stil - die Vorschau zeigt exakt das fertige Widget (gleicher Renderer), Uebernehmen laedt es auf den Homescreen
- **Profi-Modus:** jedes Element einzeln in Farbe, Groesse, Deckkraft, Stil und Symbol
- Runde Ecken: der Rahmen ist die aeussere Begrenzung, dahinter scheint der Hintergrund durch - sauber auf jedem Launcher
- Widgets aktualisieren sich automatisch mit jedem Fortschritt

### Sync und Daten
- **Geraete-Sync:** Spielstand zwischen Geraeten abgleichen - wahlweise ueber **WebDAV** (Koofr, Nextcloud, HiDrive u. a.) oder **Google Drive** (unsichtbarer App-Bereich deines Accounts)
- **Merge statt Ueberschreiben:** Streaks werden vereint, Zaehler konservativ zusammengefuehrt, Loeschungen bleiben Loeschungen - kein Datenverlust bei Parallel-Nutzung
- **Offline-first:** die App funktioniert immer und ueberall ohne Netz, Sync ist reine Ergaenzung
- **Backup/Import:** kompletter Spielstand als Text zum Wegspeichern

### Updates
- **Update-Pruefung bei jedem App-Oeffnen** gegen dieses Repository (Repository ist voreingestellt, eigenes moeglich)
- **Benachrichtigung** sobald ein neues Release verfuegbar ist - einmalig pro Version
- Download-Button direkt in den Einstellungen, Installation drueber ohne Datenverlust

### Darueber hinaus
- **Themes:** Pixel, Nothing Dark, Nothing Light (an Nothing OS angelehnt)
- **Nachrichten-Archiv:** alle Meldungen zum Nachlesen, mit Zaehler-Badge
- **App-Sperre:** optional per PIN oder Fingerabdruck (Abhak-Schutz)
- **Erinnerungen:** taegliche Benachrichtigung um 18 Uhr bei offenen Quests und gefaehrdeten Streaks
- **Feedback:** Vorschlaege und Probleme direkt aus der App einreichen
- **Sortierung:** Dailies nach Streak, Skill, Name oder Neuheit; Kategorien einklappbar

---

## Versionsverlauf

Neue Funktionen werden hier pro Version ergaenzt. Aeltere Aenderungen vor 4.34 sind zusammengefasst.

| Version | Neu |
|---|---|
| **4.49** | Update-Check robuster: Clone-URLs mit `.git` und vollstaendige GitHub-Links werden automatisch bereinigt; konkretere Fehlermeldung bei Problemen |
| **4.48** | Update-Pruefung bei **jedem** App-Oeffnen (inkl. Rueckkehr aus dem Hintergrund, gedrosselt) und **System-Benachrichtigung** bei neuem Release (einmalig pro Version) |
| **4.47** | Standard-Repository voreingestellt - Update-Check laeuft ohne jegliche Konfiguration |
| **4.46** | **Update-System ueber GitHub Releases:** Repository eintragbar, taegliche Pruefung, Download-Button in den Einstellungen |
| **4.45** | Kontrast-Systematik: Schrift auf Akzent-Farben folgt einer eigenen Variable - Nachrichten-Zaehler und Tab-Beschriftungen jetzt dunkel auf Gold statt weiss |
| **4.44** | Tagesquest-Badge sitzt immer als eigene Zeile ganz vorne in der Karte - identisch auf jedem Geraet und Format |
| **4.43** | Deterministische Zeilenausrichtung in Ueberschriften, Titeln und Meta-Zeilen (unabhaengig von Geraet, Schriftzoom und Querformat) |
| **4.42** | Layout-Auffrischung nach Geraete-Drehung (WebView-Reflow) und feste Zeilenhoehen in Quest-Karten |
| **4.41** | Tagesquest-Badge lesbar gemacht (dunkle Schrift auf Gold) und Meta-Reihe flex-zentriert |
| **4.40** | HUD-Muenze und statische Icons wechseln korrekt zum Theme-Sprite (Nothing-Symbole im Nothing-Stil) |
| **4.39** | Feedback-Formular fuer Vorschlaege und Probleme direkt in den Einstellungen |
| **4.38** | Runde Ecken: Rahmen als letzte Begrenzung des Widgets, transparente Ecken auf jedem Launcher |
| **4.35 - 4.37** | Widget-Designer komplett neu: ein Canvas-Renderer fuer Vorschau UND Widget (identisch), Layout-Engine ohne Ueberlappung, Entwurfs-Modus mit Uebernehmen, Sprites als Data-URIs |
| **4.34** | **Geraete-Sync** ueber WebDAV und Google Drive mit Merge-Engine (Streak-Vereinigung, Tombstones, Gold-Ableitung), Sync-Tab im Backup-Modal |
| **< 4.34** | Quests, Dailies, Streaks, XP/Level/Skills, Tagesquests, Challenges, Projekte, Zufalls-Quests, Shop, Errungenschaften, Widgets, Themes, Nachrichten-Archiv, PIN-Sperre, Backup/Import |

---

## Datenschutz

Die App speichert alles ausschliesslich lokal auf dem Geraet - bzw. im von dir gewaehlten Sync-Speicher. Keine Tracker, keine Werbung, keine Konten, keine Serverbetreiber. Der Update-Check ruft einmalig die GitHub-API auf, um die neueste Version zu ermitteln; dabei wird keine personenkoppelbare Information uebertragen.

## Feedback

Vorschlaege und Probleme koennen direkt in der App eingereicht werden: Einstellungen -> Vorschlaege und Probleme einreichen. Alternativ gern als Issue in diesem Repository.
