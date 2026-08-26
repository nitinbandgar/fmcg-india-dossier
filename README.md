# The FMCG India Dossier

A strategy dossier on the Indian FMCG industry and a five-year plan for Tata Consumer Products, prepared for the executive committee.

**Live site:** https://nitinbandgar.github.io/fmcg-india-dossier/
**Companion deck:** [FMCG-India-Dossier-Executive-Deck.pptx](FMCG-India-Dossier-Executive-Deck.pptx) — 18 board-ready slides

## How the document is organised

Six tabbed parts, 27 chapters. Each chapter shows its number, heading and overview; the full detail opens on click.

| Tab | Chapters |
|---|---|
| **Start Here** | Executive summary (thirteen conclusions) · The One-Page Brief · Decisions Required |
| **Part One · The Industry** | 01 Structure & size · 02 The seven forces · 03 How money is made · 04 The consumer · 05 Channels & quick commerce · 06 Channel economics · 07 Competitive landscape · 08 What it takes to win |
| **Part Two · The Company** | 09 TCPL financials · 10 Business-unit teardown · 11 The honest diagnosis |
| **Part Three · The Plan** | 12 Defining "number one" · 13 Where to play · 14 The M&A map · 15 Salty snacks: the business case · 16 How to win: five thrusts · 17 The bridge to FY31 |
| **Part Four · Execution** | 18 Eleven function playbooks · 19 Org design & decision rights · 20 Operating system & KPIs · 21 Scenarios & stress tests · 22 Risk register · 23 First 100 days |
| **Reference** | 24 Sources & method |

## Using it

- **Reading paths.** Pick a function — CFO, Marketing, Supply Chain, HR and so on — and chapters outside that path dim rather than disappear.
- **Search.** Press `/` or `Cmd/Ctrl-K`. It indexes every chapter including collapsed ones, which browser Ctrl+F cannot reach.
- **Contents pane** collapses for full-width reading, and the setting is remembered.
- **Deep links.** Any `#anchor` opens the correct tab and expands the correct chapter, so a link to one chapter can be shared directly.
- **Printing.** Print or Save-as-PDF expands every tab and chapter, so nothing is lost. The One-Page Brief is styled to land on its own sheet.

## The three findings that shape the plan

1. **The FY31 target was benchmarked against the wrong competitor.** The ₹46,000 crore figure compared TCPL to ITC's *entire* FMCG business — personal care, agarbatti and stationery included. Against ITC Foods and Nestlé India, the bar is **₹42,500 crore at a 16% CAGR**. Sections 12 and 17 now carry this single reconciled number.

2. **The base case still finishes second.** Built from the disclosed segments, competent execution of the whole plan lands at ~₹39,800 crore — roughly ₹800 crore behind Nestlé. Leadership turns on moving the growth portfolio from 28% to 32% CAGR, worth more than doubling the M&A budget.

3. **18% ROCE and the revenue target are arithmetically incompatible.** An asset bought at 3.5× revenue would need a 63% EBIT margin to earn 18% on that capital. Deploying ₹15,000 crore puts statutory ROCE near 13.5% by FY31, while the same business *excluding acquisition goodwill* earns 18%. The recommendation is to run and publish both.

## Interactive elements

- **FY31 scenario model** (section 17) — seven levers driving revenue, EBITDA and both ROCE measures against the Nestlé benchmark.
- **Value pool map** (section 01) — category size, growth and margin with TCPL's position, filterable.
- **Competitive benchmark** (section 07) — the peer set plotted, three preset views.
- **Channel economics comparator** (section 06) — per-channel waterfall from ₹100 of consumer spend to contribution.
- **Portfolio evolution** (section 09) — FY26–FY31 revenue by segment against the FY31 benchmark line.
- **Decision filter** (Start Here) — the 14 decisions by board vs executive committee, or first 90 days.

## About the data

- **Reported figures** come from company disclosures, earnings calls, investor presentations and financial press, current through Q1 FY27 (quarter ended June 2026). Principal figures carry numbered inline citations linking to the source list in section 24.
- **Derived figures** are tagged `Est` / `Derived`; **projections** `Modelled` / `Recommended`; **judgments** `Judgment`. Every tag carries a hover tooltip explaining what kind of number it marks.
- Citations are applied only to reported figures. A number with neither a citation nor a tag is an omission worth querying.

Named companies in the M&A and snacks sections are drawn from public information and illustrate archetypes only. Their inclusion implies nothing about availability, valuation or any process.

## Publishing

GitHub Pages serves this from `main`, root folder. `.nojekyll` keeps the files served as-is.
Settings → Pages → Source → Deploy from a branch → `main` / `(root)`.

The page is set to `noindex, nofollow` — reachable by link, not indexed by search engines.

## Structure

```
index.html                                Self-contained report — all CSS and JS inline
FMCG-India-Dossier-Executive-Deck.pptx    Companion 18-slide deck
.nojekyll                                 Bypass Jekyll processing
README.md                                 This file
```

Typefaces load from Google Fonts with full fallback stacks. Everything else is inline — no build step, no dependencies. Light and dark themes both supported.
