# Matkailu (Tourism)

18 datasets — 8,055 records

> Browse at [listbase.org/fi/tourism/](https://listbase.org/fi/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Matkailuneuvonta (Tourist Information)](fi-matkailuneuvonta.json) | 2,689 | 285 KB | [CSV](fi-matkailuneuvonta_FI.csv) | [Excel](fi-matkailuneuvonta_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-matkailuneuvonta/) |
| [Lomamokit (Holiday Chalets)](fi-lomamokit.json) | 929 | 94 KB | [CSV](fi-lomamokit_FI.csv) | [Excel](fi-lomamokit_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-lomamokit/) |
| [Suomen hotellit](fi-hotellit.json) | 858 | 91 KB | [CSV](fi-hotellit_FI.csv) | [Excel](fi-hotellit_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-hotellit/) |
| [Suomen nähtävyydet](fi-nahtavyydet.json) | 715 | 74 KB | [CSV](fi-nahtavyydet_FI.csv) | [Excel](fi-nahtavyydet_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-nahtavyydet/) |
| [Autiotuvat (Wilderness Huts)](fi-autiotuvat.json) | 568 | 61 KB | [CSV](fi-autiotuvat_FI.csv) | [Excel](fi-autiotuvat_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-autiotuvat/) |
| [Suomen leirintäalueet](fi-leirintaalueet.json) | 558 | 59 KB | [CSV](fi-leirintaalueet_FI.csv) | [Excel](fi-leirintaalueet_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-leirintaalueet/) |
| [Retkeilypaikat (Picnic Sites)](fi-retkeilypaikat.json) | 335 | 36 KB | [CSV](fi-retkeilypaikat_FI.csv) | [Excel](fi-retkeilypaikat_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-retkeilypaikat/) |
| [Vierasmajat (Guest Houses)](fi-vierasmajat.json) | 316 | 34 KB | [CSV](fi-vierasmajat_FI.csv) | [Excel](fi-vierasmajat_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-vierasmajat/) |
| [Suomen näköalapaikat](fi-nakoalapaikat.json) | 240 | 26 KB | [CSV](fi-nakoalapaikat_FI.csv) | [Excel](fi-nakoalapaikat_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-nakoalapaikat/) |
| [Karavaanialueet (Caravan Sites)](fi-karavaanialueet.json) | 200 | 22 KB | [CSV](fi-karavaanialueet_FI.csv) | [Excel](fi-karavaanialueet_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-karavaanialueet/) |
| [Lomahuoneistot (Tourist Apartments)](fi-lomahuoneistot.json) | 164 | 18 KB | [CSV](fi-lomahuoneistot_FI.csv) | [Excel](fi-lomahuoneistot_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-lomahuoneistot/) |
| [Suomen laskettelurinteet](fi-laskettelurinteet.json) | 159 | 37 KB | [CSV](fi-laskettelurinteet_FI.csv) | [Excel](fi-laskettelurinteet_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-laskettelurinteet/) |
| [Retkeilymajat (Hostels)](fi-retkeilymajat.json) | 124 | 14 KB | [CSV](fi-retkeilymajat_FI.csv) | [Excel](fi-retkeilymajat_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-retkeilymajat/) |
| [Ylläksen laskettelurinteet](fi-yllas-rinteet.json) | 62 | 15 KB | [CSV](fi-yllas-rinteet_FI.csv) | [Excel](fi-yllas-rinteet_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-yllas-rinteet/) |
| [Levin laskettelurinteet](fi-levi-rinteet.json) | 45 | 11 KB | [CSV](fi-levi-rinteet_FI.csv) | [Excel](fi-levi-rinteet_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-levi-rinteet/) |
| [Suomen kansallispuistot](fi-kansallispuistot.json) | 41 | 34 KB | [CSV](fi-kansallispuistot_FI.csv) | [Excel](fi-kansallispuistot_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-kansallispuistot/) |
| [Rukan laskettelurinteet](fi-ruka-rinteet.json) | 37 | 10 KB | [CSV](fi-ruka-rinteet_FI.csv) | [Excel](fi-ruka-rinteet_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-ruka-rinteet/) |
| [Pyhän laskettelurinteet](fi-pyha-rinteet.json) | 15 | 5 KB | [CSV](fi-pyha-rinteet_FI.csv) | [Excel](fi-pyha-rinteet_FI.xlsx) | [View](https://listbase.org/fi/tourism/fi-pyha-rinteet/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/tourism/fi-matkailuneuvonta.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/tourism/)
