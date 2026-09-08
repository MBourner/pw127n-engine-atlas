# PW127N Engine Atlas

An interactive 3D study model of the Pratt & Whitney Canada **PW127N** turboprop
(the engine fitted to the ATR 72-600), built as a single self-contained HTML page
with Three.js. Intended as a digital reference for ATR-rated pilots to learn how
the engine works, where its components sit, and how they connect.

**Live page:** published via GitHub Pages from this repository (see repo "About" link).

## Features
- Fully clickable 3D model — orbit, zoom, pan, and select any of ~46 components
- Explode view, movable cutaway section, adjustable casing transparency
- Animated gas-path visualisation (intake → compressors → combustor → turbines → exhaust)
- Rotor spin animation showing the real relative shaft speeds (HP / LP / power turbine / gearbox)
- A guided 17-stop tour: 12 gas-path stops followed by 5 power-path stops (turbine → gearbox → propeller)
- Every key figure is tagged with its source (EASA type certificate data sheet, ATR systems
  guide/FCOM, Pratt & Whitney maintenance manual, or "≈" for a derived/family-typical value)

## Sources
- EASA Type Certificate Data Sheet **IM.E.041**, Pratt & Whitney Canada PW100 series engines
- ATR 42/72-600 Systems Guide (FCOM 1.16, ATA 61/72)
- Pratt & Whitney Canada PW100 Engine Maintenance Manual, ch. 72-00, Description & Operation

## Disclaimer
This is an independent, unofficial training aid built from publicly available reference
material. It is **not** manufacturer CAD data, is not affiliated with or endorsed by
Pratt & Whitney Canada or ATR, and must not be used as a substitute for the aircraft's
approved AFM, FCOM, or QRH. Geometry is a schematic reconstruction for teaching purposes;
figures marked "≈" are derived or typical for the PW100 engine family rather than
PW127N-specific published values. Always defer to your operator's current official
documentation.

## License
Code and written content © the author. Provided for personal/educational reference.
