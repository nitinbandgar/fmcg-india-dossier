# The Pantry Playbook

A strategy dossier on the Indian FMCG industry and a five-year plan for Tata Consumer Products.

**Live site:** `https://nitinbandgar.github.io/fmcg-india-dossier/` (once GitHub Pages is enabled)

## Contents

| Part | Sections |
|---|---|
| Orientation | Executive summary — ten conclusions |
| One · The Industry | Structure & size · The seven forces · How money is made · The consumer · Channels & quick commerce · Competitive landscape · What it takes to win |
| Two · The Company | TCPL financials · Business-unit teardown · The honest diagnosis (SWOT) |
| Three · The Plan | Defining "number one" · Where to play · The M&A map · How to win: five thrusts |
| Four · Execution | Eleven function playbooks · Operating system & KPIs · Risk register · First 100 days · Sources & method |

## About the data

- **Reported figures** come from company disclosures, earnings calls, investor presentations and financial press, current through Q1 FY27 (quarter ended June 2026). All sources are linked in the final section.
- **Derived figures** are tagged `Est` / `Derived` — calculated from disclosed ratios and growth rates rather than lifted from a filing.
- **Projections and recommendations** are tagged `Modelled` / `Recommended` — these are analysis, not company guidance.
- **Judgments** are tagged `Judgment` and are intended to be argued with.

Named companies in the M&A section are drawn from public information and illustrate archetypes only. Their inclusion implies nothing about availability, valuation or any process.

## Enabling GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`. Save.
5. The site appears at `https://nitinbandgar.github.io/fmcg-india-dossier/` within a minute or two.

`.nojekyll` is included so GitHub serves the files as-is without running Jekyll.

## Structure

```
index.html    Self-contained report — all CSS and JS inline
.nojekyll     Bypass Jekyll processing
README.md     This file
```

The page loads its typefaces (IBM Plex Sans, IBM Plex Mono, Newsreader) from Google Fonts and has full fallback stacks. Everything else is inline — no build step, no dependencies.
