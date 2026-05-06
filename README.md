# Available .REALTY One-Word Domains (12,702)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C702%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .realty one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,702 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,702 domains · **Median ask:** $260.71 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/realty`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/realty?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./realty.csv">CSV</a> / <a href="./realty.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .REALTY search](https://unique.domains/domains/tld/realty?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .REALTY search](https://unique.domains/domains/tld/realty?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .REALTY one-word domain catalog.

### Files

- `realty.csv` — public CSV extract (1,000 rows)
- `realty.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/realty-oneword-domains/main/realty.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| bot.realty           | premium   | —         | —             | 80             | 58     | 3      | —         |
| air.realty           | premium   | —         | —             | 84             | 48     | 3      | —         |
| tips.realty          | available | $179.99   | —             | 80             | 26     | 4      | name.com  |
| girls.realty         | available | $179.99   | —             | 83             | 23     | 5      | name.com  |
| jewels.realty        | available | $179.99   | —             | 80             | 15     | 6      | name.com  |
| ladies.realty        | available | $179.99   | —             | 80             | 17     | 6      | name.com  |
| popup.realty         | available | $179.99   | —             | 84             | 29     | 6      | name.com  |
| matcha.realty        | available | $179.99   | —             | 86             | 39     | 6      | name.com  |
| edamame.realty       | available | $109.99   | $299          | 80             | 9      | 7      | namesilo  |
| gearup.realty        | available | $179.99   | —             | 80             | 16     | 7      | name.com  |
| keepthechange.realty | available | $179.99   | —             | 46             | 59     | 15     | name.com  |
| online.realty        | premium   | $2,187.50 | —             | 70             | 62     | 7      | name.com  |
| shortcuts.realty     | available | $179.99   | —             | 48             | 41     | 10     | name.com  |
| farmers.realty       | premium   | $875      | —             | 54             | 59     | 7      | name.com  |
| agents.realty        | premium   | $2,187.50 | —             | 56             | 50     | 6      | name.com  |
| whynot.realty        | available | $179.99   | —             | 74             | 39     | 7      | name.com  |
| Books.realty         | premium   | $4,900    | $7,000        | 52             | 49     | 5      | namecheap |
| tokens.realty        | available | $109.99   | $299          | 51             | 36     | 6      | namesilo  |
| maps.realty          | premium   | $4,375    | —             | 56             | 31     | 4      | name.com  |
| tickets.realty       | available | $109.99   | $299          | 64             | 34     | 7      | namesilo  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,702 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/realty?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/realty?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=related_pricing)

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

This set is entirely made up of one-word .realty domains. The names range from broad dictionary terms such as air.realty and tips.realty to more specific or higher-risk strings such as WiFi.realty, Trex.realty, and Chanel.realty. With a median ask of 260.71, these domains sit in a range where selection quality matters more than headline price alone. For founders, the best options are usually clear, memorable words that fit property use cases without confusion. For investors, the stronger candidates are terms with obvious commercial relevance, clean spelling, and limited trademark friction. Renewal cost discipline also matters with niche extensions like .realty.

- Prioritize clear property relevance over novelty
- Use the 260.71 median ask as a pricing anchor
- Check trademark risk on names like Chanel or Trex
- Favor simple, memorable words with clean spelling

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .REALTY One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REALTY page](https://unique.domains/domains/tld/realty?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
