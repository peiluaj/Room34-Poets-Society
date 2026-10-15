# ROOM 34 POETS SOCIETY — Student website

## Open in VS Code
1. Unzip this package. Open the **ROOM34_POETS_SOCIETY_SITE** folder in VS Code.
2. Open `index.html` with Live Server (recommended), or double-click `index.html` in your browser. No installation or build step required.
3. Files: `index.html` (layout), `style.css` (visual design), `script.js` (interactive features), `lessons.js` (all lesson data), `images/lessons/` and `images/readings/` (artwork).

## Content status
- Lessons **1–5** include real, differentiated reading passages, spelling activities, multiple-choice questions, written responses, poetry writing and reflection.
- Lessons **6–40** have the complete lesson titles and schedule, but their content is **not yet written**. They are explicitly labelled *coming soon*, not represented as finished.
- Images supplied for Lessons 1–3 are included as compressed WebP. The 40-lesson image plan is in `IMAGE_MANIFEST.csv`.
- Missing images show a graceful placeholder. Add the correctly named `.webp` files into the paths in the manifest and refresh.

## Important
- Work is stored in `localStorage` on the same browser/device, not in an online account. Clearing browser data can delete it.
- CSV export includes the student's name entered at download time, group, answers, poem, reflection and multiple-choice auto-mark values.
- All lessons are **visible**; future content is not falsely represented as complete.
- No teacher answer keys or exemplars are included in the student-facing app.
- No reading-level labels are shown to students.
- The styling draws inspiration from the supplied HistoryFlix layout; no HistoryFlix copyrighted image assets or source code have been copied.
- For GitHub Pages: upload the **contents of this folder** to your repository root and enable Pages from the main branch root.

## Interactive spelling activities (updated)
Each spelling challenge has its own workspace. Matching tasks use clickable word and definition tiles with connecting lines; use Check matches for feedback and Clear lines to retry. Recall-and-spell activities include individual word inputs, a hide/show word button and spelling checks. Other tasks include dedicated response boxes. All answers save automatically in browser localStorage and are included as separate spelling rows in the exported CSV. Matching lines are recalculated when the window resizes. These workspaces are available in the authored Lessons 1–5 for all five groups.
