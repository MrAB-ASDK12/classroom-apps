# A Bespoke Suite of Apps

Small, free classroom tools built with Claude by a working teacher. There are no logins and no cost, and student data stays in the teacher's own browser.

| App | Folder | Saves to |
|---|---|---|
| Class Job Wheel | `job-wheel/` | The teacher's browser (copy-and-paste backup) |
| Class Behavior Log | `behavior-log/` | The teacher's browser (backup file) |
| Math Jeopardy: Early Algebra | `jeopardy/early-algebra/` | Scores, in the browser |
| Math Jeopardy: 7th Grade | `jeopardy/7th-grade/` | Scores, in the browser |
| Math Check-In (previews and setup guide) | `math-check-in/` | The teacher's own Google Sheet |
| The +30 Button | `plus30/` | Nothing |
| Spelling Check-In (plus printable diagnostic packet) | `spelling-check-in/` | The browser on the classroom computer (CSV export) |
| Spelling Studio: how it was built (showcase page only, not a usable app) | `spelling-studio-story/` | Nothing |
| Clip Shelf (Chrome/Edge extension; download page plus `clip-shelf.zip`) | `clip-shelf/` | The teacher's own Chrome (optional sync to their own Google Sheet) |

Every app except Clip Shelf is a single, self-contained HTML file. Clip Shelf is a browser extension: its page offers `clip-shelf/clip-shelf.zip` for download. To change an app, replace its `index.html` and commit.

See `HOW-TO-PUBLISH.md` for step-by-step instructions on putting this site on GitHub Pages.
