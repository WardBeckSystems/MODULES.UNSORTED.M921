# M921 · Unsorted

Ward-Beck Systems M921, 1996|29. Wiki page: [M921 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M921.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 4 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 3 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 1 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 2 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 3 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 5 |

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M921.kicad_sym](KICAD/M921.kicad_sym)
- [PCB 14-325 - M921](KICAD/PCB%2014-325%20-%20M921)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

## 3-D model

[`MECHANICAL/M921.stl`](MECHANICAL/M921.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M921)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M921 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M921.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
