# Félix Silvestrini — Capability Statement Landing Page

Strategic Real Estate Advisory · Puerto Rico
Lic. C-23200 · Keller Williams Puerto Rico

A boutique landing page built around the printed Capability Statement (PDF), designed for institutional review, USACE industry outreach events, and direct sharing with investors, developers, and infrastructure stakeholders.

**Live site:** [https://fsilver79.github.io/capability-statement](https://fsilver79.github.io/capability-statement)

---

## Structure

```
.
├── index.html                              # The landing page (single file, no build step)
├── assets/
│   └── Felix_Silvestrini_Capability_Statement.pdf
├── README.md
└── .nojekyll                               # Tells GitHub Pages to serve files as-is
```

## What's on the page

- **Hero** — Brand introduction with capability statement stamp + download CTA
- **About Félix** — Practice positioning, credentials, languages
- **Capability Statement** — The full PDF embedded inline with download options
- **Core Capabilities** — Three pillars (Advisory, Investor Support, Workforce Housing)
- **Featured Engagement** — Dial Solar Puerto Rico case study
- **Industries Served + Differentiators** — Split layout
- **Contact** — Form (mailto-based) + WhatsApp direct button

## Local preview

```bash
# From the project root, run any local server:
python3 -m http.server 8000
# Then open http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a new repository named `capability-statement` on GitHub
2. Push the contents of this folder to the `main` branch
3. In repo settings → Pages, set source to `main` branch, `/` (root)
4. Site will be live at `https://fsilver79.github.io/capability-statement` within 1–2 minutes

```bash
git init
git add .
git commit -m "Initial commit: capability statement landing page"
git branch -M main
git remote add origin https://github.com/fsilver79/capability-statement.git
git push -u origin main
```

## Updating the PDF

Replace `assets/Felix_Silvestrini_Capability_Statement.pdf` with the new version (keep the same filename) and push the change. The site will update automatically.

## Color palette

| Token            | Hex       | Use                                          |
|------------------|-----------|----------------------------------------------|
| Black            | `#1F1F1F` | Nav, hero, engagement, footer                |
| Black soft       | `#2C2C2C` | Secondary dark surfaces                      |
| Champagne        | `#D7BE84` | Accents over dark backgrounds                |
| Champagne deep   | `#A8884A` | Accents over light backgrounds (legibility)  |
| Cream            | `#F5F2EC` | Light section backgrounds                    |
| Beige            | `#E8E1D5` | Document section background                  |
| Paper            | `#FAF8F3` | Body / card backgrounds                      |

## Type

- **Display:** Fraunces (serif) — headlines, large numerals, italic accents
- **Body:** Archivo (sans-serif) — paragraphs, navigation, controls
- **Utility:** Archivo Narrow — eyebrows, labels, small caps lockups

---

© 2026 Félix Silvestrini Real Estate · All Rights Reserved
