# Rahoitus ja kauppa (Finance & Trade)

2 datasets — 3,010 records

> Browse at [listbase.org/fi/finance/](https://listbase.org/fi/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Suomen kahvilat - OpenStreetMap (Cafes in Finland, OSM)](fi-kahvilat.json) | 2,662 | 272 KB | [CSV](fi-kahvilat_FI.csv) | [Excel](fi-kahvilat_FI.xlsx) | [View](https://listbase.org/fi/finance/fi-kahvilat/) |
| [Suomen pankkiautomaatit - OpenStreetMap (ATMs in Finland, OSM)](fi-pankkiautomaatit.json) | 348 | 34 KB | [CSV](fi-pankkiautomaatit_FI.csv) | [Excel](fi-pankkiautomaatit_FI.xlsx) | [View](https://listbase.org/fi/finance/fi-pankkiautomaatit/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/finance/fi-kahvilat.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/finance/)
