# Life RPG

Dein Leben als Pixel-RPG: Quests, taegliche Gewohnheiten mit Streaks, XP, Level, Skills, Challenges, Projekte, Zufalls-Quests, Shop mit echten Belohnungen - komplett offline, ohne Account.

## Download und Installation (Android)

1. Oeffne die [neueste Version unter Releases](releases)
2. Lade `LifeRPG.apk` herunter
3. Datei oeffnen und installieren - Android fragt einmalig nach Erlaubnis fuer "Unbekannte Quellen" (normal bei Apps ausserhalb des Play Store)
4. Fertig. Alle Daten bleiben lokal auf dem Geraet

## Updates

- Einfach die neue `LifeRPG.apk` aus den [Releases](releases) laden und drueber installieren
- Updates installieren sich ueber die bestehende App - Spielstand, Einstellungen und Widgets bleiben erhalten
- In der App: Einstellungen -> Updates (GitHub) -> Repository eintragen, dann prueft die App taeglich automatisch und bietet den Download direkt an

## Feedback

Vorschlaege und Probleme koennen direkt in der App eingereicht werden (Einstellungen -> Feedback).

## Datenschutz

Die App speichert alles ausschliesslich lokal (bzw. im von dir gewaehlten Sync-Speicher). Keine Tracker, keine Werbung, keine Konten.

---

# Technische Dokumentation

## Features

- **Onboarding-Assistent** – Held erstellen, Lebensbereiche wählen, ausbalancierte Starter-Quests erhalten
- **Faires XP-System** – XP aus *Dauer x Anstrengung*, Softcap statt hartem Limit: volle XP bis 160/Skill/Tag, halbe bis 320, danach ein Viertel. Der Softcap laesst sich im Held-Tab optional komplett abschalten
- **Daily-Quests mit Streaks** – bis zu +50 % XP-Bonus bei täglicher Konsequenz
- **10 Skills** – Sport, Lernen, Gesundheit, Achtsamkeit, Haushalt, Finanzen, Soziales, Kreativität, Karriere, Abenteuer
- **Zufalls-Quests** – taeglich 2 gewuerfelte Quests aus einem Pool von 81 Ideen (inkl. Lost Places), 2 Gratis-Rerolls pro Tag, 1,5x XP-Bonus
- **Reroll-Shop** – zusaetzliche Rerolls fuer Gold kaufen (1/3/5er-Pakete), gekaufte Rerolls verfallen nie
- **v4.0 Custom-XP** – per Einstellungen freischalten: eigenes XP (1-999) fuer Quests, Unterquests und Challenges
- **v4.0 Level-Belohnungen** – Gold-Boni bei Level-Ups (Gesamt: 50x Level, Skill: 20x Level)
- **v4.0 Shop-Upgrade** – eigene Preise (10-99999) + Freischaltungen (ab Level X / Skill-Level X / nach Quest / nach Challenge)
- **v4.0 Quest-Ketten** – Quests koennen andere Quests als Voraussetzung haben (Schloss bis erfuellt, Zirkel verhindert)
- **v4.0 Abhak-Schutz** – optional: Bestaetigungs-Dialog, 4-stellige PIN oder Fingerabdruck (in der App: Geraete-Sperre via Android-Bridge, im Browser: WebAuthn)
- **v4.0 Tagesquest-Vorlagen** – 90 vordefinierte Dailies pro Skill nachladbar, ohne Duplikate
- **v4.9 Tagesquests** – taeglich wird pro Kategorie (Skill) automatisch eine Daily zur Tagesquest: angepinnt, markiert, doppelte XP - nur aus bewusst aktivierten Dailies (selbst erstellt oder Vorlagen), nicht aus Onboarding-Startern
- **v4.9 Dailies sortierbar** – nach hoechstem/niedrigstem Streak, Kategorie, Name, Neueste
- **v4.9 Einklappbare Kategorien** – optional (Einstellungen): Dailies nach Skill gruppiert ein-/ausklappbar - im Quests- UND Heute-Tab, Tagesquests bleiben oben
- **v4.15 Nachrichten-Archiv** – alle Meldungen (Quests, Level-Ups, Kaefe, Erfolge...) bleiben nachlesbar: HUD-Schriftrolle mit roter Badge, Archiv-Modal, max. 100 Eintraege
- **v4.16 Launcher-Fix** – Widgets behalten immer ihr Layout-Verhaeltnis (fitCenter + Hintergrundfarbe), keine Verzerrung mehr bei Launchern wie Lawnchair
- **v4.17 Custom-Widget** – drittes Widget "Life RPG (Custom)" mit eigenem Designer in der App: 5 frei waehlbare Farben (Hintergrund, Schrift, Akzent, XP-Balken) und 8 ein-/ausschaltbare Anzeige-Elemente
- **Projekte** – grosse Quests mit Unterquests, 25 % Abschlussbonus auf die Summe
- **Challenges** – wiederkehrende Verpflichtungen (1x pro Woche bis taeglich, 1 Woche bis ganzes Jahr). Woche verpasst = Neustart. **XP-Modus frei waehlbar:** automatisch aus Dauer x Anstrengung oder **Custom XP pro Check-in (1–999)**
- **Achievements + Geheimerfolge** – alle geben XP und Gold, geheime werden als "???" angezeigt, bis sie freigeschaltet sind
- **Gold & Belohnungs-Shop** – selbst definierte Belohnungen zu festen Tier-Preisen (Klein/Mittel/Gross/Episch)
- **Backup/Import** – kompletter Spielstand als Text exportieren/importieren (Held-Tab), mit Kopier-Hilfe und 2-Klick-Bestätigung (funktioniert auch in der Android-App, JS-Dialoge werden nativ angezeigt)
- **Themes** – im Held-Tab umschaltbar: Pixel-Retro, Nothing Dark und Nothing Light.
  Der Nothing-Style ist ein kompletter Reskin (nicht nur Farben): kleine Texte in fetter Doto-Dot-Matrix-Schrift (runde Punkte, groesser skaliert fuer Lesbarkeit),
  grosse Ueberschriften in Space Grotesk (Nothing-Headline-Look, fette Grotesk statt Dot-Matrix),
  abgerundete Karten, Pillen-Buttons, runde Icon-Kreise, XP-Balken als Punktreihen, gepunktete Trennlinien,
  Eigene Nothing-Sprite-Sets (sprites_nothing_dark/ + sprites_nothing_light/): gefuellte monochrome Icons
  mit Nothing-Rot als Akzent: komplett rot (Flamme, Blitz, Warnung) sowie zweifarbige Icons mit roten Details
