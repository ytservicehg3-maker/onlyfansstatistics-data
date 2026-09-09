# OnlyFans Statistics — open data & charts

Machine-readable data and 39 ready-made charts behind **[onlyfansstatistics.com](https://onlyfansstatistics.com)**, the independent OnlyFans data hub. Everything here is free to reuse under **CC BY-SA 4.0** — credit *onlyfansstatistics.com* and link back.

| Headline (FY2024, audited) | Value |
|---|---|
| Gross fan payments | $7.22B |
| Creator payouts | $5.80B |
| Platform net revenue | $1.41B |
| Pre-tax profit | $684M |
| Creator accounts | 4,634,000 |
| Fan accounts (cumulative) | 377,500,000 |

Source: Fenix International Ltd, FY2024 accounts filed with UK Companies House (company no. 10354575). FY2025 accounts are overdue since 1 September 2026 — the site tracks the filing live at [/onlyfans-annual-report](https://onlyfansstatistics.com/onlyfans-annual-report).

## What is in this repository

| Path | Content |
|---|---|
| `data/stats.json` | Platform-wide figures: revenue, creators, fans, geography, demographics, corporate structure, compliance reports, timeline (schema 1.1.0, generated 2026-07-12) |
| `data/creator-stats.json` | Creator listing & engagement dataset: 100,200 public profiles across 1,057 niches, collected 2026-06 with [bestonlyfansreviews.com](https://bestonlyfansreviews.com) — pricing, reach, content library, 37 curated niche profiles, creator ages |
| `data/csv/` | 18 CSV exports of the tables above |
| `charts/` | 39 SVG charts (1200 px, dark theme, licence metadata embedded) |

The same files are served live and CORS-enabled from the site: `https://onlyfansstatistics.com/data/stats.json`, `/data/creator-stats.json`, `/data/csv/<name>.csv`, `/assets/charts/<name>.svg`.

## Charts

- [`age-distribution.svg`](charts/age-distribution.svg) — OnlyFans users by age bracket
- [`ai-creators-share.svg`](charts/ai-creators-share.svg) — AI-generated creator share of new OnlyFans accounts
- [`bot-share.svg`](charts/bot-share.svg) — OnlyFans bot subscriber share
- [`ceo-timeline.svg`](charts/ceo-timeline.svg) — OnlyFans leadership, 2016–2026: who ran it and who owned it
- [`creator-age-distribution.svg`](charts/creator-age-distribution.svg) — OnlyFans creator age distribution
- [`creator-growth.svg`](charts/creator-growth.svg) — OnlyFans creator accounts (cumulative)
- [`creator-likes-lorenz.svg`](charts/creator-likes-lorenz.svg) — Like concentration among OnlyFans creators
- [`creator-price-distribution.svg`](charts/creator-price-distribution.svg) — OnlyFans subscription price distribution
- [`creator-reach-distribution.svg`](charts/creator-reach-distribution.svg) — OnlyFans creator reach: total likes per profile
- [`creators-by-country.svg`](charts/creators-by-country.svg) — Where OnlyFans creators actually live
- [`cvi-score-anatomy.svg`](charts/cvi-score-anatomy.svg) — Creator Velocity Index™: how revenue and cadence become a 0–100 score
- [`digital-intimacy-forecast-2030.svg`](charts/digital-intimacy-forecast-2030.svg) — Digital intimacy industry forecast 2025-2030
- [`digital-intimacy-spending-comparison.svg`](charts/digital-intimacy-spending-comparison.svg) — Annual digital intimacy spend per user — 2025
- [`dm-reply-rate.svg`](charts/dm-reply-rate.svg) — OnlyFans DM reply rate declining from 67% in 2023 to 38% in 2025 — a -43% relative decline over 24 months
- [`dmca-requests.svg`](charts/dmca-requests.svg) — What OnlyFans receives: legal & IP requests — June 2026
- [`es-cadence-reach.svg`](charts/es-cadence-reach.svg) — Engagement Signal™: cadence bands and the reach of 100,200 creators
- [`fan-creator-ratio.svg`](charts/fan-creator-ratio.svg) — Fan-to-creator ratio over time
- [`fenix-filing-timing.svg`](charts/fenix-filing-timing.svg) — Fenix International (OnlyFans): accounts filed vs. the 31 August deadline, FY2020–FY2025
- [`gender-split.svg`](charts/gender-split.svg) — OnlyFans users by gender
- [`gfe-market-share.svg`](charts/gfe-market-share.svg) — Girlfriend Experience (GFE) market: digital vs physical 2023-2025
- [`income-distribution.svg`](charts/income-distribution.svg) — OnlyFans creator income — the long tail
- [`indices-overview.svg`](charts/indices-overview.svg) — OnlyFans Creator Indices: the four scales at a glance
- [`mid-tier-collapse.svg`](charts/mid-tier-collapse.svg) — Mid-tier OnlyFans creator median monthly income declining from $4
- [`money-flow.svg`](charts/money-flow.svg) — Where each $1 a fan pays actually lands
- [`niche-earnings.svg`](charts/niche-earnings.svg) — OnlyFans monthly earnings by niche
- [`npi-niche-medians.svg`](charts/npi-niche-medians.svg) — Niche Position Index™: median subscription price in 37 OnlyFans niches
- [`platform-fees.svg`](charts/platform-fees.svg) — Creator platform fees comparison
- [`posting-cadence-engagement.svg`](charts/posting-cadence-engagement.svg) — OnlyFans engagement curve peaking at 7 posts per week
- [`profit-margin.svg`](charts/profit-margin.svg) — OnlyFans revenue vs pre-tax profit
- [`revenue-by-year.svg`](charts/revenue-by-year.svg) — OnlyFans gross fan payments by year
- [`revenue-streams.svg`](charts/revenue-streams.svg) — OnlyFans revenue streams (estimated breakdown)
- [`rms-mix-anatomy.svg`](charts/rms-mix-anatomy.svg) — Revenue Mix Score™: what typical income mixes score, and why mix matters
- [`safety-deactivations-trend.svg`](charts/safety-deactivations-trend.svg) — OnlyFans safety enforcement: monthly account deactivations (2026)
- [`timeline.svg`](charts/timeline.svg) — OnlyFans timeline — major milestones
- [`top-earners.svg`](charts/top-earners.svg) — Top reported OnlyFans earners — peak monthly figures
- [`top-spending-2025.svg`](charts/top-spending-2025.svg) — Top OnlyFans spending countries 2025
- [`uk-market.svg`](charts/uk-market.svg) — OnlyFans in the UK — at a glance
- [`user-growth.svg`](charts/user-growth.svg) — OnlyFans fan accounts (cumulative)
- [`users-by-country.svg`](charts/users-by-country.svg) — OnlyFans traffic share by country

Every chart also exists as an embeddable widget with a live attribution footer — see [onlyfansstatistics.com/widgets](https://onlyfansstatistics.com/widgets):

```html
<iframe src="https://onlyfansstatistics.com/embed/revenue" width="100%" height="500" loading="lazy" frameborder="0" style="border:0;border-radius:10px;max-width:700px;display:block;margin:auto;" title="OnlyFans gross fan payments by year"></iframe>
```

## Sources

- Fenix International Ltd — UK Companies House filing FY2024
- Companies House — Fenix International Ltd PSC & officer filings (March–July 2026)
- Press coverage of the Architect Capital minority-stake deal (NY Post, Bloomberg, Axios — 8 May 2026)
- Similarweb traffic data (June 2026)
- Semrush traffic panel (June 2026, device split)
- Statista
- NCMEC CyberTipline reports
- OnlyFans Transparency Center — monthly reports through June 2026

Full sourcing notes: [onlyfansstatistics.com/sources](https://onlyfansstatistics.com/sources) · methodology: [onlyfansstatistics.com/methodology](https://onlyfansstatistics.com/methodology).

## Caveats

- `creator-stats.json` holds listing and engagement aggregates (subscription price, free/paid status, content counts, like totals). It is **not** earnings data — OnlyFans publishes no per-creator earnings. Directory-listed creators skew active and discoverable versus the full registered creator base.
- Estimates are labelled as such in the JSON (`*_estimated` keys, `caveat` fields). Audited figures carry the `fenix-2024-filing` source id.

## Updates, questions, corrections

Data refreshes land here when the site updates (the FY2025 filing will be added on the day it appears at Companies House). Use **[Discussions](../../discussions)** for questions and corrections, **Issues** for errors in a file.

## Licence

Data, CSV files and charts: [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/) — see [LICENSE](LICENSE) (full legal text) and [NOTICE.md](NOTICE.md). Suggested credit: *Source: onlyfansstatistics.com (CC BY-SA 4.0)*, linked to https://onlyfansstatistics.com. Licence page with ready-made credit lines: [onlyfansstatistics.com/license](https://onlyfansstatistics.com/license).
