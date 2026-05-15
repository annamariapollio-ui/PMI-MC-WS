# MC Acquisition Workshop — June 2026

A participant-facing web app for the **Multi-Category Acquisition Workshop**, hosted at PMI's Rhodanie Campus in Lausanne, Switzerland on **June 2–3–4, 2026**.

## What's inside

A single-page HTML app with four tabs:

| Tab | Content |
|-----|---------|
| **Participants** | All 20+ attendees grouped by region (R2 MENA, R3 Europe, R4 Americas) with roles, flags and confirmation status |
| **Agenda** | Full 3-day programme with day filter, session types, speakers and descriptions |
| **Logistics** | Venue, dates, visa info, recommended hotels, key contacts and evening programme |
| **How to Prepare** | "Steal With Pride" session brief — the one slide participants need to prepare before arriving |

## Tech

- Pure HTML/CSS/JS — no build step, no dependencies, no framework
- Self-contained in a single `index.html` file
- PMI MC brand palette (dark slate, electric cyan, teal, navy, purple, magenta)
- Google Fonts: Outfit + DM Sans

## Deploy

### GitHub Pages (recommended)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your app will be live at `https://<your-username>.github.io/<repo-name>/`

### Any static host
Upload `index.html` to Netlify, Vercel, or any static hosting — it works as-is.

## Local preview

```bash
open index.html
# or
npx serve .
```

## Content sources

Content is compiled from:
- Market diagnostic interview transcripts (8 markets)
- Workshop agenda Excel (v03)
- Participant list spreadsheet
- Save the Date email logistics
- PMI MC Marketing Master PPT Template 2026 (brand palette)
