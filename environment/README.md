# Ympäristö (Environment)

3 datasets — 789 records

> Browse at [listbase.org/fi/environment/](https://listbase.org/fi/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Voimalaitokset Suomessa](fi-voimalaitokset.json) | 416 | 216 KB | [CSV](fi-voimalaitokset_FI.csv) | [Excel](fi-voimalaitokset_FI.xlsx) | [View](https://listbase.org/fi/environment/fi-voimalaitokset/) |
| [Suomen luonnonsuojelualueet](fi-luonnonsuojelualueet.json) | 367 | 716 KB | [CSV](fi-luonnonsuojelualueet_FI.csv) | [Excel](fi-luonnonsuojelualueet_FI.xlsx) | [View](https://listbase.org/fi/environment/fi-luonnonsuojelualueet/) |
| [Suomen ydinvoimalat](fi-ydinvoimalat.json) | 6 | 5 KB | [CSV](fi-ydinvoimalat_FI.csv) | [Excel](fi-ydinvoimalat_FI.xlsx) | [View](https://listbase.org/fi/environment/fi-ydinvoimalat/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/environment/fi-voimalaitokset.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/environment/)
