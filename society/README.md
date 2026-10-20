# Yhteiskunta (Society)

2 datasets — 165 records

> Browse at [listbase.org/fi/society/](https://listbase.org/fi/society/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Suomen poliisiasemat - OpenStreetMap (Police stations in Finland, OSM)](fi-poliisiasemat.json) | 103 | 13 KB | [CSV](fi-poliisiasemat_FI.csv) | [Excel](fi-poliisiasemat_FI.xlsx) | [View](https://listbase.org/fi/society/fi-poliisiasemat/) |
| [Hyvantekevaisyyskaupat (Charity Shops)](fi-hyvantekevaisyyskaupat.json) | 62 | 8 KB | [CSV](fi-hyvantekevaisyyskaupat_FI.csv) | [Excel](fi-hyvantekevaisyyskaupat_FI.xlsx) | [View](https://listbase.org/fi/society/fi-hyvantekevaisyyskaupat/) |

## Quick Start

```bash
# List all society datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="society") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/society/fi-poliisiasemat.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/society/)
