# 🏠 HAUSaufgaben

**Die Familien-App für Haushalt, Einkauf & Organisation**

Eine Progressive Web App (PWA) – installierbar auf iPhone, Android & Desktop direkt aus dem Browser.

---

## ✨ Features

- **📌 Aufgaben** – Erstellen, zuweisen, abhaken. Filter nach Familienmitglied.
- **🛒 Einkaufsliste** – Notizblock-Stil. Antippen = durchstreichen. Einfach & schnell.
- **🍽️ Essensplan** – Woche planen + Familienmitglieder können Wünsche äußern.
- **📅 Familienkalender** – Geteilte Termine mit Farbcodierung.
- **🎤 Diktierfunktion** – Text eingeben, App erkennt automatisch ob Einkauf oder Aufgabe.
- **🏆 Familien-Ranking** – Wer hat am meisten erledigt?
- **💾 Offline-fähig** – Daten werden lokal gespeichert (localStorage).

---

## 📱 Installieren

### iPhone (Safari)
1. Öffne die App-URL in Safari
2. Tippe auf **Teilen** (↑)
3. Wähle **Zum Home-Bildschirm**
4. Fertig – die App erscheint als Icon!

### Android (Chrome)
1. Öffne die App-URL in Chrome
2. Tippe auf **Menü** (⋮) → **App installieren**

### Desktop
1. In Chrome/Edge erscheint ein Install-Icon in der Adressleiste

---

## 🚀 Deployment

### GitHub Pages (empfohlen)
1. Pushe dieses Repo zu GitHub
2. Gehe zu **Settings → Pages**
3. Wähle Branch: `main`, Folder: `/ (root)`
4. Deine App ist live unter `https://username.github.io/HAUSaufgaben/`

### Lokal testen
```bash
# Einfachen Server starten (PWA braucht HTTPS/localhost)
npx serve .
# oder
python3 -m http.server 8000
```

---

## 📁 Projektstruktur

```
HAUSaufgaben/
├── index.html      ← Komplette App (React + Babel, alles in einer Datei)
├── manifest.json   ← PWA-Manifest (Name, Icons, Theme)
├── sw.js           ← Service Worker (Offline-Cache)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

---

## 🛠 Technologie

- **React 18** via CDN (kein Build-Step nötig!)
- **Babel** für JSX-Transpilation im Browser
- **localStorage** für Datenpersistenz
- **Service Worker** für Offline-Support
- **PWA-Manifest** für App-Installation
- **CSS Animations** für flüssige Übergänge
- **Google Fonts** (DM Sans, Playfair Display, Caveat)

Kein Node.js, kein npm, kein Build-Prozess – einfach hochladen und fertig.

---

## 📄 Lizenz

MIT – Frei zur Nutzung und Weiterentwicklung.

---

Gebaut mit ❤️ für Familien.
