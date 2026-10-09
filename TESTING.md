# Manual test plan

Run each test and record the actual outcome before submitting your report.

| ID | Test | Steps | Expected result |
|---|---|---|---|
| T01 | Initial load | Open `index.html` | Dashboard loads with demo records |
| T02 | Add student | Add unique name and roll | Student appears in roster and attendance list |
| T03 | Required fields | Submit blank name or roll | Browser blocks form submission |
| T04 | Duplicate roll | Add an existing roll in different letter case | Duplicate is rejected with a message |
| T05 | Edit student | Change a student's name | Updated name appears throughout app |
| T06 | Delete student | Delete and confirm | Student and their attendance values are removed |
| T07 | Present | Mark all present and save a session | Attendance metrics update |
| T08 | Absent | Mark a student absent and save | Percentage decreases correctly |
| T09 | Update session | Save same date and subject again | Existing session updates instead of duplicating |
| T10 | Search | Search part of name or roll | Matching students remain |
| T11 | Filter | Select below 75% | Only recorded students below threshold appear |
| T12 | Prediction | Select a student with records | Percentage and estimate are shown |
| T13 | CSV | Export report | CSV downloads with headings and values |
| T14 | Persistence | Reload after saving | Data remains in the same browser |
| T15 | Empty roster | Delete all students | App remains usable and prompts to add students |
| T16 | CSV escaping | Use a name with comma/quotes and export | CSV quoting is preserved correctly |

## Bug report template
- Issue title:
- Browser/environment:
- Preconditions:
- Steps to reproduce:
- Expected result:
- Actual result:
- Screenshot/evidence:
- Root cause:
- Fix:
- Regression tests and actual result:

These are test cases, not claims that they have already passed.
