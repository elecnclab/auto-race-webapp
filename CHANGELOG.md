# Changelog

All notable changes to this project will be documented in this file.

## [1.0.5] - 2026-05-16
- Added `references/version-1/` and `references/version-2/` to separate first and second Auto Race reference photo sets.
- Moved historical/reference images out of `screenshots/` while keeping gameplay screenshots in `screenshots/`.
- Added photo attribution for the newly added references to Giuseppe Romano (`romans3`) in `README.md` and `references/CREDITS.md`.
- Updated README screenshot links to match the current file layout.

## [1.0.4] - 2026-05-12
- Improved anti-block logic to prevent no-escape scenarios in all lanes (left, center, right).
- Added a forward path reachability check on upcoming rows to ensure at least one valid passage.

## [1.0.3] - 2026-05-11
- Fixed an unfair no-passage scenario at high score/speed when the player is in the center lane.
- Added a gameplay safety check to prevent simultaneous left+right block on the row above the player.

## [1.0.2] - 2026-05-10
- Updated screenshots set in `screenshots/` (added new assets and removed `Screenshot-0.png`).
- Updated `README.md` with a dedicated screenshots section.

## [1.0.1] - 2026-05-09
- Added `VERSION` file for explicit version tracking.
- Added and initialized `CHANGELOG.md`.
- Created `screenshots/` folder and moved game screenshots into it.

## [1.0.0] - 2026-05-09
- Initial public repository structure.
- Added `README.md` and `auto_race_webapp.html`.
- Added project metadata files for version tracking.
