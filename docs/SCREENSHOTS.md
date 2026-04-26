# Screenshots — visual index

Every screenshot was captured at **2× device-scale factor** from `maqueen-reference.html` rendered in headless Chromium at 1280×1000 viewport. PNGs stay sharp when embedded in documents, README files, slides, or printed handouts.

---

## Front of document

### `01-hero.png` — Hero block
Cream background, terracotta kicker, Cormorant title `Maqueen Lite · Reference`. Kicker explicitly names the relationship: *"DFRobot ROB0148 · Reference · companion to Guide Terrain"*.

### `02-user-guides-panel.png` — User-guides quick-access panel
Seven rows of clickable links: Lite, Plus V2, Plus V3, Mechanic kits, MakeCode editor, Guide Terrain (sibling), Also by author.

### `03-family-table-section.png` — Family comparison table
Lite vs Plus V2 vs Plus V3 — the canonical "which Maqueen do I buy?" answer.

### `19-toc-15-entries.png` — Sidebar TOC (v1.1)
The sticky table-of-contents sidebar showing all 15 sections after the wiki-examples section was added. Visual confirmation that the new section slots in between Code recipes and Mechanic add-ons.

---

## Hardware reference

### `04-anatomy-pinout.png` — Anatomy & pinout
Master visual reference. Every pin labelled (P0 buzzer, P1/P2 servo, P8/P12 LEDs, P13/P14 line sensors, P15 RGB×4, P16 IR receiver, I²C 0x10).

### `05-universal-mounting.png` — Universal mounting reference
Four M3 expansion holes highlighted in terracotta, plus servo cable colour code inset.

---

## Connection close-ups

### `06-servo-connection.png` — Servo connection
Both S1/S2 sockets, three-wire connector, right-way / wrong-way panels.

### `07-sr04-connection.png` — SR04 connection (redesigned)
Vertical layout: sensor on top, big down-arrow, socket below. Three numbered steps. Dashed alignment lines tie each pin to its hole.

---

## The 16 official wiki examples (new in v1.1)

### `16-wiki-examples-intro.png` — § 11 introduction
Section heading, "Where to find the actual code" callout, and the first four catalog entries (#01 Getting Started, #02 IR remote control, #03 Auto line-tracking, #04 Motor control). Shows the visual rhythm: italic terracotta number on the left, Cormorant title + paraphrased summary + teal API tags + dual links on the right.

### `17-wiki-card-detail.png` — Single card close-up
Entry #06 (Read ultrasonic distance) shown at full visual scale. Demonstrates the card composition: italic *06* number, Cormorant title, prose with inline `<code>` tag for `maqueen.Ultrasonic()`, teal API pills (`SR04 socket`, `Ultrasonic()`), dotted-underline links to Wiki + Guide Terrain.

### `18-wiki-reading-order.png` — Reading order subsection
The "Reading order — what to teach when" pedagogical sequence at the end of § 11. Four numbered phases: setup & smoke test (#1 / #7 / #16) → single-component reads (#10 / #6 / #8 / #13) → single-component drives (#4 / #15 / #5) → combined behaviours (#11 / #3 / #12 / #2 / #9 / #14). Followed by a Guide Terrain pointer noting the lesson scaffolding it adds on top.

---

## Mechanic kit profiles

### `08-forklift-kit.png` — Forklift profile (ROB0156-F)
Side view: chassis, mast, fork plate, linkage arm, ≈ 45 mm travel arrow.

### `09-loader-kit.png` — Loader profile (ROB0156-L)
Side view: single pivoting arm with bucket scoop, arc-of-motion indicator.

### `10-beetle-kit.png` — Beetle gripper (ROB0156-B)
Top-down view showing the scissor linkage that converts servo rotation into mirrored jaw motion.

### `11-push-kit.png` — Push profile (ROB0156-P)
Side view: passive blade in front + rotating ultrasonic mount on top with 10°→170° sweep arc.

---

## Reference panels & BoMs

### `12-assembly-pdf-panel.png` — Official assembly tutorials
Six PDF links: Master Mechanic instructions + four per-kit tutorials + Lite installation.

### `13-forklift-bom.png` · `14-bom-{forklift,loader,beetle,push}.png` — Bills of materials
Verified shipping lists per kit, cross-checked against DFRobot product pages, Element14, Farnell, Core Electronics distributors.

---

## Document close

### `15-footer.png` — Footer credit
*"Maqueen Lite · Reference — the technical companion to Guide Terrain. v1.0 · MIT License · same author as the parent repo."*

---

## Suggested embeds

* **README on GitHub**: `02-user-guides-panel.png` and `04-anatomy-pinout.png` work well as flagship images.
* **Slides for a teacher demo**: `07-sr04-connection.png` (the redesigned vertical layout) is the strongest single image.
* **Showcase the wiki-examples catalog**: `16-wiki-examples-intro.png` shows the top of § 11 with the callout and first 4 entries — ideal for explaining the catalog's purpose at a glance.
* **Print handouts**: 06, 07, 17 designed to print legibly at quarter-page size.
