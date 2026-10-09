# AttendEase — Smart Attendance Management System

A browser-based attendance manager for the Open Source Technologies CA-3. It manages a student roster, records dated sessions, calculates percentages, flags students below 75%, estimates future attendance needs, and exports CSV.

## Features
- Add, edit, search, filter, and delete students
- Mark present/absent for a dated subject session
- Update an existing session for the same date and subject
- Attendance metrics and shortage prediction
- CSV report export
- LocalStorage persistence and responsive layout
- Fictional demo records

## Run
1. Download/clone the repository.
2. Open `index.html` in a modern browser.
3. No build step, packages, server, or database required.

If local-file storage is restricted, run `python3 -m http.server 8000` in this directory and visit `http://localhost:8000`.

## Reset demo data
Delete the LocalStorage key `attendease.v1` in browser developer tools and reload.

## Limitations
Data is saved only in the current browser profile. There is no authentication, server database, multi-user sync, or official college integration. The predictor assumes future classes are attended and uses a 75% target. Verify actual institutional rules before real use.

## Suggested CA-3 work
Run the test plan in `docs/TESTING.md`, create a GitHub repository, document an issue, reproduce a bug, implement a focused fix on a branch, and open a PR with test evidence. Capture real screenshots and report actual outcomes—do not invent issues, test results, or PR status.

## Files
- `index.html`: UI structure
- `styles.css`: styling and responsive layout
- `app.js`: application logic
- `CONTRIBUTING.md`: contribution workflow
- `docs/TESTING.md`: manual test plan
- `docs/CA3-REPORT-OUTLINE.md`: report structure

MIT licensed; see `LICENSE`.
