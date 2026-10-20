# Viihde (Entertainment)

2 datasets — 2,467 records

> Browse at [listbase.org/fi/entertainment/](https://listbase.org/fi/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Suomalaiset elokuvat (Finnish films)](fi-elokuvat.json) | 2,280 | 20072 KB | [CSV](fi-elokuvat_FI.csv) | [Excel](fi-elokuvat_FI.xlsx) | [View](https://listbase.org/fi/entertainment/fi-elokuvat/) |
| [Kirjakaupat (Bookshops)](fi-kirjakaupat.json) | 187 | 21 KB | [CSV](fi-kirjakaupat_FI.csv) | [Excel](fi-kirjakaupat_FI.xlsx) | [View](https://listbase.org/fi/entertainment/fi-kirjakaupat/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/entertainment/fi-elokuvat.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/entertainment/)
