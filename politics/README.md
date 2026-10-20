# Politiikka (Politics)

2 datasets — 423 records

> Browse at [listbase.org/fi/politics/](https://listbase.org/fi/politics/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Valtionvirastot (Government Offices)](fi-valtionvirastot.json) | 410 | 46 KB | [CSV](fi-valtionvirastot_FI.csv) | [Excel](fi-valtionvirastot_FI.xlsx) | [View](https://listbase.org/fi/politics/fi-valtionvirastot/) |
| [Suomen tasavallan presidentit](fi-presidentit.json) | 13 | 12 KB | [CSV](fi-presidentit_FI.csv) | [Excel](fi-presidentit_FI.xlsx) | [View](https://listbase.org/fi/politics/fi-presidentit/) |

## Quick Start

```bash
# List all politics datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="politics") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/politics/fi-valtionvirastot.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/politics/)