(Trank-Inhalt, Zielscheiben-Kern, Stundenglas-Sand, Wuerfel-Punkt, Karten-Pin, Medaillen-Band).
Die Icons bleiben exakt im generierten Stil (keine Nachbearbeitung der Trennungen).
Achtsamkeit = Lotus-Icon. Hochaufloesende farbige Avatare (gleiche Charaktere wie Pixel, Ritter als Brustportrait).
  Fehlt ein Nothing-Sprite, faellt die App automatisch aufs Pixel-Sprite zurueck.
  Das Rang-Farbsystem (Leicht/Mittel/Schwer/Episch) bleibt in allen Themes erhalten.
- **Android-Widgets** – 2 Homescreen-Widgets mit Live-Daten (Level, XP-Balken, Gold, Streak, Tages-XP, offene Quests):
  - "Life RPG (Pixel)" – Pixel-Retro-Style mit Avatar-Sprite
  - "Life RPG (Nothing)" – Dot-Matrix-Style mit Punkterprozess-Balken
  - Light/Dark automatisch je System-Design, Update bei jedem Speichern in der App
- **Erinnerungen** – Android-Notification um 18 Uhr bei offenen Dailies

## Installation auf Android

### Variante A: APK (native App, empfohlen)
1. Öffne die Live-Vorschau-URL auf deinem Handy und lade `/LifeRPG.apk` herunter
   (oder übertrage die Datei per USB/Cloud)
2. Antippen -> "Installieren" -> ggf. "Unbekannte Quellen zulassen"
3. Beim ersten Start Benachrichtigungen erlauben -> tägliche Erinnerung um 18 Uhr

> **Updates:** Das APK ist mit dem persistenten Key `android/liferpg.keystore` signiert.
> Neuere Versionen installieren sich einfach ueber die alte App - **kein Deinstallieren noetig, alle Daten bleiben erhalten!**

### Variante B: PWA (ohne APK)
1. Ordner `liferpg/` auf einen kostenlosen Host laden (z. B. GitHub Pages, Netlify Drop)
2. In Chrome am Handy oeffnen -> Menü -> "Zum Startbildschirm hinzufuegen"
3. Läuft dann im Vollbild und offline (Service Worker)

## Daten

Alle Daten bleiben **lokal auf deinem Gerät** (localStorage). Kein Konto, kein Server, kein Tracking.
Trotzdem regelmässig ein Backup ueber den Held-Tab machen!

## Projektstruktur

```
liferpg/          Web-App (PWA)
  index.html      UI-Geruest
  style.css       Retro-Pixel-Design
  app.js          Spiellogik (v5)
  manifest.webmanifest, sw.js, icons/, sprites/
android/          Natives Android-Projekt (WebView + Notifications + Widgets)
  build.sh        Kompletter APK-Build (SDK unter /tmp/android-sdk noetig)
  liferpg.keystore Persistenter Signier-Key (NIEMALS loeschen!)
LifeRPG.apk       Fertige, signierte Android-App (v4.4)
tests/            jsdom-Testsuiten (Custom-XP, Softcap/Backup, Reroll-Shop)
```

