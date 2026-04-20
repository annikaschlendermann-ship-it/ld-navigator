# L&D Navigator

**Live:** [annikaschlendermann-ship-it.github.io/ld-navigator](https://annikaschlendermann-ship-it.github.io/ld-navigator/)

Ein interaktives, mobil-optimiertes Referenz-Tool für Learning & Development — von der Lernbedarfsanalyse bis zur skalierten Lernkultur.

---

## Was ist der L&D Navigator?

Der L&D Navigator ist eine Single-Page-Anwendung (kein Framework, kein Backend, kein Login) die als persönliches Referenz- und Lerntool für L&D-Praktiker:innen entwickelt wurde. Die gesamte Anwendung besteht aus einer einzigen `index.html` Datei.

**Kernidee:** Alle wichtigen Frameworks, Modelle, Checklisten und Best Practices aus dem L&D-Bereich — an einem Ort, jederzeit auf dem Handy verfügbar.

---

## Inhalt

### Phase 1 — Analysieren
| Schritt | Inhalt |
|---------|--------|
| S1 | Organisationsziele verstehen |
| S2 | Stakeholder-Interviews führen |
| S3 | Daten multi-methodisch erheben |
| S4 | Gap-Analyse & Priorisierung |

### Phase 2 — Designen
| Schritt | Inhalt |
|---------|--------|
| S5 | Programmarchitektur & didaktisches Design (Bloom, Gagné, Merrill, Mayer, UDL, Blended Learning) |
| S6 | Zielgruppen-Pfade & Personalisierung (Learner Personas, Onboarding, Skills-basierte Pfade) |
| S7 | Build vs. Buy & Vendor-Management (Entscheidungsmatrix, Authoring Tools, Content Libraries) |
| S8 | Rollout-Kommunikation & Stakeholder-Management (WIIFM, Resistance Management) |

### Phase 3 — Messen
| Schritt | Inhalt |
|---------|--------|
| S9 | Erfolgsmessung nach Kirkpatrick (4 Level-Kacheln mit KPIs, Messmethoden, Benchmarks, Challenges) |
| S10 | KPIs definieren und tracken (6 KPI-Kategorien: Activity, Learning, Transfer, Business Impact, ROI, Talent) |
| S11 | Feedback-Loop etablieren |
| S12 | Lernkultur skalieren |

### Praxis-Kompetenzen
- **P1** — Programme & Trainings entwickeln
- **P2** — Coaching & Workshops
- **BP** — Best Practices: Coaching, Weiterentwicklung & Teamentwicklung
- **P3** — eLearning & LMS
- **P4** — Live Trainings (Präsenz & Virtuell)
- **P5** — Compliance & Projektmanagement

### Tools & Entscheidung
- **UC** — Use Cases (6 Praxis-Szenarien)
- **DT** — Decision Tree (interaktiver Format-Auswahl-Guide)
- **ML** — Moderne Lernmethoden (14 Methoden in 4 Kategorien)

### Interview & Assessment
- **AC** — Assessment Center Vorbereitung (13 Szenarien: Case Study, Needs Analysis, Roleplay, Pitch)
- **CM** — Change Management (Cialdini 7 Prinzipien, Kotter, ADKAR, Kübler-Ross, Bridges, Lewin, Nudge Theory, COM-B)

### Referenz
- **RS** — Research & Neurowissenschaft (9 Papers)
- **G** — Glossar (50+ Fachbegriffe mit Suchfunktion und Filter)
- **R** — Quellen & Links

---

## Features

- **Vollständig offline** nach dem ersten Laden (kein Backend, keine API)
- **Mobil-optimiert** — Hamburger-Navigation, Touch-freundlich, als App auf den Homescreen legbar
- **Zweisprachig** — DE/EN Toggle für Navigation und UI
- **Interaktive Kacheln** — alle Inhalte aufklappbar, kein Scrollmonster
- **Fortschrittsbalken** — trackt besuchte Schritte (S1–S12)
- **Decision Tree** — interaktiver Format-Auswahl-Guide mit 6 Szenarien
- **Glossar** — Suche + Filter nach Typ (Modell/Konzept/Methode) und Bereich (Analysieren/Designen/Messen/Change/Praxis)

---

## Technologie

| Aspekt | Detail |
|--------|--------|
| Stack | Reines HTML, CSS, JavaScript — keine Dependencies |
| Schriften | Google Fonts: Syne, DM Sans |
| Hosting | GitHub Pages (Branch: `main`, Root: `/`) |
| Datei | Eine einzige `index.html` (~500KB) |
| Browser | Alle modernen Browser, iOS Safari, Android Chrome |

---

## Lokale Nutzung

Die Datei kann direkt im Browser geöffnet werden — kein Server nötig:

```bash
# Option 1: Direkt öffnen
open index.html

# Option 2: Lokaler Server (optional)
python3 -m http.server 8000
# → http://localhost:8000
```

---

## Updates deployen

1. `index.html` lokal anpassen oder via Claude bearbeiten lassen
2. Datei auf GitHub hochladen: [Repository Upload](https://github.com/annikaschlendermann-ship-it/ld-navigator/upload/main)
3. Bestehende `index.html` ersetzen → **Commit changes**
4. Nach ~1–2 Minuten ist die live Version aktualisiert

---

## Wissenschaftliche Grundlage

Die Inhalte basieren auf etablierten L&D-Frameworks und Forschungsergebnissen:

- **Kirkpatrick** (1954) — 4-Ebenen-Evaluationsmodell
- **70-20-10** (McCall, Lombardo & Morrison, 1988) — Lernquellen-Framework
- **Bloom's Taxonomy** (Anderson & Krathwohl, 2001) — Kognitive Lernziele
- **Gagné's Nine Events** (1965) — Instruktionsdesign-Sequenz
- **Mayer** (2001) — Multimedia-Lernprinzipien
- **Merrill** (2002) — First Principles of Instruction
- **Edmondson** (1999) — Psychological Safety
- **Blume et al.** (2010) — Transfer of Training Meta-Analyse
- **Karpicke & Blunt** (2011) — Retrieval Practice
- **Cialdini** (1984/2016) — Influence Principles
- **Prosci/Hiatt** — ADKAR Change Model
- **Kotter** (1996) — 8-Step Change Model
- **Kübler-Ross** (1969) — Change Curve
- **Bridges** (1991) — Transitions Model
- **Michie et al.** (2011) — COM-B Behaviour Change Model
- **Thaler & Sunstein** (2008) — Nudge Theory

---

## Entwickelt mit

- [Claude](https://claude.ai) (Anthropic) — Inhalt, Code und Iterationen
- [GitHub Pages](https://pages.github.com) — kostenloses Hosting

---

*Entwickelt als persönliches Referenz-Tool für L&D-Praxis und Assessment-Vorbereitung.*
