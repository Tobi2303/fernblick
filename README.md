# 🏔️ Fernblick – Naturfotografie Website

Komplette Website für den Verkauf digitaler Naturfotografien.

---

## ✅ Checkliste vor der Veröffentlichung

### 1. Pflichtangaben ausfüllen (in allen HTML-Dateien)

Suche nach folgenden Platzhaltern und ersetze sie überall:

| Platzhalter | Ersetzen durch |
|-------------|----------------|
| `[Nachname]` / `[Last Name]` | Deinen echten Nachnamen |
| `[Straße] [Hausnummer]` | Deine Wohnanschrift |
| `[PLZ] [Stadt]` | Deine Postleitzahl und Stadt |
| `info@fernblick-foto.de` | Deine echte E-Mail-Adresse |
| `DEIN-PAYPAL-NAME` | Dein PayPal.me-Benutzername |

> 🔍 Tipp: Nutze "Suchen & Ersetzen" in einem Texteditor (z.B. VS Code)

### 2. PayPal einrichten

1. Erstelle ein **PayPal Business-Konto** (kostenlos): https://www.paypal.com/de/business
2. Richte dein **PayPal.me-Profil** ein: https://www.paypal.me/
3. Ersetze `DEIN-PAYPAL-NAME` in allen HTML-Dateien durch deinen PayPal.me-Benutzernamen
4. **Nach Zahlungseingang:** Sende den Downloadlink manuell per E-Mail an den Käufer  
   (oder nutze Gumroad.com für automatischen Versand)

### 3. Fotos einfügen

Ersetze in `index.html` die Unsplash-URLs durch deine eigenen Fotos:

```html
<!-- Alt: Unsplash-Platzhalter -->
<img src="https://images.unsplash.com/..." />

<!-- Neu: Dein Foto (hochgeladen ins GitHub-Repository) -->
<img src="fotos/mein-foto.jpg" />
```

Empfohlene Bildgröße für die Galerie: 1200×900px (JPG, ~300KB)  
Empfohlene Bildgröße für den Verkauf: Original-Auflösung (RAW/JPG)

---

## 🚀 Veröffentlichung auf GitHub Pages (kostenlos)

### Schritt 1: GitHub-Account erstellen
Gehe zu https://github.com und erstelle ein kostenloses Konto.

### Schritt 2: Repository erstellen
1. Klicke auf "New repository"
2. Name: `fernblick` (oder dein gewünschter Name)
3. Wähle "Public"
4. Klicke "Create repository"

### Schritt 3: Dateien hochladen
1. Klicke auf "uploading an existing file"
2. Lade alle Dateien hoch:
   - `index.html`
   - `style.css`
   - `agb.html`
   - `impressum.html`
   - `datenschutz.html`
   - `widerruf.html`
   - Deine Fotoordner
3. Klicke "Commit changes"

### Schritt 4: GitHub Pages aktivieren
1. Gehe zu **Settings** → **Pages**
2. Unter "Source": wähle `Deploy from a branch`
3. Branch: `main`, Folder: `/ (root)`
4. Klicke "Save"

### Schritt 5: Website abrufen
Nach 1–2 Minuten ist deine Website erreichbar unter:  
`https://DEIN-GITHUB-USERNAME.github.io/fernblick/`

---

## 📁 Dateistruktur

```
fernblick/
├── index.html          → Startseite mit Galerie & Shop
├── style.css           → Gemeinsames Design
├── agb.html            → Allgemeine Geschäftsbedingungen
├── impressum.html      → Impressum (gesetzlich Pflicht!)
├── datenschutz.html    → Datenschutzerklärung (DSGVO)
├── widerruf.html       → Widerrufsbelehrung
├── fotos/              → Deine Galeriebilder (selbst anlegen)
│   ├── nebelwald.jpg
│   └── ...
└── README.md           → Diese Anleitung
```

---

## ⚖️ Enthaltene Rechtsdokumente

| Dokument | Zweck | Status |
|----------|-------|--------|
| **Impressum** | Gesetzlich verpflichtend (§5 TMG) | ✅ Enthalten – Platzhalter ausfüllen! |
| **AGB** | Kaufbedingungen für digitale Downloads | ✅ Enthalten |
| **Datenschutz** | DSGVO-Konformität | ✅ Enthalten |
| **Widerruf** | Verbraucherrechte, §356 Abs.5 BGB | ✅ Enthalten |

> ⚠️ **Rechtlicher Hinweis:** Diese Dokumente wurden sorgfältig erstellt, ersetzen aber keine Rechtsberatung. Für verbindliche rechtliche Sicherheit empfehle ich eine einmalige Prüfung durch einen Anwalt oder den Einsatz eines zertifizierten Rechtstextdienstleisters (z.B. IT-Recht Kanzlei, Händlerbund).

---

## 💡 Nächste Schritte (optional)

- **Eigene Domain** verbinden: In GitHub Pages Settings unter "Custom domain" eintragen
- **Automatischer Downloadversand**: Gumroad.com (kostenlos, ~10% Provision) einbinden
- **Mehr Fotos**: Weitere Galerie-Einträge in `index.html` hinzufügen (Vorlage copy-pasten)
- **Kontaktformular**: Formspree.io für kostenlose Formularverarbeitung

---

Erstellt mit Claude von Anthropic. Viel Erfolg, Tobias! 🏔️
