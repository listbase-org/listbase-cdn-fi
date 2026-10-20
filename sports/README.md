# Urheilu (Sports)

4 datasets — 2,396 records

> Browse at [listbase.org/fi/sports/](https://listbase.org/fi/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Suomen liikuntakeskukset](fi-liikuntakeskukset.json) | 1,706 | 182 KB | [CSV](fi-liikuntakeskukset_FI.csv) | [Excel](fi-liikuntakeskukset_FI.xlsx) | [View](https://listbase.org/fi/sports/fi-liikuntakeskukset/) |
| [Urheilukaupat – Suomi (OpenStreetMap)](fi-osm-shop-sports.json) | 330 | 71 KB | [CSV](fi-osm-shop-sports_FI.csv) | [Excel](fi-osm-shop-sports_FI.xlsx) | [View](https://listbase.org/fi/sports/fi-osm-shop-sports/) |
| [Urheilukaupat (Sports Shops)](fi-urheilukaupat.json) | 311 | 32 KB | [CSV](fi-urheilukaupat_FI.csv) | [Excel](fi-urheilukaupat_FI.xlsx) | [View](https://listbase.org/fi/sports/fi-urheilukaupat/) |
| [Suomen golfkentät](fi-golfkentat.json) | 49 | 16 KB | [CSV](fi-golfkentat_FI.csv) | [Excel](fi-golfkentat_FI.xlsx) | [View](https://listbase.org/fi/sports/fi-golfkentat/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/sports/fi-liikuntakeskukset.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/sports/)
