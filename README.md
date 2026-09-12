# ContainerCraft Studio — Architect v4

Browser-based ISO shipping-container home designer. Open `index.html` in a modern desktop browser with internet access (Three.js loads from CDN).

The original single-file build is also included as `ContainerCraft_Studio_Architect_v4.html`.

## Features

- 31 starter home designs plus a blank canvas
- ISO containers: 20' Standard, 40' Standard, 40' High Cube
- Interior walls, rooms, doors, windows, and auto-framing
- Functional straight / L / spiral stairs with floor and roof cutouts
- Plot-and-edit decks with magnetic snap to container edges
- Beams, support posts, shed / gable / A-frame roofs
- Plan, elevation, isometric, and walk views
- Printable blueprint package (SVG / PDF via print)
- Project JSON import / export and local browser save
- Editable 2026 planning cost ranges derived from the model

## Quick start

```bash
git clone https://github.com/tbenitz/containercraft-studio.git
cd containercraft-studio
python3 -m http.server 8080
```

Visit `http://localhost:8080`.

Or open `index.html` / `ContainerCraft_Studio_Architect_v4.html` directly.

## Notes

- Design aid only. Structural, guard/stair, energy, MEP, site, wind/seismic/snow, code, and permit work still need local professional verification.
- Cost figures are editable planning allowances, not bids.
- Scene data stays in the browser unless you export JSON or use Save.
