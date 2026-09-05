# Life RPG

Dein Leben als Pixel-RPG. Gewohnheiten werden zu Dailies mit Streaks, Aufgaben zu Quests mit XP, und dein Fortschritt landet als Level, Skills und Gold auf dem Homescreen-Widget. Komplett offline, kein Account, keine Tracker – deine Daten gehören dir.

**Download:** [Neueste Version (Releases)](https://github.com/HackerBoy110010/RPGLife/releases) – `LifeRPG.apk` herunterladen, öffnen, installieren. Android fragt einmalig nach der Erlaubnis für Apps außerhalb des Play Store. Updates einfach darüber installieren – Spielstand und Einstellungen bleiben erhalten.

---

## Funktionen

### Quests und Gewohnheiten
- **Quests:** einmalige Aufgaben mit XP aus Dauer × Anstrengung
- **Dailies:** tägliche Gewohnheiten mit Streak-Zahl und bis zu +50 % Streak-Bonus
- **Wochentage:** Dailies nur an bestimmten Tagen aktiv (z. B. Mo–Fr) – der Streak läuft sicher übers Wochenende weiter
- **Quest-Editor:** Titel, Skill, Dauer, Aufwand, Wochentage und Voraussetzungen direkt in der Karte bearbeiten
- **Tagesquests:** jeden Tag pro Kategorie eine Daily als Tagesquest mit doppelten XP – streichbar ohne Nachrücken, oder direkt löschbar
- **Quest-Ketten:** Quests können Voraussetzungen haben und bleiben so lange gesperrt, bis die vorherige erledigt ist
- **Custom-XP:** optional eigene XP-Werte pro Quest, Unterquest und Challenge
- **Vorlagen:** 90 fertige Tagesquest-Vorschläge zum Anklicken
- **Zufalls-Quests:** täglich 2 überraschende Aufgaben mit Bonus-XP, neu würfeln per Reroll

### Charaktere und Packs
- **25 Charaktere** mit einzigartigen Fähigkeiten: Skill-Boni, Gold-Boni, Streak-Verstärkung, Nacht-Boni und mehr
- **4 Seltenheits-Stufen:** Gewöhnlich, Selten, Episch, Legendär – je seltener, desto krasser die Fähigkeit
- **Packs öffnen:** spannende Eskalations-Animationen – jede Stufe durchläuft alle niedrigeren Stufen mit steigender Intensität, Partikeln und Glow
- **Unbegrenztes Leveln:** Duplikate (aus Packs oder Kauf) steigern das Fähigkeits-Level mit harmonischer Kurve – der Zuwachs nimmt ab, hört aber nie auf
- **10er-Pack:** 10 Packs auf einmal mit Sofort-Übersicht (Legendäre kriegen trotzdem ihre Animation)
- **Errungenschafts-Charaktere:** 15 Charaktere werden durch Errungenschaften freigeschaltet (nach Schwierigkeit einsortiert: von „erste Challenge" bis „100 Tage aktiv")
- **6 kaufbare Charaktere:** Kobold, Pirat/in, Fee, Werwolf/in, Vampir/in und Phönix (legendär!)
- **5 neue Errungenschaften:** Untoter (geheim), Eins mit der Natur, Eiskalt, Monument, Zeitzeuge
- **Charakter-Effekt wirkt ab dem Folgetag** – kein Avatar-Hopping für Tagesquests

### Fortschritt und Belohnung
- **XP und Level:** Gesamtlevel mit Level-Boni in Gold
- **10 Skills:** jeder Fortschritt zählt auf den passenden Skill mit eigenem Skill-Level
- **Softcap:** volle XP bis 160 pro Skill und Tag, danach gedrosselt – Dranbleiben schlägt Grinden (abschaltbar)
- **Challenges:** Wochenpensum mit Check-ins, 7× pro Woche bedeutet bei einem verpassten Tag Neustart
- **Projekte:** große Ziele mit Unterquests und Abschlussbonus
- **Shop:** eigene Belohnungen mit selbst gewähltem Preis und Freischalt-Bedingung
- **Errungenschaften:** vier Stufen, darunter über ein Dutzend Geheimerfolge

### Widgets
- Drei Homescreen-Widgets: **Pixel**, **Nothing** und **Custom**
- **Widget-Designer:** eigenes Design mit Farben, Deckkraft, Rahmen, Schrift- und Symbol-Stil
- **Profi-Modus:** jedes Element einzeln anpassbar
- Widgets aktualisieren sich automatisch mit jedem Fortschritt

### Designs
- **5 Stile × 9 Farbsets** = 45 Kombinationen, frei wählbar:
  - **Pixel:** klassischer Retro-Look (Press Start 2P)
  - **Nothing:** minimalistisch mit Dot-Grid und Dot-Balken
  - **Samsung One UI:** riesige Titel, randlose Karten mit Schatten, Pillen-Buttons
  - **Google Material You:** tonale Flächen, Pille hinter dem aktiven Nav-Icon, DM Sans
  - **Apple iPhone:** Liquid Glass (Milchglas mit Blur), Grouped Lists, iOS-Switches, Inter
- **Eigene Icon-Sets je Marke:** One UI dünn umrandet, Material gefüllt, SF-Stil für iPhone
- **Marken-Switches:** iOS-Schalter (grüne Pille), M3-Switch, One-UI-Switch

### Tutorial
- **8 Kapitel** mit Spotlight-Overlay, Pfeilen und erklärenden Texten
- Startet automatisch nach dem Onboarding
- In den Einstellungen jederzeit wieder aufrufbar

### Sync und Daten
- **Geräte-Sync:** Spielstand zwischen Geräten abgleichen – wahlweise über **WebDAV** oder **Google Drive**
- **Merge statt Überschreiben:** Streaks werden vereint, Zähler konservativ zusammengeführt
- **Charakter-Sync:** Fähigkeits-Level werden über Geräte synchronisiert (höheres Level gewinnt)
- **Offline-first:** die App funktioniert immer und überall ohne Netz
- **Backup/Import:** kompletter Spielstand als Text zum Wegspeichern

### Updates
- **Update-Prüfung bei jedem App-Öffnen** gegen dieses Repository
- **System-Benachrichtigung** + **persistentes Banner in jedem Tab** wenn ein Update verfügbar ist
- Download-Button direkt im Banner und in den Einstellungen

### Darüber hinaus
- **Nachrichten-Archiv:** alle Meldungen zum Nachlesen, mit Zähler-Badge
- **App-Sperre:** optional per PIN oder Fingerabdruck
- **Erinnerungen:** tägliche Benachrichtigung bei offenen Quests und gefährdeten Streaks
- **Feedback:** Vorschläge und Probleme direkt aus der App einreichen
- **Sortierung:** Dailies nach Streak, Skill, Name oder Neuheit; Kategorien einklappbar

---

## Versionsverlauf

| Version | Neu |
|---|---|
| **5.1** | Gacha-Grind: höhere Level brauchen mehr Karten (Lv N → N+1 braucht N Karten) · Pack-Animation epischer (Fullscreen-Blur, wachsendes Pack, Stage-Flash, Screen-Shake) · Packs direkt im Shop · Umlaute in der App korrigiert · Tutorial-Positionierung robuster (Tablet-fest) · Tutorial startet nicht mehr bei Bestandsnutzern · Update-Banner persistent · Raritäts-Badges lesbar (Roboto) · Wochentag-Editor ohne Flackern |
| **5.0** | **GROSSES UPDATE:** Charakter-System (25 Charaktere, Fähigkeiten, Packs mit Eskalations-Animationen, Raritäten, 57 Sprites) · Design-System (5 Stile × 9 Farbsets, eigene Marken-Icons, Liquid Glass für iPhone) · Wochentage für Dailies + Quest-Editor · Tutorial (8 Kapitel, Spotlight + Pfeile) · Held-Tab Untertabs · Tagesquest streichen/löschen · Update-Banner |
| **4.51** | Charakter-Sicherung für Bestandsnutzer |
| **4.50** | Sync entschärft (keine Anfragen ohne Änderung, 429-Rückkühlung) |
| **4.46 – 4.49** | Update-System über GitHub Releases |
| **4.35 – 4.45** | Widget-Designer v2 (Canvas-Renderer, Layout-Engine) |
| **4.34** | **Geräte-Sync** über WebDAV und Google Drive mit Merge-Engine |
| **< 4.34** | Quests, Dailies, Streaks, XP/Level/Skills, Tagesquests, Challenges, Projekte, Shop, Errungenschaften, Widgets, Themes, PIN-Sperre, Backup |

---

## Entwicklung

- **Android APK:** `android/build.sh` baut eine signierte APK aus den Web-Assets (PWA-first)
- **PWA:** dieselbe Codebasis läuft auch als Progressive Web App im Browser
- **Tests:** 21 Test-Suiten mit über 700 Tests (`tests/test-*.js`)

## Projektstruktur

```
liferpg/          Web-Assets (HTML, CSS, JS, Sprites, Fonts)
android/          Android-Wrapper (Java, Manifest, Build-Script)
tests/            Test-Suiten (jsdom)
docs/             Pläne und Anleitungen
```

---

*Made with pixel love.*
