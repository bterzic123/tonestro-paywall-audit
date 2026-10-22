# Paywall Audit — tonestro

**Live:** https://bterzic123.github.io/tonestro-paywall-audit/

Four ranked paywall ideas for tonestro, each backed by a number from Adapty's State of Paywalls 2026, a scorecard of the live paywall against the report, and a clickable rebuild of the paywall and the close moment in tonestro's own design (Today / Proposed switch, report pins, EN / DE, light / dark, 30-second walkthrough).

Prepared for the tonestro team by Adapty.

## The ideas

| # | Idea | Report anchor | Outcome |
| :-- | :-- | :-- | :-- |
| 1 | Give the 7-day trial on the first paywall, on Yearly, with the "No payment now" timeline | 5.3 annual-forward layout; 4.3 Education: 80% of buyers buy on the first paywall view; 2.6 / K 7-day trials on annual | ARPU +25–40% (observed in winning A/B tests) |
| 2 | Name their song and instrument in the headline | 3.5 only 2% personalize; 5.3 onboarding personalization | CR +8–17% (observed in winning A/B tests) |
| 3 | Show Monthly, and what Yearly saves (64%) | 2.3 two plan lengths, 67% higher conversion; 3.1 / 3.4 "Save X%" badges | Report finding, no projected range |
| 4 | Turn the close into a price offer (€69.99 instead of €99.99) | 4.5 second-chance paywalls: 4% of apps, 0.88× the main paywall; 2.7 up to 30% off keeps 90% of revenue | ARPU +10–15% (based on Adapty data) |

## Benchmark slice

Education (App Store primary category) · US (tonestro's largest App Store revenue country). Figures the report only splits by category cover all regions. App Store data, Oct 2025–Sep 2026.

## Report

State of Paywalls 2026: https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=tonestro

## Grounding

Prices, the review, the plans and every screen come from tonestro's live iOS app (recorded October 2026, EUR storefront) and its App Store listing. €69.99 is a tonestro Premium price listed in the same storefront. Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for tonestro.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. `?open=proto` opens the prototype directly.
