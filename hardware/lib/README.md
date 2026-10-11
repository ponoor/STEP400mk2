# step_series library

Shared KiCad library for the STEP series hardware.

| Path | Contents |
|---|---|
| `step_series.kicad_sym` | Symbols |
| `step_series.pretty/` | Footprints |
| `step_series.3dshapes/` | 3D models referenced by the footprints |
| `step_series.kicad_blocks/` | Design blocks (reusable schematic blocks) |

Projects refer to this library through their project library tables, using paths relative to the project (`${KIPRJMOD}/../lib/...`).

Footprints carried over from the r1 design ([ponoor/STEP400](https://github.com/ponoor/STEP400), `hardware/step400_r1/step400_r1.pretty`) are added here only after they have been reviewed against the datasheets.
