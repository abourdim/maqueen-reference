# Maqueen Lite · Reference — v1.0

The technical companion to [**Guide Terrain**](https://abourdim.github.io/maqueen-activities/) (the 85-activity trilingual classroom guide at `github.com/abourdim/maqueen-activities`). This package is a single self-contained HTML reference document plus a screenshot library.

---

## What's in this package

```
maqueen-reference-v1.0/
├── maqueen-reference.html        the deliverable — single HTML, no dependencies
├── README.md                     this file
├── docs/
│   ├── SCREENSHOTS.md            visual index of every screenshot
│   └── CHANGELOG.md              version history
└── screenshots/                  18 PNGs at 2× device-scale factor
    ├── 01-hero.png
    ├── 02-user-guides-panel.png
    ├── 03-family-table-section.png
    ├── 04-anatomy-pinout.png
    ├── 05-universal-mounting.png
    ├── 06-servo-connection.png
    ├── 07-sr04-connection.png
    ├── 08-forklift-kit.png
    ├── 09-loader-kit.png
    ├── 10-beetle-kit.png
    ├── 11-push-kit.png
    ├── 12-assembly-pdf-panel.png
    ├── 13-forklift-bom.png
    ├── 14-bom-{forklift,loader,beetle,push}.png
    └── 15-footer.png
```

---

## Quick start

Open `maqueen-reference.html` in any modern browser. No build step, no server, no dependencies. Works offline. Total size: ≈ 135 KB.

To print: **Ctrl+P** / **Cmd+P** — the print CSS strips the sidebar and reflows for A4.

---

## What the document covers

Fourteen sections, sticky table-of-contents sidebar:

1. **What is it** — positioning, history, target audience
2. **The Maqueen family** — comparison table: Lite vs Plus V2 vs Plus V3
3. **Why Maqueen** — design choices, when to pick this vs alternatives
4. **Onboard hardware** — every component, every connector
5. **Pinout table** — every pin, every API call, on one page
6. **Schematic** — top-down chassis diagram with all pin labels
7. **Getting started** — first MakeCode upload, USB drive flow
8. **Programming environments** — MakeCode / Python / Mind+ / CreateAI
9. **The maqueen API** — every namespace function, with examples
10. **Code recipes** — six things that always work (line-follow, obstacle, dance, etc.)
11. **Mechanic add-ons** — full feature reference for all four kits:
    * Universal hardware reference (M3 mounting holes, servo wiring)
    * Pre-flight checklist + tools list
    * Kid-friendly servo connection close-up (right-way / wrong-way)
    * Kid-friendly SR04 connection close-up (vertical layout, three steps)
    * Per-kit profile (Forklift / Loader / Beetle / Push) — diagram, BoM, assembly steps, calibration angles, code recipe, activity ideas
12. **AI capabilities** — sound classification, image classification, RL
13. **Common pitfalls** — the 10 most-common classroom problems, ordered by frequency
14. **Resources** — every link worth bookmarking, deduplicated

---

## Cross-references to Guide Terrain

The two documents are designed as a deliberate pair:

* **Reference** (this doc) explains *what the parts are* — pinout, schematic, API, mechanism diagrams, BoMs.
* **[Guide Terrain](https://abourdim.github.io/maqueen-activities/)** shows *what to do with them* — 85 activities in FR / EN / AR, with copy-paste code, flowcharts, and graduated challenges.

Cross-pointers live at the end of three high-traffic sections (§9 API, §11 Mechanic, §13 Pitfalls), plus in the hero, the user-guides panel, and the footer. Total of 9 prose mentions and 4 GitHub source links.

API conventions match exactly — same `maqueen.motorRun(maqueen.Motors.All, maqueen.Dir.CW, 150)`, same `maqueen.servoRun(maqueen.Servos.S1, 90)`, etc., as in the parent README.

---

## Verified facts

Every BoM, every URL, every PDF link in the document was verified against DFRobot's official sources before publication. Specifically:

* **Mechanic kit shipping lists** — cross-checked across DFRobot product pages, Element14, Farnell, and Core Electronics distributor listings (which all reproduce the same shipping list)
* **PDF links** — all 5 official PDFs (Master Mechanic + 4 individual kit tutorials + Lite installation guide) confirmed live as of 25 April 2026
* **Wiki URLs** — all 4 kit wiki pages confirmed live
* **API spelling** — verified against the [`pxt-maqueen` GitHub source](https://github.com/DFRobot/pxt-maqueen)

---

## Statistics

* **~135 KB** single self-contained HTML file
* **132 external links** — all verified live as of 25 April 2026
* **8 embedded SVG diagrams** — anatomy, pinout, mounting, servo, SR04, forklift, loader, beetle, push
* **14 sections**, sticky TOC sidebar
* **5 official PDFs** linked (Master + 4 kit tutorials + Lite installation)
* **4 BoMs** with verified shipping lists
* **0 dependencies**, **0 fonts loaded from CDN** (system fonts only)
* **MIT licensed**

---

## Aesthetic notes

Cream paper background (`#f3ece0` / `#ebe1cf`), ink (`#1c2230`), terracotta accents (`#b8523a`), teal (`#2f6b6e`). Fonts: Cormorant Garamond (serif headings), Spectral (body), JetBrains Mono (code). Zellige-inspired strip in the header.

The aesthetic is intentionally in the same family as Guide Terrain's "Zellige" theme — visual continuity for users who move between the two documents.

---

## License

MIT. Free to use, modify, redistribute. Same licence as the parent repo.

If you fork or extend, a credit-link back to either Guide Terrain or this Reference is appreciated but not required.

---

*Compiled April 25, 2026 — v1.0*
