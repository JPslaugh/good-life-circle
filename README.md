# The Good Life Circle — Peer Coaching Exercise

A single self-contained web page (`index.html`) — no install, no internet, no server.
Everything (questionnaire, live wheel, insights, save, PDF) runs in the browser.

## For the coach
- **Send it:** just share the `index.html` file. The person double-clicks it; it opens in any browser.
- **Privacy:** answers never leave the device. Progress is autosaved in that browser only.
- **Getting results back:** when they finish, they click **Download PDF Report** and send you the PDF.
  The PDF is the deliverable — there are no data files to manage.

## For the person filling it out
1. Enter name + date.
2. Work through the 6 areas. For each item, set two sliders:
   - **Importance** — how much it matters in your ideal life (0–10)
   - **Satisfaction** — how happy you are with it right now (0–10)
   Your progress saves automatically — you can close the tab and come back.
3. **Confirm & lock each section** when you're happy with it. A section only counts
   toward your results once confirmed — this is how a deliberate score (even a 5) is
   recorded rather than treated as "unanswered." Use **Edit answers** to reopen a section.
5. When all six sections are confirmed, click **See my results** for your wheel and insights.
6. Click **Download PDF Report** and choose **"Save as PDF"** to keep or share a clean report.

## How to read the wheel
- **Coloured fill** = satisfaction (fills from centre = 0 to edge = 10)
- **Dashed outline** = importance
- The space between them is your **gap** — the bigger the gap, the more worth a conversation.

## What's under the hood (for future edits)
- All questions/categories/tips live in the `CATEGORIES` and `TIPS` objects near the top of
  the `<script>` in `index.html` — edit text there to retune wording.
- Subcategory scores average up into the 6 main categories for the wheel.
- Insights are rule-based: priorities = importance ≥ 5 and gap ≥ 2; strengths = satisfaction ≥ 7
  and importance ≥ 5; low-priority = importance < 4.
- Source material: the *Good Life Circle Needs List* spreadsheet and the *Wheel of Life* coaching doc.
