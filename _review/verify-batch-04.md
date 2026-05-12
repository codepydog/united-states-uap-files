# Batch-04 cover verification

Date: 2026-05-12
Reviewer: visual inspection via Read tool
Scope: 15 folders (D-series Part 2 covering D4/D42/D44/D48/D49/D5/D50/D51/D52/D54 + 5 NASA missions)

## Result summary

- Kept: 14
- Replaced: 1 (061)

## Per-folder verdict

| # | folder | cover used | verdict | reason |
|---|---|---|---|---|
| 054 | dow_uap_d4_mission_report_arabian_gulf_2020 | cover.jpg | keep | GENTEXT/UAP bullet: "OBSERVED POSS UAP IVO 34SDG9041417044 ... VELOCITY 321 KNOTS. UAP INCREASED SPEED AND CHANGED DIRECTION TOWARDS THE EAST" |
| 055 | dow_uap_d42_range_fouler_debrief_japan_2023 | form.jpg | keep | SPEAR Range Fouler Debrief Form, 482 ATKS / O-2 Pilot, Other Shaped + Apparent Propulsion checked, dusk over Japan, 18000 ft, Yes-moving 150/230, hand-written narrative present |
| 056 | dow_uap_d44_range_fouler_gulf_of_aden_october_2020 | form.jpg | keep | SPEAR Range Fouler Reporting Form, 172 ATKS, Round checked, "bright white" object at 19,073 ft HAT over Gulf of Aden, "abrupt directional changes" narrative, full position fix and slant range |
| 057 | dow_uap_d48_air_force_space_booster_risk_report_1996 | cover.jpg | keep | RTI report title page "Modeling Unlikely Space-Booster Failures in Risk Calculations" prepared for 45th/30th Space Wing Safety Office, with DTIC stamp 19961025 122 - artifact-identifiable; all alts (abstract, TOC) less distinctive |
| 058 | dow_uap_d49_vandenberg_launch_summary_1958_2000 | cover.jpg | keep | "Vandenberg AFB Launch Summary 1958-2000" cover with 30th Space Wing crest - punch-hole binder aesthetic; alts are bare annual launch tables / acronym lists |
| 059 | dow_uap_d5_mission_report_arabian_gulf_2020 | cover.jpg | keep | GENTEXT/UAP bullet: "OBSERVED 1X UAP IVO 34SCE7566990098. VELOCITY WAS 40 KNOTS AT FL160 TO FL170. UAP SPEED REMAINED CONSTANT" |
| 060 | dow_uap_d50_email_correspondence_indopacom_april_2025 | p-01.jpg | keep | INDOPACOM tearline classification email; mentions "AOR INDOPACOM ... UNCLASSIFIED level" with PAROC Intel Data Analysis Technician 12 AF / DET 3 signature - the document IS the artifact |
| 061 | dow_uap_d51_email_correspondence_pacific_time_zone_march_2023 | cover.jpg (now = p-04) | **replaced** | Original cover was admin "Good morning ... process for declassifying IIRs is lengthy" with no UAP content. Copied p-04 (full UAP narrative: "large blue featureless triangular object with a solid, unwavering silhouette emitting powerful 'whitish blue' light from multiple points along its perimeter ... hovering ... over a national security facility for approximately three minutes ... backing up in a jerking or jumping manner inconsistent with smooth jet propulsion") over cover.jpg. README untouched. |
| 062 | dow_uap_d52_email_correspondence_na_august_2024 | p-01.jpg | keep | Email leads with UNCLASS tearline + observation: "31 OCT 24, U.S Aircraft observed a possible UAP. It appeared to be oval/orb" - dramatic opening |
| 063 | dow_uap_d54_mission_report_mediterranean_sea_na | cover.jpg | keep | GENTEXT/UAP block: "1X UAP DETECTED WITH DESCRIPTIVE INFORMATION SUCH AS BEING A TRIANGULAR AND METALLIC UAP ... DURING RTB AT 1319Z ... OBSERVED 1X UAP WHILE TRANSITING OVER 363453N 0255943E FLYING AT AN ALTITUDE OF 24,989FT MSL AND SPEED OF 168KTS" |
| nasa-apollo-11 | aldrin-cabin-flashes | cover.jpg | keep | Aldrin Confidential debrief 6-37 narrative: "I observed what I thought were little flashes inside the cabin ... double flashes, at points separated by maybe a foot ... some sort of penetration of some object into the spacecraft" - iconic cabin-flash quote (cover.jpg md5 matches aldrin-cabin-flashes.jpg) |
| nasa-apollo-12 | cover.jpg | cover.jpg | keep | Lunar surface panorama with astronaut shadow + yellow zoom-box annotation showing vertical blue-green light streak - one of the most dramatic NASA UAP images in the set |
| nasa-apollo-17 | cover.jpg | cover.jpg | keep | Apollo-17 mountainous lunar panorama with yellow zoom-box showing three blue light points above the horizon (VM6 trio); cinematic and clearly UAP-flavoured |
| nasa-gemini-7 | cover.jpg | cover.jpg | keep | GT-7/7-6 PAO release transcript with Borman/Lovell calls: "A BOGEY AT TEN O'CLOCK HIGH ... THIS IS AN ACTUAL SIGHTING ... HUNDREDS OF LITTLE PARTICLES ... BRILLIANT BODY IN THE SUN AGAINST A BLACK BACKGROUND ... SLOWLY TUMBLING" - canonical Borman bogey transcript |
| nasa-skylab | garriott-redstar.jpg | garriott-redstar.jpg | keep | Skylab debrief section "20.0 VISUAL SIGHTINGS" opens with Garriott: "Jack first noticed this rather large red star out the wardroom window. Upon close examination, it was much brighter than Jupiter or any of the other planets" - all skylab alternates are pure text, this is the best UAP-themed excerpt |

## Notes

- 057 and 058 retained their admin-flavoured covers because every alternate page in those folders is equally text-heavy (abstracts, TOCs, acronym dictionaries, annual launch tables). The cover at least conveys "this is the artifact" through document title and unit insignia.
- Email-correspondence folders (060/061/062) per task spec: covers are the email content itself. 060 and 062 lead with UAP-relevant text (INDOPACOM AOR tearline, oval/orb observation). 061 was the only one whose first page was pure declassification admin, so it was upgraded to the page that actually contains the UAP narrative.
- D-series mission reports (054/059/063) all show the classic redacted-page-with-GENTEXT/UAP-description layout - they look identical structurally but each carries a different UAP narrative line and were left as-is.

## Files modified

- `reports/061-dow_uap_d51_email_correspondence_pacific_time_zone_march_2023/cover.jpg` (overwritten with p-04.jpg content; md5 b2ec4a7e058a8d5965ffdf4ae406ecb5)

## Files untouched

- All `report.md` (READMEs)
- All other cover/form/p-XX images in the 15 folders
- Git state (no commits made)
