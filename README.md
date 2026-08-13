# Available .DEALS One-Word Domains (14,062)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-14%2C062%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .deals one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **14,062 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 14,062 domains · **Median ask:** $13.83 · **High-demand under $2,500:** 2

**Last updated:** 2026-08-13
**Canonical page:** `https://unique.domains/domains/tld/deals`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/deals?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./deals.csv">CSV</a> / <a href="./deals.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DEALS search](https://unique.domains/domains/tld/deals?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DEALS search](https://unique.domains/domains/tld/deals?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DEALS one-word domain catalog.

### Files

- `deals.csv`, public CSV extract (1,000 rows)
- `deals.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/deals-oneword-domains/main/deals.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain     | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ---------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| aug.deals  | available | $5.99     | $50.99        | low            | low    | 3      | name.com          |
| big.deals  | resell    | —         | —             | high           | medium | 3      | GoDaddy.com, LLC  |
| aid.deals  | premium   | $78.54    | $78.54        | medium         | low    | 3      | namesilo          |
| bce.deals  | available | $5.99     | —             | medium         | low    | 3      | name.com          |
| buy.deals  | resell    | —         | —             | medium         | medium | 3      | Spaceship, Inc.   |
| ala.deals  | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo          |
| cry.deals  | available | $5.99     | —             | high           | low    | 3      | name.com          |
| pin.deals  | resell    | —         | —             | high           | low    | 3      | GoDaddy.com, LLC  |
| and.deals  | premium   | $242      | $242          | high           | medium | 3      | namesilo          |
| hum.deals  | available | $5.99     | —             | high           | low    | 3      | name.com          |
| life.deals | resell    | —         | —             | high           | medium | 4      | Spaceship, Inc.   |
| DJI.deals  | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo          |
| les.deals  | available | $5.99     | —             | medium         | low    | 3      | name.com          |
| love.deals | resell    | —         | —             | high           | medium | 4      | Porkbun LLC       |
| gas.deals  | premium   | $260      | $260          | high           | low    | 3      | namecheap         |
| nor.deals  | available | $5.99     | —             | high           | low    | 3      | name.com          |
| mail.deals | resell    | —         | —             | high           | medium | 4      | Sav.com, LLC - 32 |
| hat.deals  | premium   | $78.54    | $78.54        | high           | low    | 3      | namesilo          |
| NWO.deals  | available | $5.99     | —             | medium         | low    | 3      | name.com          |
| rank.deals | resell    | —         | —             | high           | low    | 4      | Porkbun LLC       |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 14,062 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 2 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/deals?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/deals?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list of .deals domain names covers thousands of available, one-word and two-word compound names like whitewater.deals, gingerbread.deals, and primarycare.deals. Most carry a low median ask near $17, making the extension approachable for testing a name before committing to a longer-term brand. Because .deals signals discounts and offers by default, these names tend to fit promo pages, coupon hubs, and niche marketplaces rather than general-purpose brands. When comparing options in this set, focus on how clearly each word pair reads at a glance and whether it still makes sense once shortened to a URL.

- 11,852 available one-word .deals domain names in this set
- Median ask near $17 — low-cost entry for testing ideas
- Everyday compound names like coffeecake and gingerbread
- Ideal for deal, promo, and marketplace-style branding

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DEALS One-Word Domains*. Version 2026-08-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DEALS page](https://unique.domains/domains/tld/deals?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
