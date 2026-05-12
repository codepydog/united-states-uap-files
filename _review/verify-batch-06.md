# Batch-06 cover.jpg visual verification

Date: 2026-05-12
Range: 093 - 106 (PR36 - PR49), 14 folders
Method: Read tool visual inspection of every cover.jpg, replace if scene is blank/featureless.

## Manifest

| # | Folder | Verdict | Action | Notes |
|---|---|---|---|---|
| 093 | PR36 middle_east_may_2020 | keep | - | Full IR HUD with pitch ladder, heading tape, redacted overlays; faint white spot lower-left |
| 094 | PR37 middle_east_2020 | keep | - | Clear boat wake at sea with cyan center reticle |
| 095 | PR38 middle_east_2013 | keep | - | Distinctive eight-point dark star artifact at lower-right (signature PR38 frame) |
| 096 | PR39 middle_east_2020 | keep | - | Aerial IR of island / coastal base with target reticle and red bearing arrow |
| 097 | PR40 middle_east_2020 | keep | - | "U/I SMALL THERMAL SIGNATURE" annotation with white circle (label rare among 161 frames) |
| 098 | PR41 middle_east_2020 | **replace** | cp frame-end.jpg -> cover.jpg | Original cover was flat grey cloud with no visible target; frame-end has clearer sea surface + small bright dot lower-right |
| 099 | PR42 middle_east_2020 | keep | - | Faint horizontal streak left-of-center + small light point; understated but has IR detail (frame-mid/end alternatives are weaker) |
| 100 | PR43 africa_2025 | keep | - | High-altitude oblique with horizon curve, river drainage and small settlement |
| 101 | PR44 middle_east_2020 | keep | - | Central dark vortex surrounding bright object with red bearing wedge |
| 102 | PR45 middle_east_2020 | keep | - | Purple autotrack ellipse + crosshair + green border frame (only autotrack-style cover in batch) |
| 103 | PR46 indopacom_2024 | keep | - | Football / olive-shape dark object with protrusion at center reticle |
| 104 | PR47 indopacom_2023 | keep | - | Red ring reticle + paired "infinity" double-blob target above |
| 105 | PR48 indopacom_2024 | keep | - | Offshore wind farm silhouettes with magenta reticle (unique scene type) |
| 106 | PR49 army_2026 | keep | - | Dark olive-green frame with twin bright dots and faint trail at center |

## Summary

- 14 folders checked
- 13 kept (interesting IR detail: HUD overlay, wakes, targets, labels, reticles, wind farms, twin dots)
- 1 replaced: 098 PR41 (cover -> frame-end)
- README.md and git untouched
