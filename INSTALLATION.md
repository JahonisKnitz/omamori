# Omamori — Als iPad-App installieren

## Was du brauchst
- Ein kostenloses GitHub-Konto (github.com)
- Diese 4 Dateien:
  - `garden-game.html`
  - `manifest.json`
  - `omamori-icon.png`
  - `omamori-icon-512.png`

---

## Schritt 1: GitHub Repository erstellen (5 Minuten)

1. Gehe zu **github.com** und logge dich ein
2. Klicke oben rechts auf **"+"** → **"New repository"**
3. Name: `omamori` (oder beliebig)
4. Setze auf **Public**
5. Klicke **"Create repository"**

---

## Schritt 2: Dateien hochladen

1. Im neuen Repository: **"uploading an existing file"** klicken
2. Alle 4 Dateien per Drag & Drop hochladen
3. **Wichtig:** `garden-game.html` in `index.html` umbenennen  
   (oder direkt als `index.html` hochladen)
4. **"Commit changes"** klicken

---

## Schritt 3: GitHub Pages aktivieren

1. Im Repository: **Settings** → **Pages** (links in der Seitenleiste)
2. Source: **"Deploy from a branch"**
3. Branch: **main** → Ordner: **/ (root)**
4. **Save** klicken
5. Nach ~2 Minuten erscheint die URL:  
   `https://DEIN-NAME.github.io/omamori/`

---

## Schritt 4: Als App auf dem iPad installieren

1. Öffne Safari auf dem iPad
2. Gehe zur URL: `https://DEIN-NAME.github.io/omamori/`
3. Tippe auf das **Teilen-Symbol** (Quadrat mit Pfeil nach oben)
4. Scrolle und tippe **"Zum Home-Bildschirm"**
5. Name: **Omamori** — tippe **"Hinzufügen"**

✅ Das Spiel erscheint jetzt als App-Icon auf dem Home-Bildschirm!  
Beim Öffnen startet es vollbild ohne Browser-Leiste — wie eine echte App.

---

## Tipps

- **Aktualisierung:** Lade einfach eine neue `index.html` auf GitHub hoch. Das Spiel aktualisiert sich automatisch beim nächsten Öffnen.
- **Offline:** Das Spiel läuft auch ohne Internet (nach dem ersten Laden).
- **Teilen:** Gib anderen einfach die GitHub-URL — sie können es genauso installieren.
- **Privat halten:** Setze das Repository auf "Private" — dann braucht man einen GitHub-Account zum Zugriff.

---

## Alternative: Lokal per WLAN teilen (ohne Internet)

Falls du kein GitHub willst, kannst du das Spiel auch direkt vom Mac/PC teilen:

```bash
# Im Terminal, im Ordner mit der HTML-Datei:
python3 -m http.server 8080
```

Dann auf dem iPad Safari: `http://[IP-DEINES-MACS]:8080/garden-game.html`  
Die IP-Adresse findest du unter: Systemeinstellungen → WLAN → Details
