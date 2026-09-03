# Available .REALTY One-Word Domains (20,142)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-20%2C142%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .realty one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **20,142 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 20,142 domains · **Median ask:** $164.90 · **High-demand under $2,500:** 33

**Last updated:** 2026-09-03
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

- `realty.csv`, public CSV extract (1,000 rows)
- `realty.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/realty-oneword-domains/main/realty.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain      | status    | ask_price | renewal_price | attractiveness | demand | length | registrar          |
| ----------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------ |
| bad.realty  | available | $109.99   | $299          | high           | medium | 3      | namesilo           |
| flow.realty | resell    | —         | —             | high           | medium | 4      | Spaceship, Inc.    |
| art.realty  | premium   | $910      | $1,300        | high           | medium | 3      | namecheap          |
| BBC.realty  | available | $109.99   | $299          | high           | medium | 3      | namesilo           |
| fuck.realty | resell    | —         | —             | high           | high   | 4      | DNC Holdings, Inc. |
| buy.realty  | premium   | $7,875    | $11,250       | medium         | medium | 3      | name.com           |
| bob.realty  | available | $109.99   | $299          | high           | medium | 3      | namesilo           |
| gay.realty  | premium   | $875      | —             | high           | medium | 3      | name.com           |
| btw.realty  | available | $109.99   | $299          | high           | low    | 3      | namesilo           |
| map.realty  | premium   | $4,550    | $6,500        | high           | medium | 3      | namecheap          |
| cap.realty  | available | $109.99   | $299          | high           | low    | 3      | namesilo           |
| tax.realty  | premium   | $875      | —             | high           | medium | 3      | name.com           |
| dad.realty  | available | $109.99   | $299          | high           | low    | 3      | namesilo           |
| usa.realty  | premium   | $7,875    | —             | high           | medium | 3      | name.com           |
| Eid.realty  | available | $109.99   | $299          | high           | low    | 3      | namesilo           |
| bali.realty | premium   | $875      | —             | medium         | medium | 4      | name.com           |
| had.realty  | available | $109.99   | $299          | high           | low    | 3      | namesilo           |
| food.realty | premium   | $910      | $1,300        | high           | medium | 4      | namecheap          |
| ham.realty  | available | $109.99   | $299          | medium         | low    | 3      | namesilo           |
| gift.realty | premium   | $875      | —             | high           | low    | 4      | name.com           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 20,142 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 33 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/realty?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/realty?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=related_pricing)

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

This selection covers one-word .realty domain names built around real estate, property services, and agency branding. Names like fitinto.realty, ladies.realty, gingerbread.realty, and landscaping.realty show the range on offer — from descriptive property terms to warmer, lifestyle-driven words that suit agencies and platforms. With 12,722 domains and a median ask near $221, the set spans a wide price range worth comparing before you settle on one. Whether you're sourcing inventory or picking a name to launch on, weigh price against renewal cost, length, and how easily the word reads as a real estate brand.

- 12,722 .realty domains spanning real estate and property niches
- Median ask near $220.97 for one-word .realty names
- Descriptive names like fitinto.realty, gingerbread.realty
- Weigh pricing and renewal before choosing a .realty name

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .REALTY One-Word Domains*. Version 2026-09-03. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .REALTY page](https://unique.domains/domains/tld/realty?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_realty_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