## APK neu bauen

```bash
# SDK einmalig einrichten (verschwindet nach Session-Neustart):
#   cmdline-tools nach /tmp/android-sdk/cmdline-tools/latest entpacken,
#   dann: sdkmanager "platforms;android-34" "build-tools;34.0.0"
# JDK 11 (javac) + JDK 21 (d8/apksigner) muessen vorhanden sein.
android/build.sh
```

Vorher in `android/AndroidManifest.xml` `versionCode` + `versionName` hochziehen!

## Tests

```bash
mkdir -p /home/user/.cache/jstest && cd /home/user/.cache/jstest && npm init -y && npm i jsdom
export NODE_PATH=/home/user/.cache/jstest/node_modules
node /home/user/tests/test-custom-xp.js        # Custom-XP-Challenges
node /home/user/tests/test-softcap-backup.js   # Softcap-Toggle + Backup/Import
node /home/user/tests/test-reroll-shop.js      # Reroll-Shop
node /home/user/tests/test-themes.js           # Theme-System
node /home/user/tests/test-hist.js             # v4.34: hist-Ableitung, goldSpent, Migration
node /home/user/tests/test-merge.js            # v4.34: Merge-Kern fuer Gerate-Sync
node /home/user/tests/test-sync.js             # v4.34: WebDAV/Google-Transports + Orchestrierung
```

## Sync (v4.34 — fertig)

Spielstand zwischen Geraeten, ohne eigenen Server. Plan + Setup-Anleitungen: `liferpg/docs/plan-sync-ranglisten.md`.

- **Beide Transports waehlbar** (auch gleichzeitig): **WebDAV** (Koofr/Nextcloud/HiDrive/mailbox.org — URL + Benutzer + Passwort) und **Google Drive** (unsichtbarer `appDataFolder`-Bereich deines Google-Accounts, OAuth ueber `liferpg://oauth` Custom Scheme)
- **Offline-first:** App funktioniert ohne Netz exakt wie vorher. Sync = Pull beim App-Start/Resume + gedaempfter Push (5 s) nach Aenderungen. Kein Change = kein Traffic
- **Merge statt Ueberschreiben:** Dailies via `hist`-Vereinigung, Zaehler via max, Loeschungen via Tombstones, Spielstand getrennt von Geraete-Einstellungen (Theme/Widget/PIN wandern nicht)
- Sync-Tab im Backup-Modal (Einstellungen → Backup/Import → SYNC)
- Android: `MainActivity` hat `setAllowUniversalAccessFromFileURLs(true)` + `openUrl`-Bridge + OAuth-Intent-Filter (`liferpg://oauth`, `singleTop`)
- Setup-Kurzanleitungen: Ende des Plan-Dokuments (WebDAV ~5 Min, Google Drive ~15 Min einmalig)

## Custom-Widget-Designer (v4.35 - komplett neu)

Ein Canvas-Renderer fuer Vorschau UND echtes Widget - die Vorschau ist per Definition identisch mit dem Homescreen-Ergebnis:

- **Vorschau = Widget:** Der Designer zeichnet auf Canvas im exakten Widget-Format (500:220, exportiert als 1000x440-PNG). Genau dieses Bitmap geht ans Widget - kein zweiter Renderer in Java mehr (Java zeigt nur noch das PNG, mit Fallback auf das alte Rendering)
- **Layout-Engine ohne Ueberlappung:** Alle Elemente werden mit echten Textmassungen platziert, Schriften schrumpfen automatisch bis sie passen, bei Platzmangel skaliert das ganze Layout runter. Nothing-Stil (Doto 800) kann nichts mehr ueberlappen - gegen alle 256 Element-Kombinationen getestet
- **Slider funktionieren jetzt alle:** Jeder Slider aktualisiert den Wert direkt daneben und zeichnet die Vorschau neu - ohne den Einstellungs-Bereich neu zu bauen (kein Scroll-Sprung, kein Abreissen beim Ziehen); inkl. des bisher toten Profi-Deckkraft-Sliders und des Rahmen-Dicke-Labels
- **Entwurf bis UEBERNEHMEN:** Aenderungen laufen im Entwurf (mit Dirty-Hinweis), das Homescreen-Widget wird nur bei UEBERNEHMEN aktualisiert. Schliessen ohne Uebernehmen = Rueckfrage + verwerfen. Nur die Vorschau ist echtzeit
- **Daten-Updates bleiben:** Quest abhaken etc. rendert das Widget-Bitmap automatisch neu (nur wenn sich etwas geaendert hat)
- Nothing-Icons waehlen automatisch das helle/dunkle Sprite-Set je nach Widget-Hintergrund
- Tests: `test-wdg-layout.js` (44) + `test-wdg-designer.js` (52) - ersetzen die 4 alten Designer-Suiten
- v4.37: Sprites fuer den Widget-Export werden per XHR als **Data-URI** geladen - file-Bilder wuerden den Canvas "tainten" und das PNG scheitern lassen. Kommt kein PNG mit, verwirft Java das alte Bitmap (kein veraltetes Design mehr) und die App meldet sich per Toast
- v4.38: **Runde Ecken / Rahmen als letzte Begrenzung** - der Hintergrund wird als abgerundete Flaeche gezeichnet (Nothing-Stil Ecke 22, Pixel-Stil 8, plus halbe Rahmenbreite), der Rahmenstrich liegt mit seiner Aussenkante exakt auf der Hintergrund-Rundung. Ausserhalb der Rundung (inkl. Ecken) ist das Bitmap transparent - kein kantiger Ueberstand mehr auf irgendeinem Launcher, der Wallpaper scheint durch

