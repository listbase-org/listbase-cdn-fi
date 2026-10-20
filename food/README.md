# Ruoka (Food & Nutrition)

6 datasets — 8,429 records

> Browse at [listbase.org/fi/food/](https://listbase.org/fi/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Suomen ravintolat - OpenStreetMap (Restaurants in Finland, OSM)](fi-ravintolat.json) | 5,709 | 578 KB | [CSV](fi-ravintolat_FI.csv) | [Excel](fi-ravintolat_FI.xlsx) | [View](https://listbase.org/fi/food/fi-ravintolat/) |
| [Suomen pikaruokapaikat](fi-pikaruokapaikat.json) | 2,196 | 219 KB | [CSV](fi-pikaruokapaikat_FI.csv) | [Excel](fi-pikaruokapaikat_FI.xlsx) | [View](https://listbase.org/fi/food/fi-pikaruokapaikat/) |
| [Suomen leipomot](fi-leipomot.json) | 288 | 31 KB | [CSV](fi-leipomot_FI.csv) | [Excel](fi-leipomot_FI.xlsx) | [View](https://listbase.org/fi/food/fi-leipomot/) |
| [Jaatelobaarit (Ice Cream Parlours)](fi-jaatelobaarit.json) | 136 | 16 KB | [CSV](fi-jaatelobaarit_FI.csv) | [Excel](fi-jaatelobaarit_FI.xlsx) | [View](https://listbase.org/fi/food/fi-jaatelobaarit/) |
| [Suomen lihakaupat - OpenStreetMap (Butchers in Finland, OSM)](fi-lihakaupat.json) | 66 | 8 KB | [CSV](fi-lihakaupat_FI.csv) | [Excel](fi-lihakaupat_FI.xlsx) | [View](https://listbase.org/fi/food/fi-lihakaupat/) |
| [Michelin-ravintolat Suomessa](fi-michelin-ravintolat.json) | 34 | 37 KB | [CSV](fi-michelin-ravintolat_FI.csv) | [Excel](fi-michelin-ravintolat_FI.xlsx) | [View](https://listbase.org/fi/food/fi-michelin-ravintolat/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/food/fi-ravintolat.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/food/)
