# website_test'

steinheim-karate/
├── .github/                   # Optional: Für GitHub-Automatisierungen
├── assets/                    # ZENTRALE RESSOURCEN (teilen sich alle Sprachen)
│   ├── css/
│   │   ├── style.css          # Haupt-Design (inkl. Responsive Media Queries)
│   │   └── gallery.css        # Layout & Popup-Styles für die Fotogalerie
│   ├── js/
│   │   ├── main.js            # Menü-Logik (Mobile Burger-Menü), Formular-Logik
│   │   └── gallery.js         # Lightbox-Skript (GLightbox / PhotoSwipe)
│   ├── docs/                  # PDFs & Dokumente
│   │   ├── de/                # Z. B. aufnahmeantrag.pdf, vereinssatzung.pdf
│   │   └── en/                # Z. B. membership-application.pdf
│   └── images/
│       ├── logo.svg           # Vereinslogo
│       ├── favicon.ico        # Icon für den Browser-Tab
│       ├── hero-banner.jpg    # Großes Startseiten-Foto
│       ├── trainer/           # Fotos des Trainer-Teams
│       │   ├── trainer-1.jpg
│       │   └── trainer-2.jpg
│       └── gallery/           # Alle Ordner für Galerie-Bilder
│           ├── lehrgang-2025/
│           │   ├── cover.jpg  # Vorschaubild für die Galerie-Übersicht
│           │   ├── thumbs/    # Kleine Bildkopien (werden in der Galerie geladen)
│           │   └── full/      # Große Originalbilder (laden erst bei Klick)
│           └── sommerfest-2025/
│               ├── cover.jpg
│               ├── thumbs/
│               └── full/
│
├── de/                        # DEUTSCHE SEITEN
│   ├── index.html             # Startseite
│   ├── trainer.html           # Trainer-Team
│   ├── trainingszeiten.html   # Trainingszeiten & Hallenplan
│   ├── preise.html            # Mitgliedsbeiträge
│   ├── anfahrt.html           # Wegbeschreibung & Anfahrt
│   ├── kontakt.html           # Kontaktformular (über Formspree / Web3Forms)
│   ├── galerie.html           # Galerie-Hauptseite (Übersicht aller Alben)
│   ├── galerien/              # Unterordner für einzelne Alben
│   │   ├── lehrgang-2025.html
│   │   └── sommerfest-2025.html
│   ├── impressum.html         # Rechtliches
│   └── datenschutz.html       # Rechtliches
│
├── en/                        # ENGLISCHE SEITEN
│   ├── index.html             # Home
│   ├── trainers.html          # Trainers
│   ├── training-schedule.html # Schedule
│   ├── pricing.html           # Fees & Pricing
│   ├── directions.html        # How to find us
│   ├── contact.html           # Contact form
│   ├── gallery.html           # Main gallery page
│   ├── galleries/             # Subpages for individual albums
│   │   ├── workshop-2025.html
│   │   └── summer-party-2025.html
│   ├── legal-notice.html      # Legal Notice
│   └── privacy-policy.html    # Privacy Policy
│
├── index.html                 # Pförtner-Datei (Leitet nur weiter auf /de/)
├── CNAME                      # Enthält exakt eine Zeile: www.steinheim-karate.de
├── .gitignore                 # Dateien, die Git ignorieren soll (z. B. .DS_Store)
└── README.md                  # Projekt-Dokumentation
