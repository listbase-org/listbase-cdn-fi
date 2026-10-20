# Teknologia (Technology)

1 datasets — 510 records

> Browse at [listbase.org/fi/tech/](https://listbase.org/fi/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Kirjastot Suomessa](fi-kirjasto.json) | 510 | 568 KB | [CSV](fi-kirjasto_FI.csv) | [Excel](fi-kirjasto_FI.xlsx) | [View](https://listbase.org/fi/tech/fi-kirjasto/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/tech/fi-kirjasto.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/tech/)
