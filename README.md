# NOVA – KI Ernährungscoach PWA

## Dateien in diesem Ordner

| Datei | Beschreibung |
|-------|-------------|
| `index.html` | Die komplette NOVA App |
| `manifest.json` | PWA-Konfiguration (Name, Icon, Farben) |
| `sw.js` | Service Worker (Offline-Support) |
| `icon-192.png` | App-Icon klein (Homescreen) |
| `icon-512.png` | App-Icon gross (Splash Screen) |

---

## Schritt 1 – GitHub Account erstellen (kostenlos)

1. Gehe auf **github.com**
2. Klicke "Sign up" und erstelle einen kostenlosen Account
3. E-Mail bestätigen

---

## Schritt 2 – Neues Repository erstellen

1. Klicke oben rechts auf **"+"** → **"New repository"**
2. Repository Name: `nova-app`
3. Auf **"Public"** stellen (wichtig für GitHub Pages)
4. Klicke **"Create repository"**

---

## Schritt 3 – Alle Dateien hochladen

1. Im neuen Repository klicke **"uploading an existing file"**
2. Alle 5 Dateien aus diesem Ordner per Drag & Drop reinziehen:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Unten auf **"Commit changes"** klicken

---

## Schritt 4 – GitHub Pages aktivieren

1. Im Repository oben auf **"Settings"** klicken
2. Links im Menü: **"Pages"**
3. Unter "Branch": **"main"** auswählen, Ordner **"/ (root)"**
4. Auf **"Save"** klicken
5. Nach ca. 1-2 Minuten erscheint deine URL:
   `https://DEIN-USERNAME.github.io/nova-app/`

---

## Schritt 5 – Als App auf dem iPhone installieren

1. Öffne die URL aus Schritt 4 in **Safari** (nicht Chrome!)
2. Tippe unten auf das **Teilen-Symbol** (Quadrat mit Pfeil nach oben)
3. Scrolle und tippe auf **"Zum Home-Bildschirm"**
4. Name lassen oder anpassen → **"Hinzufügen"**
5. NOVA erscheint jetzt als App auf deinem Homescreen!

---

## Schritt 6 – Als App auf Android installieren

1. Öffne die URL in **Chrome**
2. Tippe oben rechts auf die **drei Punkte** (Menü)
3. Tippe auf **"App installieren"** oder **"Zum Startbildschirm hinzufügen"**
4. Bestätigen → fertig!

---

## API-Key einbinden (OpenAI)

Sobald du deinen OpenAI API-Key hast, wird er direkt in die `index.html` eingebaut.
Danach einfach die `index.html` erneut auf GitHub hochladen (alte Datei überschreiben) –
die App aktualisiert sich automatisch beim nächsten Öffnen.

---

## Wichtige Hinweise

- **Safari auf iOS** ist Pflicht für die Installation (Chrome funktioniert auf iPhone nicht)
- Die App funktioniert **offline** für alle bereits geladenen Inhalte
- **Mikrofon-Zugriff**: Beim ersten Starten fragt das iPhone nach Erlaubnis – erlauben!
- Updates: Einfach neue `index.html` auf GitHub hochladen, App neu öffnen

---

## Kosten

- GitHub Pages: **kostenlos**
- Domain (optional): ca. 10-15€/Jahr für nova-app.de
- OpenAI API für 101 Videos: **unter 10 USD**

---

*NOVA v3 – Entwickelt mit Claude (Anthropic)*
