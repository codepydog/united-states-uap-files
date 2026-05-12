# Batch-10 Cover Verification Manifest

Date: 2026-05-12
Scope: 14 folders (State Dept cables, DoW Misreps, USPER statement, FBI Sept-2023 serials, Western US event)

## Legend

- KEEP: cover already substantive, no change.
- REPLACE: cover swapped with a more interesting page; README path may need updating.

## Per-folder verdict

| # | folder | original cover | action | new cover | README path change |
|---|--------|---------------|--------|-----------|---------------------|
| 151 | 151-dow_uap_d74_mission_report_syria_nov_2023 | page-01.jpg (Misrep narrative, redacted) | REPLACE | cover.jpg (copy of page-09.jpg — UAP data card listing "TRAVELED ~424KN CONSISTENTLY FOR AT LEAST 7MINS IN THE SHAPE OF A BOUNCY BALL") | README points at `page-01.jpg` — **update to `cover.jpg`** |
| 151 | 151-state_dept_uap_cable_1_papua_new_guinea_1985 | cover.jpg (cable header, PNG NIO inquiry) | KEEP | — | none |
| 152 | 152-dow_uap_d75_mission_report_gulf_of_aden_jul_2024 | page-1.jpg (Misrep narrative, redacted) | REPLACE | cover.jpg (copy of page-7.jpg — UAP data form with "STRAIGHT FLIGHT PATH AT SAME ALTI", DTG 140517 etc.) | README points at `page-1.jpg` — **update to `cover.jpg`** |
| 152 | 152-state_dept_uap_cable_2_kazakhstan_1994 | cover.jpg (Dushanbe cable, "TAJIK AIR PILOTS REPORT UFO at 41,000 ft") | KEEP | — | none |
| 153 | 153-dow_uap_d8_mission_report_djibouti_2025 | page-1.jpg (fully-redacted 1.4(a) black page) | REPLACE | cover.jpg (copy of page-7.jpg — GENTEXT/UAP "OBS 2X ROUND WHITE HOT UAPS DYNAMIC SOUTH AT APPROX 240NM/HOUR IVO 35SQT…") | README points at `page-1.jpg` — **update to `cover.jpg`** |
| 153 | 153-state_dept_uap_cable_3_tbilisi_2001 | cover.jpg (Moscow cable, "UFOS OVER GEORGIA: STRANGE ENCOUNTERS OF AN MFA KIND") | KEEP | — | none |
| 154 | 154-state_dept_uap_cable_4_ashgabat_2004 | cover.jpg (Ashgabat cable, "TURKMENISTAN, CIVIL SOCIETY AND UFOS" + "Yes, UFOs.") | KEEP | — | none |
| 155 | 155-state_dept_uap_cable_5_mexico_2023 | cover.jpg (Weekly Political Blotter, bullet includes "Mexican Congress Hears Testimony on Alien Life") | KEEP | — | none |
| 156 | 156-usper_statement_uap_sighting | cover.jpg (USPER narrative — 1751Z spotted large cavern, 2050Z landed west of mountains, NVG, FLIR, helicopter) | KEEP | — | none |
| 157 | 157-fbi_september_2023_composite_sketch | cover.jpg (the FBI composite sketch itself: bronze elliptical disc + intense light over field) | KEEP | — | none |
| 158 | 158-fbi_september_2023_serial_3 | cover.jpg (FD-302 form, narrative starts: "bright light over the horizon… stationary… 10 seconds before it disappeared") | KEEP | — | none |
| 159 | 159-fbi_september_2023_serial_4 | cover.jpg was FD-302 page-1 (interview setup, gate fob issue, page cut before sighting description) | REPLACE | cover.jpg (overwritten with page-2.jpg — cigar-shaped object, metallic bronze, 500-3000 ft above tree line, "length of two or three Blackhawks lined up nose to tail", ring around light, just disappeared) | README points at `cover.jpg` — **no path change**, content updated only |
| 160 | 160-fbi_september_2023_serial_5 | cover.jpg (FD-302 with full description: "linear object… super bright light… metallic/gray… smaller than a 737… 5000 ft AGL… moved east to west… vanished") | KEEP | — | none |
| 161 | 161-western_us_event | cover.jpg ("Orbs Launching Orbs" slide — orange mother orbs launching red orbs in groups of 2-4, witnessed 5+ times by 3 teams) | KEEP | — | none |

## Summary

- Replaced: 4 covers (151-dow Syria, 152-dow Aden, 153-dow Djibouti, 159 FBI serial-4)
- Kept: 10 covers
- README path updates required: 3 (151-dow, 152-dow, 153-dow — change image src from `page-0?1.jpg` to `cover.jpg`)
- README path updates NOT required: 11 (all already point at `cover.jpg` or replacement is content-only overwrite of `cover.jpg`)

## Notes

- 153-dow original page-1 through page-6 were all fully-redacted black "1.4(a)" pages. Page-7 (chosen) is the only substantive page in that folder and is already noted as such in the existing README caption.
- All four "DoW Misrep" folders (151/152/153-dow) had no pre-existing `cover.jpg`; this run creates one as a copy of the best page.
- 159 had `cover.jpg` already (was duplicate of page-1.jpg). Content overwritten in place.
- No README.md edits and no git operations performed by this run.
