# Changelog

All notable changes to the Maqueen Lite Reference document.

---

## [1.1.0] — 2026-04-25

The wiki-examples catalog release.

### Added

#### § 11 — The 16 official examples (catalog)

A new top-level section between Code recipes (§ 10) and Mechanic add-ons (§ 12). Catalogues every numbered example from the DFRobot ROB0148 wiki at `wiki.dfrobot.com/rob0148-en`. Each entry includes:

* **Italic Cormorant ID** (01 through 16)
* **Title** matching the wiki's title
* **Paraphrased summary** in the reference doc's own technical voice
* **API surface tags** — compact teal pills naming the relevant pins, namespaces, and method calls (e.g. `P16 IR`, `IR_Read`, `motorRun`)
* **Two links** — direct to the official wiki page, and to the Guide Terrain implementation
* The 16 entries cover: getting started, IR remote (×2), line-tracking (×2), motor control, RGB ambient, ultrasonic distance, LED flash, IR key codes, line-sensor read, ultrasonic obstacle avoidance, light-following, wireless GamePad, servo, product info

A "Reading order — what to teach when" subsection at the end groups the 16 entries into four pedagogical phases (setup & smoke test → single-component reads → single-component drives → combined behaviours).

A "Where to find the actual code" callout at the top of the section explicitly directs readers to either the wiki or to Guide Terrain for working implementations — keeping the reference doc focused on its companion role.

#### CSS

* New `.wiki-cat` and `.wiki-row` component styles
* Italic Cormorant numbering, terracotta left-border accent, teal API tags
* Responsive: collapses gracefully below 640 px viewport

#### Screenshots (4 new)

* `16-wiki-examples-intro.png` — heading, callout, first 4 example cards
* `17-wiki-card-detail.png` — single card close-up showing layout (entry #06, Read ultrasonic distance)
* `18-wiki-reading-order.png` — the 4-phase teaching sequence at the end
* `19-toc-15-entries.png` — updated sticky sidebar with all 15 sections

### Changed

#### Section numbering

The four sections after Code recipes shifted by one:

* Mechanic add-ons: § 11 → **§ 12**
* AI capabilities: § 12 → **§ 13**
* Common pitfalls: § 13 → **§ 14**
* Resources: § 14 → **§ 15**

The sticky TOC sidebar reflects all 15 entries in order. All section anchors and cross-references (`#mechanic`, `#ai`, `#pitfalls`, `#resources`) remained unchanged — old deep-links continue to work.

#### Document size

134 KB → 151 KB (+ 17 KB for the new section's content + CSS).

---

## [1.0.0] — 2026-04-25

Initial packaged release. See `v1.0` package for the original changelog. Major content:

* 14 sections with sticky TOC, print CSS, copy buttons, cream / ink / terracotta / teal aesthetic
* Hero, user-guides quick-access panel, family comparison table
* Top-down chassis schematic with every pin labelled
* Universal mounting reference + servo wiring diagram
* Kid-friendly servo and SR04 connection close-ups (the SR04 redesigned from side-by-side to vertical layout for teaching clarity)
* Per-kit profiles for all four Mechanic kits with verified BoMs
* AI capabilities, common pitfalls, full resources list
* 132 verified external links
* 8 embedded SVG diagrams
* 5 official PDFs linked
* 18 screenshots at 2× DPI
* MIT licensed
