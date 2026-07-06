# Available .CAT One-Word Domains (66)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-67%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-66%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated dataset of available and resale .cat one-word domains from Unique Domains.

> **Note:** this repository currently mirrors the full live catalog for this exact search.
> Unique Domains counts can still change as the search refreshes.

**Public extract:** 67 rows · **Live catalog:** 66 domains · **Median ask:** $26.98 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-06
**Canonical page:** `https://unique.domains/domains/tld/cat`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/cat?utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./cat.csv">CSV</a> / <a href="./cat.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .CAT search](https://unique.domains/domains/tld/cat?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .CAT search](https://unique.domains/domains/tld/cat?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .CAT one-word domain catalog.

### Files

- `cat.csv`, public CSV extract (67 rows)
- `cat.json`, public JSON extract (67 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/cat-oneword-domains/main/cat.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| dogsledmail.cat   | available | $26.98    | $38.98        | high           | low    | 12     | namecheap |
| gearup.cat        | available | $26.98    | $38.98        | high           | low    | 7      | namecheap |
| midafternoon.cat  | available | $26.98    | $38.98        | high           | low    | 12     | namecheap |
| barup.cat         | available | $26.98    | $38.98        | high           | low    | 6      | namecheap |
| preferences.cat   | available | $26.98    | $38.98        | high           | low    | 11     | namecheap |
| FinalFour.cat     | available | $26.98    | $38.98        | high           | low    | 10     | namecheap |
| mealsonwheels.cat | available | $26.98    | $38.98        | high           | low    | 15     | namecheap |
| axes.cat          | available | $26.98    | $38.98        | low            | low    | 4      | namecheap |
| Jews.cat          | available | $26.98    | $38.98        | medium         | low    | 4      | namecheap |
| says.cat          | available | $26.98    | $38.98        | medium         | low    | 4      | namecheap |
| seas.cat          | available | $26.98    | $38.98        | medium         | low    | 4      | namecheap |
| sees.cat          | available | $26.98    | $38.98        | medium         | low    | 4      | namecheap |
| draws.cat         | available | $26.98    | $38.98        | medium         | low    | 5      | namecheap |
| cypher.cat        | available | $26.98    | $38.98        | low            | medium | 6      | namecheap |
| goape.cat         | available | $26.98    | $38.98        | high           | low    | 6      | namecheap |
| nuclei.cat        | available | $26.98    | $38.98        | medium         | low    | 6      | namecheap |
| tapon.cat         | available | $26.98    | $38.98        | medium         | low    | 6      | namecheap |
| actions.cat       | available | $26.98    | $38.98        | medium         | low    | 7      | namecheap |
| couples.cat       | available | $26.98    | $38.98        | medium         | low    | 7      | namecheap |
| results.cat       | available | $26.98    | $38.98        | medium         | low    | 7      | namecheap |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract        | Unique Domains                             |
| --------------------- | ------------------------------------------ |
| 67-row public sample  | 66 live domains                            |
| Static CSV / JSON     | live search and daily refresh              |
| Basic exported fields | 0 high-demand names under $2,500           |
| No persistence        | Radar, saved search, and alerts            |
| No founder workflow   | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/cat?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/cat?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=related_pricing)

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

This selection covers 66 one-word domain names registered under the .cat extension, a sponsored top-level domain tied to Catalan language and culture. Names in this set range from short compounds such as gearup.cat and barup.cat to longer phrases such as mealsonwheels.cat and dogsledmail.cat, spanning everyday vocabulary rather than a single industry. With a median ask of $26.98, this .cat selection offers a low-cost way to compare single-token names before deciding which, if any, fit a specific project or portfolio.

- 66 one-word .cat domain names in this selection
- Median ask of $26.98 across this selection
- Single-token names are easier to brand and pitch
- A niche, sponsored TLD tied to Catalan identity

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .CAT One-Word Domains*. Version 2026-07-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .CAT page](https://unique.domains/domains/tld/cat?utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_cat_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
