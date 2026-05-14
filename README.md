# Available .SHOPPING One-Word Domains (12,224)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C224%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .shopping one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,224 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,224 domains · **Median ask:** $23.27 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
**Canonical page:** `https://unique.domains/domains/tld/shopping`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/shopping?utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./shopping.csv">CSV</a> / <a href="./shopping.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .SHOPPING search](https://unique.domains/domains/tld/shopping?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .SHOPPING search](https://unique.domains/domains/tld/shopping?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .SHOPPING one-word domain catalog.

### Files

- `shopping.csv` — public CSV extract (1,000 rows)
- `shopping.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/shopping-oneword-domains/main/shopping.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain            | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                    |
| ----------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------- |
| Acup.shopping     | available | $37.98    | —             | 80             | 5      | 5      | namecheap                    |
| barup.shopping    | available | $14.99    | —             | 82             | 2      | 6      | name.com                     |
| forces.shopping   | available | $14.99    | —             | 82             | 12     | 6      | name.com                     |
| Apples.shopping   | available | $37.98    | —             | 90             | 16     | 6      | namecheap                    |
| dogsit.shopping   | available | $14.99    | —             | 96             | 2      | 6      | name.com                     |
| edamame.shopping  | available | $14.99    | —             | 80             | 9      | 7      | name.com                     |
| QandA.shopping    | available | $37.98    | —             | 80             | 10     | 7      | namecheap                    |
| toneup.shopping   | available | $14.99    | —             | 80             | 5      | 7      | name.com                     |
| leaveon.shopping  | available | $14.99    | —             | 80             | 1      | 8      | name.com                     |
| presents.shopping | available | $14.99    | —             | 80             | 9      | 8      | name.com                     |
| headout.shopping  | available | $14.99    | —             | 82             | 6      | 8      | name.com                     |
| Ryan.shopping     | available | $37.98    | —             | 60             | 44     | 4      | namecheap                    |
| prompts.shopping  | resell    | —         | —             | 54             | 39     | 7      | Dynadot Inc                  |
| Tools.shopping    | premium   | $560      | $560          | 56             | 40     | 5      | namecheap                    |
| whynot.shopping   | available | $14.99    | —             | 74             | 39     | 7      | name.com                     |
| ties.shopping     | resell    | —         | —             | 59             | 9      | 4      | TLD Registrar Solutions Ltd. |
| events.shopping   | premium   | $500      | —             | 68             | 37     | 6      | name.com                     |
| emoji.shopping    | available | $14.99    | —             | 88             | 38     | 5      | name.com                     |
| rewards.shopping  | premium   | $242      | $242          | 62             | 30     | 7      | namesilo                     |
| stories.shopping  | available | $14.99    | —             | 58             | 36     | 7      | name.com                     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,224 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/shopping?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/shopping?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=related_pricing)

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

This selection is entirely focused on one-word .shopping domains. The set includes dictionary-like words, personal names, verbs, and short coined forms such as Acup.shopping, Cindy.shopping, Trex.shopping, getup.shopping, and useit.shopping. For founders, the main question is whether the word is memorable, relevant to commerce, and easy to say without extra explanation. For investors, the first pass is pricing discipline: the median ask is 23.27, so stronger terms should justify any premium through clarity, breadth, and resale potential. When comparing these domains, weigh category fit, spelling simplicity, and the risk of third-party brand conflicts before treating a name as ownable.

- One-word .shopping domains across names, verbs, and broad terms
- Median ask is 23.27 across 12,222 listed domains
- Favor clear spelling and broad commerce relevance
- Check brand conflict risk before treating a name as ownable

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .SHOPPING One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .SHOPPING page](https://unique.domains/domains/tld/shopping?utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_shopping_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
