# Maqueen Lite · Reference — v1.1

The technical companion to [**Guide Terrain**](https://abourdim.github.io/maqueen-activities/) (the 85-activity trilingual classroom guide at `github.com/abourdim/maqueen-activities`). Single self-contained HTML reference + screenshot library.

## What's new in v1.1

* **§ 11 — The 16 official examples (catalog)** — every example from the [DFRobot ROB0148 wiki](https://wiki.dfrobot.com/rob0148-en/), summarised at the API level. Each entry has: ID, title, what it teaches, hardware involved, API surface (as compact teal tags), and direct links to both the original wiki page and the Guide Terrain implementation. Total: 16 entries plus a "reading order — what to teach when" pedagogical sequence at the end.
* Section numbering shifted: Mechanic moved to § 12, AI to § 13, Pitfalls to § 14, Resources to § 15. Sticky TOC sidebar updated.
* New CSS component `.wiki-row` — italic terracotta number, Cormorant title, prose summary, teal API tags, dotted-underline links.
* 4 new screenshots (16-19): the new section's intro, a single-card close-up, the reading-order subsection, and the updated 15-entry sidebar TOC.

## Package contents

```
maqueen-reference-v1.1/
├── maqueen-reference.html        the deliverable — single HTML, 0 deps, ≈ 151 KB
├── README.md                     this file
├── LICENSE                       MIT
├── docs/
│   ├── SCREENSHOTS.md            visual index of every screenshot
│   ├── CHANGELOG.md              v1.0 → v1.1 history
│   └── gallery.html              browsable visual index
└── screenshots/                  22 PNGs at 2× device-scale factor
```

## Quick start

Open `maqueen-reference.html` in any modern browser. No build step, no server, no dependencies. Works offline. **Ctrl+P / Cmd+P** for clean A4 printing.

## What the document covers

Fifteen sections, sticky TOC sidebar:

1. What is it
2. The Maqueen family (Lite vs Plus V2 vs Plus V3)
3. Why Maqueen
4. Onboard hardware
5. Pinout table
6. Schematic
7. Getting started
8. Programming environments (MakeCode / Python / Mind+ / CreateAI)
9. The maqueen API
10. Code recipes (six things that always work)
11. **The 16 official examples (catalog)** — new in v1.1
12. Mechanic add-ons (full feature reference)
13. AI capabilities
14. Common pitfalls
15. Resources

## Cross-references to Guide Terrain

The two documents are designed as a deliberate pair:

* **Reference** (this doc) explains *what the parts are* — pinout, schematic, API, mechanism diagrams, BoMs, and the official examples catalog.
* **[Guide Terrain](https://abourdim.github.io/maqueen-activities/)** shows *what to do with them* — 85 activities in FR / EN / AR with copy-paste code, flowcharts, graduated challenges. It includes faithful trilingual implementations of all 16 official examples (look for the **📘 Officiel** category) plus 70 creative extensions.

The new § 11 catalog is explicit about this: every entry links to *both* the wiki source AND Guide Terrain.

## Verified facts

Every link, BoM, and PDF reference was verified live as of 2026-04-25. The API spelling matches `pxt-maqueen` source. The wiki-examples catalog maps directly onto the 16 numbered tutorials at https://wiki.dfrobot.com/rob0148-en/ — example IDs and learning targets are preserved; descriptions are paraphrased in the reference doc's own technical voice.

## Statistics

* **151 KB** single self-contained HTML file
* **15 sections**
* **8 embedded SVG diagrams**
* **5 official PDFs** linked
* **4 BoMs** with verified shipping lists
* **16 official wiki examples** catalogued with API tags and dual links
* **0 dependencies**
* **MIT licensed**

## License

MIT — same as the parent repo. See `LICENSE`.

---

*v1.1 · 2026-04-25*
