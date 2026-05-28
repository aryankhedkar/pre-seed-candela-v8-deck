# Candela · Pre-Seed Deck · v8

Twenty slides on the new product thesis, framed as the question the hiring manager is already losing sleep over: **your junior is using Claude shamelessly, so how do you know which of them can do the job?**

Companion deck to [v7](https://github.com/aryankhedkar/pre-seed-candela-v7-deck). Team, market, model, competition, secrets, ask and close from v7 stand as-is. This deck replaces the problem and product story that sits under them, after Nadal's mentorship session on what hiring on Candela should look like end to end for both sides.

## What changed from v7

- **Frame:** addressed directly to the hiring manager, around the question competence reduces to in 2026: who is thinking with the model, and who is just letting it ship?
- **Product:** Candela is no longer "credentialed projects + a thinking partner for students" alone. v8 reframes it as the assessment-is-the-application platform: a JD becomes a real project the candidate ships before they apply.
- **Hiring manager UX:** paste a JD, the platform reads it and generates a structured project with milestones, scaffolding and rubric. Each company gets a branded portal page. Submissions land on a per-job pipeline with AI-scored shortlist.
- **Candidate UX:** discovers a role through the company portal, sees the project they would build with the salary and a 24-hour window, builds inside the existing Candela workspace with the thinking partner, ships, gets scored, gets surfaced.

## Files

| File | Notes |
|---|---|
| `index.html` | The 20-slide deck. Arrow keys, space, click, or type a slide number to navigate. Append `?print=1` for a stacked print mode. |
| `PITCH_PACK.md` | 7-minute walkthrough script, Q&A, numbers to know cold, pre-meeting checklist. |
| `assets/` | Favicon, OG card, wordmark and headshot reused from v7. |

## Run locally

```bash
python3 -m http.server 5180
# open http://localhost:5180
```

## Deploy

`vercel deploy --prod` from this directory ships the deck as a static site, the same way v7 lives at pre-seed-candela-v7-deck.vercel.app.

## Stack

- Single static HTML, Newsreader (serif), JetBrains Mono, design tokens inline. No build step.
- Light theme only (employer reading room).
- Print mode via `?print=1`, which exports cleanly to PDF via the browser's "Save as PDF" at 14in × 7.875in.
