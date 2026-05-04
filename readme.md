# MG – Networking

**Softwareentwicklung • Technical Scrum Master (PSM II) • Agile Delivery**

Willkommen im Repository der offiziellen Website von **MG – Networking**.  
Dieses Projekt dient als persönliche Landing Page für meine freiberuflichen Leistungen in den Bereichen Softwareentwicklung, Agile Coaching und technischer Prozessoptimierung.

Die Seite wird über **GitHub Pages** bereitgestellt und basiert vollständig auf **HTML + SCSS**, ohne Jekyll‑Theme oder Markdown‑Rendering.

---

## 🚀 Features

- Modernes, responsives HTML‑Layout  
- Hero‑Section, Leistungen, Pakete, About & Zertifizierungen  
- Sticky Navigation  
- Individuelles Branding (Farben, Typografie, Logo)  
- SCSS‑Struktur mit automatischer Kompilierung durch GitHub Pages  
- Saubere, modulare Code‑Struktur  

---

## 📁 Projektstruktur

```
/
├── index.html              # Hauptseite (Landing Page)
├── _config.yml             # GitHub Pages Konfiguration (HTML + SCSS)
└── assets/
    ├── img/                # Bilder, Icons, Logos
    ├── scss/               # SCSS-Quellcode
    │   └── style.scss
    └── css/
        └── style.css       # Automatisch generiert aus SCSS
```

---

## 🧩 Technologien

- **GitHub Pages** (Deployment)  
- **HTML5** (Struktur)  
- **SCSS** (Styles, kompiliert nach CSS)  
- **Jekyll SCSS Pipeline** (nur für SCSS, kein Theme)  
- **PNG/JPG/SVG Assets**

---

## ⚙️ SCSS Build Setup

GitHub Pages kompiliert SCSS automatisch.  
Die `_config.yml` ist entsprechend konfiguriert:

```yaml
theme: null
markdown: null

sass:
  sass_dir: assets/scss
  style: compressed

exclude:
  - README.md
```
SCSS‑Dateien aus assets/scss werden automatisch nach assets/css kompiliert.

---

## 📬 Kontakt

**MG – Networking**  
Wendlingen am Neckar, Deutschland  

📧 E-Mail: michael.gaertner\[at\]mg-networking.com
🔗 LinkedIn: [https://linkedin.com/in/mgaert]

---

## 📄 Lizenz

Dieses Projekt steht unter der **MIT License**.  
Details findest du in der Datei