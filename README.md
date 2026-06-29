# 🏊 SwimSafer Assessment Dashboard

A live assessment tracking dashboard for SwimSafer NYC, covering **21,815 assessments** across 6 stages and 7 swimming complexes from 25 Jul 2025 to 19 Jul 2026.

**[View Live Dashboard →](https://YOUR-USERNAME.github.io/swimsafer-dashboard/)**

---

## 📊 Dashboard Features

- **Overview** — Pass/Fail breakdown by stage with a detailed summary table
- **Timeline** — Monthly and weekly trend analysis across all stages
- **Locations** — Assessment volume by swimming complex
- **Failure Analysis** — Drill-down into failure reasons per stage
- **Assessors** — Pass/Fail breakdown by individual assessor

## 📈 Key Stats

| Metric | Value |
|---|---|
| Total Assessments | 21,815 |
| Overall Pass Rate | 80.6% |
| Total Passed | 17,593 |
| Total Failed | 4,222 |
| Locations | 7 swimming complexes |
| Stages | 6 (Stage 1 → Stage 6 Gold) |

## 🚀 Deployment

This dashboard is a single self-contained HTML file hosted via **GitHub Pages**. No build step or server is required.

### How to update the dashboard

1. Replace `index.html` with your new export
2. Commit and push to the `main` branch
3. GitHub Pages auto-deploys within ~60 seconds

## 🛠 Tech Stack

- **Plotly.js 2.35** — interactive charts
- **Vanilla JS** — tab switching, filter logic
- **Google Fonts** — DM Sans + JetBrains Mono
- Pure HTML/CSS — zero framework dependencies

## 📁 Repository Structure

```
swimsafer-dashboard/
├── index.html        # Main dashboard (self-contained)
├── README.md         # This file
└── .github/
    └── workflows/
        └── pages.yml # Auto-deploy to GitHub Pages
```

---

*Dashboard last updated: June 2025*
