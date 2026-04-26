# Changelog

All notable changes to the Maqueen Lite Reference document.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) conventions.

---

## [1.0.0] — 2026-04-25

The first packaged release. Drafted as a deliberate technical companion to the [Guide Terrain](https://abourdim.github.io/maqueen-activities/) activity guide.

### Added

#### Document structure
* 14 sections with sticky table-of-contents sidebar
* Print CSS optimised for A4 classroom use
* Copy buttons on every code block
* Cream / ink / terracotta / teal aesthetic in the same family as Guide Terrain's Zellige theme

#### Cross-references to Guide Terrain
* Hero positions this doc as the "companion" — explicit text in kicker and lede
* User-guides panel: dedicated row with 4 links (Live / Source / README / Changelog)
* User-guides panel: "Also by author" row linking the two confirmed sibling repos
* Section-end pointers at §9 (API → cheatsheet), §11 (Mechanic → Robotique/Capteurs), §13 (Pitfalls → FAQ panel)
* Footer credits the parent repo and names the relationship
* Result: 9 prose mentions, 9 live-demo links, 4 source links

#### Hardware reference
* Top-down chassis schematic with every pin labelled (P0–P16, I²C 0x10)
* Pinout reference table — every pin, every API call, on one page
* Universal hardware reference for Mechanic kits: M3 mounting holes diagram + servo wiring inset
* Pre-flight checklist (6 numbered steps applying to every kit assembly)
* Tools-you-need list

#### Connection close-ups
* Servo cable plugging into S1/S2 — chassis with both sockets, three-wire connector, right-way / wrong-way panels with mini connector mock-ups
* SR04 ultrasonic plugging into the chassis socket — vertical layout with sensor on top, big down arrow, socket on bottom, dashed alignment lines tying each pin to its hole, three numbered steps
* Both diagrams designed for kids: large labels, plain language, "you cannot break it" reassurance

#### Mechanic kit coverage
* Per-kit profile for all four kits (Forklift / Loader / Beetle / Push)
* Each kit: side or top-view diagram, BoM, step-by-step assembly (9-11 steps), calibration angles, code recipe, activity ideas
* "Official assembly tutorials" panel linking all 5 PDFs (Master + 4 per-kit + Lite installation)

#### API reference
* Every namespace function from `pxt-maqueen` with verified spelling
* Code samples match the parent README's conventions exactly:
  * `maqueen.motorRun(maqueen.Motors.All, maqueen.Dir.CW, 150)`
  * `maqueen.servoRun(maqueen.Servos.S1, 90)`
  * `maqueen.readPatrol(maqueen.Patrol.PatrolLeft)`
  * `maqueen.Ultrasonic()`
  * `maqueen.writeLED(maqueen.LED.LEDLeft, maqueen.LEDswitch.turnOn)`
  * `maqueen.IR_Read(IR_Pin.P16)`

#### Verified bills of materials

* **Forklift (ROB0156-F)** — 11 part types, official shipping list
* **Loader (ROB0156-L)** — 7 part types, official shipping list (cross-checked Amazon / Element14)
* **Beetle (ROB0156-B)** — 10 part types, official shipping list (cross-checked Core Electronics)
* **Push (ROB0156-P)** — 7 part types including the often-overlooked 4-pin ultrasonic extension wire

All BoMs verified against DFRobot product pages, Element14, Farnell, and Core Electronics distributor listings.

#### Screenshot library
* 18 PNGs at 2× device-scale factor
* Captured via headless Chromium at 1280×1000 viewport
* Ordered to match document flow
* Indexed in `docs/SCREENSHOTS.md`

### Verified

* All 132 external links confirmed live as of 2026-04-25
* All 5 official PDFs (Master Mechanic + 4 kit tutorials + Lite installation) confirmed reachable
* All 4 kit wiki URLs confirmed reachable
* `pxt-maqueen` API spelling cross-checked against the source repo

### Design decisions

* **Vertical SR04 layout** — replaced the original side-by-side diagram after kid-friendliness review revealed pin labels colliding ("VCCTrigEchoGND" rendering) and unclear spatial relationship. The vertical layout mirrors the physical action (sensor pushes down onto socket) and uses dashed alignment lines for unambiguous pin-to-hole mapping.
* **No CDN-loaded fonts** — system fonts only (Cormorant Garamond, Spectral, JetBrains Mono fall back gracefully). Document works offline, prints predictably.
* **No external dependencies** — no JavaScript libraries, no CSS frameworks. Single self-contained file under 135 KB.
* **MIT license** — matches parent repo for frictionless integration.
