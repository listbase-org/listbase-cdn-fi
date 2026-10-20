# Koulutus (Education)

5 datasets — 4,491 records

> Browse at [listbase.org/fi/education/](https://listbase.org/fi/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Suomen koulut](fi-koulut.json) | 2,342 | 2374 KB | [CSV](fi-koulut_FI.csv) | [Excel](fi-koulut_FI.xlsx) | [View](https://listbase.org/fi/education/fi-koulut/) |
| [Suomen paivakodit](fi-paivakodit.json) | 1,860 | 203 KB | [CSV](fi-paivakodit_FI.csv) | [Excel](fi-paivakodit_FI.xlsx) | [View](https://listbase.org/fi/education/fi-paivakodit/) |
| [Autokoulut (Driving Schools)](fi-autokoulut.json) | 176 | 20 KB | [CSV](fi-autokoulut_FI.csv) | [Excel](fi-autokoulut_FI.xlsx) | [View](https://listbase.org/fi/education/fi-autokoulut/) |
| [Musiikkikoulut (Music Schools)](fi-musiikkikoulut.json) | 78 | 10 KB | [CSV](fi-musiikkikoulut_FI.csv) | [Excel](fi-musiikkikoulut_FI.xlsx) | [View](https://listbase.org/fi/education/fi-musiikkikoulut/) |
| [Finland — Universities (yliopistot)](fi-yliopistot.json) | 35 | 11 KB | [CSV](fi-yliopistot_FI.csv) | [Excel](fi-yliopistot_FI.xlsx) | [View](https://listbase.org/fi/education/fi-yliopistot/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/education/fi-koulut.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/education/)