## Wichtig: Workspace-Groesse (Snapshot-Limit ~128 MB)

Der Workspace darf ~128 MB nicht ueberschreiten, sonst werden Snapshots unvollstaendig
und Dateien gehen zwischen Sitzungen verloren (ist passiert - deshalb v4.37):

- Aufraeumt am 2026-09-01: `sprites_src/` (verbrauchte Quellbilder der Sprite-Generierung, finalen Sprites liegen in `liferpg/sprites*`), `widget_preview/`, `uploads/` und npm-Cache entfernt - der Workspace ist jetzt ~6 MB schlank
- `android/build/`, `android/assets/` und APK-Kopien sind Build-Artefakte (build.sh erzeugt sie neu)

## Feedback-Formular (v4.39)

In den Einstellungen (Tab "Held", Bereich Daten) gibt es den Button **VORSCHLÄGE & PROBLEME EINREICHEN**:
- In der Android-App oeffnet er das Formular (https://forms.gle/xPwq4eTavzZzyHaw9) im externen Browser ueber die `openUrl`-Bridge
- Im Browser/PWA per `window.open(..., '_blank')`, mit Fallback auf `location.href`
- Tests: `test-feedback.js` (11 Faelle)

## Updates ueber GitHub Releases (v4.46)

**APK gehoert in die Releases, nicht in den Repo-Ordner** (sonst blaest jede Version das Git-Repo auf):

1. Die App prueft automatisch gegen `HackerBoy110010/RPGLife` (voreingestellt, taeglich beim Start) - ein eigenes Repository laesst sich in den Einstellungen eintragen
2. Auf GitHub: Releases -> "Draft a new release" -> Tag `v4.46` -> Titel + Notizen -> `LifeRPG.apk` als Datei anhaengen -> Publish
3. Immer gleiche Dateiname `LifeRPG.apk` und Tag ohne/mit `v`-Praefex (`v4.47`)

Direktlink auf die neueste APK:
`https://github.com/HackerBoy110010/RPGLife/releases/latest/download/LifeRPG.apk`

Hochladen per Kommandozeile (im entpackten Repo-Ordner, einmalig bei GitHub angemeldet):
`git push -u origin master`

Wichtig fuer kuenftige Builds (Checkliste pro Version):
- `android/AndroidManifest.xml`: versionCode + versionName hochziehen
- `liferpg/sw.js`: CACHE-Version hochziehen
- `liferpg/app.js`: `APP_VERSION` hochziehen (dagegen prueft der Update-Checker)
- `bash /home/user/android/build.sh`
- Release anlegen und `LifeRPG.apk` hochladen

Der Signatur-Schluessel (`android/liferpg.keystore`) ist per .gitignore vom Repo ausgeschlossen und muss **privat** gesichert werden - ohne ihn koennen keine Updates fuer die installierte App signiert werden.

## Balancing (falls du schrauben willst)

In `app.js` ganz oben:
- `DUR` / `EFF` – XP-Basiswerte und Multiplikatoren
- `DAILY_SKILL_SOFTCAP` – Softcap pro Skill und Tag (160)
- `STREAK_BONUS_PER_DAY` / `STREAK_BONUS_MAX` – Streak-Boni
- `SIDEQUESTS_PER_DAY` / `REROLLS_PER_DAY` / `SIDEQUEST_BONUS` – Zufalls-Quests
- `PROJECT_BONUS` / `CHALLENGE_BONUS` – Projekt-/Challenge-Boni
- `REWARD_TIERS` – Shop-Preise
