# Available .DEALS One-Word Domains (11,849)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C849%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .deals one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,849 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,849 domains · **Median ask:** $14.84 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-08  
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

- `deals.csv` — public CSV extract (1,000 rows)
- `deals.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/deals-oneword-domains/main/deals.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                  |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------- |
| barup.deals     | available | $5.99     | —             | 82             | 2      | 6      | name.com                   |
| forces.deals    | available | $5.99     | —             | 82             | 12     | 6      | name.com                   |
| Apples.deals    | available | $51.98    | —             | 90             | 16     | 6      | namecheap                  |
| hangon.deals    | available | $5.99     | —             | 82             | 6      | 7      | name.com                   |
| pierogi.deals   | available | $5.99     | —             | 82             | 7      | 7      | name.com                   |
| stirup.deals    | available | $5.99     | —             | 82             | 3      | 7      | name.com                   |
| presents.deals  | available | $5.99     | —             | 80             | 9      | 8      | name.com                   |
| Snickers.deals  | available | $51.98    | —             | 80             | 10     | 8      | namecheap                  |
| prompts.deals   | available | $5.99     | —             | 54             | 39     | 7      | name.com                   |
| robots.deals    | resell    | —         | —             | 62             | 47     | 6      | Squarespace Domains II LLC |
| jobs.deals      | premium   | $123.75   | —             | 79             | 42     | 4      | name.com                   |
| justin.deals    | available | $5.99     | —             | 58             | 38     | 7      | name.com                   |
| coffee.deals    | resell    | —         | —             | 76             | 43     | 6      | Dynadot Inc                |
| lets.deals      | premium   | $123.75   | —             | 77             | 39     | 4      | name.com                   |
| Cats.deals      | available | $51.98    | —             | 59             | 33     | 4      | namecheap                  |
| closeout.deals  | resell    | —         | —             | 76             | 6      | 9      | GoDaddy.com, LLC           |
| partners.deals  | premium   | $250      | —             | 61             | 32     | 8      | name.com                   |
| teams.deals     | available | $5.99     | —             | 62             | 32     | 5      | name.com                   |
| solutions.deals | premium   | $123.75   | —             | 56             | 31     | 9      | name.com                   |
| William.deals   | available | $51.98    | —             | 74             | 31     | 7      | namecheap                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,849 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/deals?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/deals?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection focuses only on one-word domains under the .deals extension. The set includes short keyword-led names such as Acup.deals, Trex.deals, WiFi.deals, finals.deals, and jewels.deals. For founders, the main question is whether the word is instantly clear, easy to remember, and commercially credible with .deals. For investors, the key test is whether the keyword has broad buyer relevance and enough specificity to support resale interest. With a median ask of 14.84, price is accessible, but quality still varies widely by word strength, category fit, and potential trademark friction.

- Prefer clear commercial words that fit .deals naturally
- Short, familiar words are easier to remember and compare
- Check trademark exposure on branded or distinctive terms
- Use median ask 14.84 as a price discipline reference

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DEALS One-Word Domains*. Version 2026-05-08. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DEALS page](https://unique.domains/domains/tld/deals?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_deals_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
