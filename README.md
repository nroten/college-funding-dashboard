# College Funding Command Center

A private dashboard for tracking a college-funding scholarship campaign (2026–27 cycle) for a North Carolina Early College student transferring to a 4-year university with an Associate's degree in hand.

## What it does
- **Scholarship tracker** — every researched award as a card: amount, deadline, eligibility, apply link, and a status you can move through (Not started → In progress → Submitted → Awarded).
- **Filters & sort** — by category, status, search, deadline, amount, or priority. Progress + potential-dollar totals at the top.
- **Built-in funding assistant** — chat with Claude right in the page about deadlines, strategy, or essay drafts. It can also update the tracker for you ("mark Beta Club submitted", "add a scholarship…").

## Running it
Just open `index.html` in a browser — or use the live GitHub Pages URL. All your progress is saved in your browser (localStorage); nothing is uploaded.

### Enabling the chat
1. Click the ⚙️ icon in the assistant panel.
2. Paste your own Anthropic API key (get one at <https://console.anthropic.com>). It's stored **only in your browser** and is never committed or sent anywhere except directly to Anthropic.
3. Optionally paste a private student profile (also browser-only) so the assistant can give tailored advice.
4. Pick a model and Save.

## Privacy
- No student name, GPA, or identifying detail is in the committed files — the public page shows only a generic profile.
- Your API key, private profile notes, and all tracker progress live in your browser's localStorage, not in this repo.
- Keep this repo **private**.

## Files
- `index.html` — the whole app (UI + chat).
- `scholarships.js` — the scholarship dataset (research findings).
- The detailed narrative playbook lives in the parent project folder as a Word document (kept private, not in this repo).

*Data reflects research as of June 2026 for the 2026–27 cycle. Verify amounts and deadlines on each official site before applying — flags are noted on the cards.*
