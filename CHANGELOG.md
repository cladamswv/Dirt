# Changelog

## Arcade 3.2.0 — Turnkey Presentation Pass
- Added new DIRTLINE MX main logo, app mark, and branded boot splash.
- Added animated splash sequence and full-screen main menu.
- Added Arcade Race and functional solo Time Trial selection.
- Added Garage with three player color schemes.
- Added How to Play and Settings screens.
- Added branded course loading screen and staged loading progress.
- Added pause menu and main-menu return flow.
- Added redesigned results screen with place, time, top speed, and clean landings.
- Rebuilt gameplay HUD into compact telemetry/status/control clusters.
- Added new UI click and confirmation audio.
- Replaced in-world DIRTLINE, START, and FINISH banner artwork.
- Added presentation checks to the Godot runtime smoke test and Android CI workflow.
- Preserved Arcade 3.1 medium-poly textured environments and Arcade V4 rider/bike.

## 3.2.1 hotfix
- Fixed Godot 4.3 runtime parse failure in `Main.gd` caused by inferred Variant types in race-start positions.
- Race-start lanes, offsets, colors, start X, bike X/Y and runtime surface count now use explicit GDScript types.
- CI now rejects unsafe inferred local declarations in `Main.gd` before running the smoke test.
- Updated runtime smoke-test marker and Android artifact/version to 3.2.1.

## 3.2.2
- Fixed missing Android touchscreen controls.
- Added race-grid activation watchdog and live-motion smoke tests.
- Restored audible player/AI motorcycle engine mix.
- Reduced intrusive start-line branding in the race camera.

## 3.2.3
- Fixed CI exit-code 60 from the AI movement smoke test.
- Added deterministic AI clutch launch via `activate_from_grid()`.
- Strengthened rider deadlock recovery, including momentary airborne/ground-contact edge cases.
- Preserved touchscreen/control and motorcycle-audio fixes from 3.2.2.
- Cleaned Android package/export version labels and raised version code to 34.
