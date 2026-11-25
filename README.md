# MVP features dataset: 43 first-version software builds

The headline features of 43 first versions (MVPs) built by the aibrevo team, coded into 19 building blocks, with build time in weeks for each product.

Full write-up, method and charts: https://aibrevo.com/research/mvp-features-43-builds/

## Files

| File | What it is |
|---|---|
| `mvp-features-43-builds.csv` | One row per build: client, product type, industry, platform, weeks to first version, number of published features, marketplace flag, one 0/1 column per building block, and a link to the case study |
| `mvp-features-43-builds.pdf` | The study as a PDF |

## Key findings

- A typical first version had 5 building blocks (median, range 1 to 10).
- The most common blocks: operator dashboard (23 of 43), payments (21), notifications (18), booking or scheduling (17) and search (16).
- Marketplaces are their own shape: 12 of 16 marketplace MVPs took payments, 8 verified their providers and 5 held money in escrow.
- Apps that connected to an outside system took 7.7 weeks on average against 6.8 without.
- Taking payments added no time (7.1 weeks with, 7.2 without).
- Only 4 of 43 named an AI feature, and only 3 named direct messaging between users.

## How the data was made

Source: the published feature lists of 44 builds on aibrevo.com. DAIN has no feature list on its case study and is left out, leaving 43 builds and 247 headline features. Each feature was coded into one or more building blocks based only on what the feature list says. Build-time comparisons use the 41 apps only (the 2 websites are excluded). Coded November 14, 2026.

## About

aibrevo is a software development company in San Francisco, founded in 2021. We build web apps, mobile apps, MVPs and AI apps. https://aibrevo.com
