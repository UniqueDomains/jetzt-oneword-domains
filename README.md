# Available .JETZT One-Word Domains (12,373)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C373%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .jetzt one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,373 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,373 domains · **Median ask:** $136.56 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-11  
**Canonical page:** `https://unique.domains/domains/tld/jetzt`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/jetzt?utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./jetzt.csv">CSV</a> / <a href="./jetzt.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .JETZT search](https://unique.domains/domains/tld/jetzt?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .JETZT search](https://unique.domains/domains/tld/jetzt?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .JETZT one-word domain catalog.

### Files

- `jetzt.csv` — public CSV extract (1,000 rows)
- `jetzt.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/jetzt-oneword-domains/main/jetzt.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price   | renewal_price | attractiveness | demand | length | registrar                |
| ------------- | --------- | ----------- | ------------- | -------------- | ------ | ------ | ------------------------ |
| Acup.jetzt    | available | $30.48      | —             | 80             | 5      | 5      | namecheap                |
| homes.jetzt   | available | $9.99       | —             | 86             | 34     | 5      | name.com                 |
| finals.jetzt  | available | $9.99       | —             | 80             | 7      | 6      | name.com                 |
| jewels.jetzt  | available | $9.99       | —             | 80             | 15     | 6      | name.com                 |
| forces.jetzt  | available | $9.99       | —             | 82             | 12     | 6      | name.com                 |
| geton.jetzt   | available | $9.99       | —             | 82             | 10     | 6      | name.com                 |
| Apples.jetzt  | available | $30.48      | —             | 90             | 16     | 6      | namecheap                |
| toneup.jetzt  | available | $9.99       | —             | 80             | 5      | 7      | name.com                 |
| makeit.jetzt  | available | $9.99       | —             | 82             | 22     | 7      | name.com                 |
| stirup.jetzt  | available | $9.99       | —             | 82             | 3      | 7      | name.com                 |
| dogsick.jetzt | available | $9.99       | —             | 90             | 1      | 7      | name.com                 |
| leaveon.jetzt | available | $9.99       | —             | 80             | 1      | 8      | name.com                 |
| Books.jetzt   | available | $30.48      | —             | 52             | 49     | 5      | namecheap                |
| forum.jetzt   | resell    | —           | —             | 72             | 36     | 5      | Vautron Rechenzentrum AG |
| cars.jetzt    | premium   | $447,608.34 | —             | 66             | 47     | 4      | Porkbun LLC              |
| robots.jetzt  | available | $9.99       | —             | 62             | 47     | 6      | name.com                 |
| camping.jetzt | resell    | —           | —             | 80             | 31     | 7      | Vautron Rechenzentrum AG |
| tickets.jetzt | premium   | $118.80     | $118.80       | 64             | 34     | 7      | namesilo                 |
| Ryan.jetzt    | available | $30.48      | —             | 60             | 44     | 4      | namecheap                |
| led.jetzt     | resell    | —           | —             | 78             | 31     | 3      | Vautron Rechenzentrum AG |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,373 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/jetzt?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/jetzt?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=related_pricing)

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

This selection is defined by a single trait: every domain uses the .jetzt extension and consists of a single word. That creates a broad mix, from plain dictionary terms such as tips.jetzt and movies.jetzt to shorter invented or ambiguous names such as Acup.jetzt and barup.jetzt. For founders, the main question is whether the word is memorable, easy to explain, and strong enough to carry a less common extension. For investors, the key is entry price discipline around the 136.56 median ask, plus whether the keyword has enough commercial clarity to support resale interest. In both cases, the best choices are simple, readable, and specific without creating obvious trademark friction.

- All names in this selection use the .jetzt extension
- Median ask is 136.56 across 12,372 listed domains
- Prioritize clear words over obscure or awkward terms
- Check trademark overlap before valuing brandability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .JETZT One-Word Domains*. Version 2026-05-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .JETZT page](https://unique.domains/domains/tld/jetzt?utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_jetzt_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
