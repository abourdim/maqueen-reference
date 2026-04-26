# Screenshots — visual index

Every screenshot in `/screenshots/` was captured at **2× device-scale factor** from `maqueen-reference.html` rendered in headless Chromium at 1280×1000 viewport. PNGs stay sharp when embedded in documents, README files, slides, or printed handouts.

---

## Front-of-document

### `01-hero.png` — 840 × 364
The hero block. Cream background, terracotta kicker line, Cormorant title `Maqueen Lite · Reference`, four-column meta strip (Hardware / Power / Languages / Price). The kicker explicitly names the relationship to Guide Terrain: *"DFRobot ROB0148 · Reference · companion to Guide Terrain"*.

### `02-user-guides-panel.png` — 840 × 220
The user-guides quick-access panel. Seven rows of clickable links: Maqueen Lite (Wiki / Buy / Install PDF / Extension), Plus V2, Plus V3, Mechanic kits (Master PDF / Walkthrough), MakeCode editor (Open / Python / CreateAI), **Guide Terrain (sibling)** with four links (Live / Source / README / Changelog), and **Also by author** with two sibling-project links.

### `03-family-table-section.png` — 840 × 1561
The Maqueen family comparison section. Long table covering Lite vs Plus V2 vs Plus V3 with every row of feature comparison. Tallest screenshot in the bundle — this is the canonical visual for "which Maqueen do I buy?".

---

## Hardware reference

### `04-anatomy-pinout.png` — 840 × 876
The schematic section. Top-down chassis diagram with every pin labelled (P0 buzzer, P1/P2 servo, P8/P12 LEDs, P13/P14 line sensors, P15 RGB×4, P16 IR receiver, I²C 0x10 motors). The master visual reference of the document.

### `05-universal-mounting.png` — 840 × 463
Universal hardware reference. Chassis with the four M3 expansion holes highlighted in terracotta (where every Mechanic kit attaches), plus a wiring inset showing the servo cable colour code (orange / red / brown) with the brown-toward-edge orientation rule.

---

## Connection close-ups (kid-friendly)

### `06-servo-connection.png` — 840 × 605
Servo cable plugging into S1 / S2. Both sockets drawn with three coloured pins matching the wires. Right-side connector with three-wire cable. Green ✓ panel showing brown wire on the outside; red ✗ panel showing the flipped (no-damage, just retry) version.

### `07-sr04-connection.png` — 840 × 707  ⭐
**The redesigned SR04 close-up.** Vertical layout: sensor with two transducer eyes on top, four pins coming down, big terracotta arrow in the middle, four matching holes below at the same x-coordinates. Three numbered steps: **1 · HOLD THE SENSOR · 2 · push the sensor straight DOWN · 3 · INTO THE SOCKET**. Pin labels (VCC / Trig / Echo / GND) at 60-px spacing so they no longer collide. Faint dashed alignment lines tie each pin to its corresponding hole. Right-way (slides on with no force) and wrong-way (resists / sits crooked) strips below.

---

## Mechanic kit profiles

### `08-forklift-kit.png` — 840 × 396
Forklift profile — chassis, mast, fork plate, linkage arm, servo position, ≈ 45 mm travel arrow. Side-view diagram with terracotta annotations.

### `09-loader-kit.png` — 840 × 396
Loader profile — single pivoting arm with bucket scoop on the end, arc-of-motion indicator, servo at the pivot.

### `10-beetle-kit.png` — 840 × 396
Beetle gripper — top-down view (the only sensible angle for a gripper) showing the scissor linkage that converts servo rotation into mirrored jaw motion.

### `11-push-kit.png` — 840 × 448
Push profile — passive blade in front + rotating ultrasonic mount on top with 10° → 170° sweep arc shown overhead. SR04 coloured teal to mark this as the only kit where the servo drives a sensor instead of a manipulator.

---

## Reference panels

### `12-assembly-pdf-panel.png` — 840 × 566
The "Official assembly tutorials" callout at the top of section 11. Six links: Master Mechanic instructions PDF (consolidated reference for all four kits), four per-kit tutorial PDFs, and the Maqueen Lite Installation Instructions v1.1 (base-robot setup). Plus wiki page links for each kit.

### `13-forklift-bom.png` — 1080 × 380
The Forklift bill of materials, showing the verified shipping list for ROB0156-F: 9 g metal gear servo, metal arm servo base, baseplate, 3× linkages, plate, servo arm linkage, forklift plate, 2× M3×15 mm copper pillars, 5× M2.5×5 mm screws, 18× M3×5 mm screws.

### `14-bom-forklift.png` · `14-bom-loader.png` · `14-bom-beetle.png` · `14-bom-push.png`
Updated BoMs after the verification round. Each shows DFRobot's exact shipping list cross-checked against Element14 / Farnell / Core Electronics distributor listings. The Beetle list is the longest (10 distinct part types). The Push list uniquely includes a 4-pin ultrasonic extension wire — the most overlooked part in classroom Push assemblies.

### `15-footer.png` — 840 × 167
The closing credit. *"Maqueen Lite · Reference — the technical companion to Guide Terrain. Drafted to fill the gaps in DFRobot's own documentation. v1.0 · MIT License · same author as the parent repo."*

---

## Order of appearance in the document

If reading the screenshots top-to-bottom mirrors a top-to-bottom read of the document, the canonical order is:

1. Hero → 2. User-guides panel → 3. Family table → 4. Anatomy/pinout → 12. Assembly-PDF panel → 5. Universal mounting → 6. Servo connection → 7. SR04 connection → 8-11. Kit profiles (in section order) → 13/14. BoMs (one per kit) → 15. Footer.

---

## Embedding tips

* **README on GitHub**: 02-user-guides-panel and 04-anatomy-pinout work well as flagship images, since they encode the most information per pixel.
* **Slides for a teacher demo**: 07-sr04-connection (the redesigned vertical layout) is the strongest single image — it tells the whole story in one frame.
* **Print handouts**: 06 and 07 are designed to print legibly at quarter-page size; the 2× DPI gives clean output even after compression.
* **Forum or blog post**: 03-family-table-section (full comparison table) often works as a one-shot answer to "which Maqueen should I buy".
