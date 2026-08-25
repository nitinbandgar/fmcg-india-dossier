# The Pantry Playbook

A strategy dossier on the Indian FMCG industry and a five-year plan for Tata Consumer Products.

**Live site:** https://nitinbandgar.github.io/fmcg-india-dossier/

## Contents

| Part | Sections |
|---|---|
| Orientation | 00 · Executive summary — thirteen conclusions |
| One · The Industry | 01 Structure & size · 02 The seven forces · 03 How money is made · 04 The consumer · 05 Channels & quick commerce · **06 Channel economics** · 07 Competitive landscape · 08 What it takes to win |
| Two · The Company | 09 TCPL financials · 10 Business-unit teardown · 11 The honest diagnosis (SWOT) |
| Three · The Plan | 12 Defining "number one" · 13 Where to play · 14 The M&A map · **15 Salty snacks: the business case** · 16 How to win: five thrusts · **17 The bridge to FY31** |
| Four · Execution | 18 Eleven function playbooks · **19 Org design & decision rights** · 20 Operating system & KPIs · **21 Scenarios & stress tests** · 22 Risk register · 23 First 100 days · 24 Sources & method |

Sections in **bold** are the analytical additions in the current version.

## What the new sections argue

Three findings from section 17 change the plan, and they are stated as disagreements with the earlier sections rather than quietly reconciled:

1. **The FY31 target was benchmarked against the wrong competitor.** The ₹46,000 crore figure compared TCPL to ITC's *entire* FMCG business, which includes personal care, agarbatti and stationery. Against ITC Foods and Nestlé India, the bar for "number one branded food and beverage" is roughly **₹42,500 crore at a 16% CAGR, not ₹46,000 crore at 18%** — about ₹4,000 crore of acquisitions that no longer need funding.

2. **The base case still finishes second.** Built from the disclosed segments, competent execution of the whole plan lands at ~₹39,800 crore — roughly ₹800 crore behind Nestlé. Leadership turns on moving the growth portfolio from 28% to 32% CAGR, which is worth more than doubling the M&A budget.

3. **18% ROCE and the revenue target are arithmetically incompatible.** An asset bought at 3.5× revenue would need a 63% EBIT margin to earn 18% on that capital. Deploying ₹15,000 crore puts statutory ROCE near 13% by FY31, while the same business *excluding acquisition goodwill* earns 19%. The recommendation is to run and publish both measures rather than pick one.

Section 17 includes an interactive scenario model — seven levers (segment CAGRs, M&A firepower, entry multiple, acquired-asset growth, non-branded divestment) driving FY31 revenue, EBITDA, and both ROCE measures against the Nestlé benchmark.

## About the data

- **Reported figures** come from company disclosures, earnings calls, investor presentations and financial press, current through Q1 FY27 (quarter ended June 2026). Principal figures carry numbered inline citations linking to the source list in section 24.
- **Derived figures** are tagged `Est` / `Derived` — calculated from disclosed ratios and growth rates rather than lifted from a filing.
- **Projections and recommendations** are tagged `Modelled` / `Recommended` — these are analysis, not company guidance.
- **Judgments** are tagged `Judgment` and are intended to be argued with.

Citations are applied only to reported figures. Modelled and judgment material carries a tag instead — a number with neither is an omission worth querying.

Named companies in the M&A and snacks sections are drawn from public information and illustrate archetypes only. Their inclusion implies nothing about availability, valuation or any process.

## Publishing

GitHub Pages serves this from the `main` branch, root folder. `.nojekyll` is included so the files are served as-is without Jekyll processing.

To change the Pages configuration: **Settings → Pages → Source → Deploy from a branch → `main` / `(root)`**.

The page is currently set to `noindex, nofollow`, so it is reachable by link but not indexed by search engines.

## Structure

```
index.html    Self-contained report — all CSS and JS inline
.nojekyll     Bypass Jekyll processing
README.md     This file
```

Typefaces (IBM Plex Sans, IBM Plex Mono, Newsreader) load from Google Fonts with full fallback stacks. Everything else is inline — no build step, no dependencies. The page is theme-aware (light/dark) and carries a print stylesheet, so it exports cleanly to PDF from the browser's print dialog.
