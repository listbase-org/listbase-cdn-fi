# Tiede (Science)

1 datasets — 226 records

> Browse at [listbase.org/fi/science/](https://listbase.org/fi/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Suomen elainlaakarit - OpenStreetMap (Veterinary clinics in Finland, OSM)](fi-elainlaakarit.json) | 226 | 26 KB | [CSV](fi-elainlaakarit_FI.csv) | [Excel](fi-elainlaakarit_FI.xlsx) | [View](https://listbase.org/fi/science/fi-elainlaakarit/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/science/fi-elainlaakarit.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/science/)
