# Production

Manufacturing data for each released revision, generated from the KiCad project when a release is tagged.

```
production/
└── r2.0.0/
    ├── gerber/          Gerber and drill files
    ├── step400_bom.csv  Bill of materials
    ├── step400_pos.csv  Component placement
    └── step400_schematic.pdf
```

Files exported during day-to-day work should not be committed; only the data actually sent to manufacturing goes here.
