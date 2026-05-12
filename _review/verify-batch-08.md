# Batch-08 Visual Verification — FBI Photo B17–B24 + B2–B9

Verifier: Claude (Opus 4.7) — used `Read` tool on each `photo.jpg`.
Date: 2026-05-12
Scope: 16 folders, all single `photo.jpg` (no alternatives).
All photos are heavily redacted thermal/IR gunsight frames (FBI release): top banner blacked out, six bilateral redaction bars left/right at three vertical bands, white crosshair overlay, timestamp `12/31/99 HH:MM:SS` bottom-left.

| # | Folder | Timestamp | Crosshair style | Object signature | Verdict |
|---|---|---|---|---|---|
| 123 | fbi_photo_b17 | 18:20:48 | short ±3 ruler | Twin dark dots, side-by-side, just RIGHT of vertical crosshair on mid-line. Classic "double-blob" pair. | keep |
| 124 | fbi_photo_b18 | 18:21:02 | short ±3 ruler | Twin blobs, tighter / partially merged, slightly right of crosshair. Same pair, ~14 s later. | keep |
| 125 | fbi_photo_b19 | 18:18:53 | full ±15 ruler | Tiny single dark speck just above horizontal axis, near crosshair center. Faint, marginal. | keep |
| 126 | fbi_photo_b2  | 18:11:27 | full ±15 ruler | Single very faint speck near center; ridgeline visible bottom-right. Earliest-style frame. | keep |
| 127 | fbi_photo_b20 | 18:18:58 | full ±15 ruler | Small dark twin-lobe smudge right of crosshair (~+3 on ruler), thinner than B17/B18. | keep |
| 128 | fbi_photo_b21 | 18:19:06 | full ±15 ruler | Same small twin-lobe smudge, slightly shifted, at ~+2 right of center. | keep |
| 129 | fbi_photo_b22 | 18:19:19 | short ±3 ruler | **Two distinct round blobs, sharply rendered, well separated, ABOVE the horizontal line, right of vertical.** Strongest "double-blob clear zoom-in" frame. Matches expectation. | keep |
| 130 | fbi_photo_b23 | 18:19:33 | short ±3 ruler | Elongated dark streak on horizontal axis, right side near "3" tick. Wing-like blur (motion). | keep |
| 131 | fbi_photo_b24 | 18:19:40 | short ±3 ruler | **Irregular asymmetric blob with wing-like extension to the right, just left of vertical crosshair, above horizontal.** Matches "winged extension + irregular form" expectation. | keep |
| 132 | fbi_photo_b3  | 18:11:34 | full ±15 ruler | Empty target area; faint single pixel near center. Only crosshair visible, no object. | keep |
| 133 | fbi_photo_b4  | 18:12:16 | full ±15 ruler | Very faint single dark speck just above crosshair center. Marginal detection. | keep |
| 134 | fbi_photo_b5  | 18:12:20 | full ±15 ruler | Effectively empty; crosshair only. Possible ridgeline shadow bottom. | keep |
| 135 | fbi_photo_b6  | 18:10:00 | full ±15 ruler | **Large dark irregular mass above crosshair top-tick (helicopter-like silhouette with rotor blur); secondary small dot at ~–10 right of vertical, below horizontal.** Earliest timestamp 18:10:00 — matches "earliest frame + large mass" expectation. | keep |
| 136 | fbi_photo_b7  | 18:10:02 | full ±15 ruler | Same large rotor-blurred silhouette, shifted right (~+6 right of center, above horizontal). Secondary small dot lower mid-frame. Continuation of B6. | keep |
| 137 | fbi_photo_b8  | 18:10:18 | full ±15 ruler | Single tiny dark dot at ruler tick ~+2 right of center; no large mass anymore. | keep |
| 138 | fbi_photo_b9  | 18:10:26 | full ±15 ruler | Single small dot at ~–6 left of center on horizontal line; ridgeline shadow bottom. | keep |

## Findings vs. expectations

- **B22 (#129):** confirmed — clearest twin-blob frame in the batch, two sharply rendered round blobs well separated. Good "zoom-in starting point."
- **B24 (#131):** confirmed — irregular shape with a wing-like extension on the right. Distinct morphology from the round B17/B18/B22 twin-blob frames.
- **B6 (#135):** confirmed — earliest timestamp (18:10:00) in the batch and shows the only large rotor-blurred dark mass at upper-center; consistent with "earliest frame + large mass."
- **B14 (#120):** **out of scope** — folder 120 is not in this batch. (Batch-08 covers 123–138.)

## Observations

- Two timestamp clusters: 18:10:00–18:12:20 (B6→B5, full ±15 ruler, large object then disappearance) and 18:18:53–18:21:02 (B19→B18, mostly short ±3 zoom ruler, twin-blob pursuit).
- Crosshair style is a reliable proxy for camera mode: full ±15 ruler = wide acquisition; short ±3 ruler = zoom track. Wide-mode frames mostly contain faint specks; zoom-mode frames carry the twin-blob and wing-shape signatures.
- B22 + B24 are the two most reportable frames; B6 + B7 anchor the early "large object" sequence; the rest are continuity/tracking frames.

## Verdict summary

All 16 photos: **keep** (no alternatives in any folder).
