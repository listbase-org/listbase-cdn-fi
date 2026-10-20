# Terveys (Health)

7 datasets — 2,677 records

> Browse at [listbase.org/fi/health/](https://listbase.org/fi/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Suomen apteekit](fi-apteekit.json) | 754 | 81 KB | [CSV](fi-apteekit_FI.csv) | [Excel](fi-apteekit_FI.xlsx) | [View](https://listbase.org/fi/health/fi-apteekit/) |
| [Suomen terveysasemat ja klinikat - OpenStreetMap (Clinics in Finland, OSM)](fi-terveysasemat.json) | 583 | 64 KB | [CSV](fi-terveysasemat_FI.csv) | [Excel](fi-terveysasemat_FI.xlsx) | [View](https://listbase.org/fi/health/fi-terveysasemat/) |
| [Optikot (Opticians)](fi-optikot.json) | 482 | 49 KB | [CSV](fi-optikot_FI.csv) | [Excel](fi-optikot_FI.xlsx) | [View](https://listbase.org/fi/health/fi-optikot/) |
| [Suomen hammaslaakarit - OpenStreetMap (Dentists in Finland, OSM)](fi-hammaslaakarit.json) | 354 | 40 KB | [CSV](fi-hammaslaakarit_FI.csv) | [Excel](fi-hammaslaakarit_FI.xlsx) | [View](https://listbase.org/fi/health/fi-hammaslaakarit/) |
| [Suomen sairaalat](fi-sairaalat.json) | 239 | 299 KB | [CSV](fi-sairaalat_FI.csv) | [Excel](fi-sairaalat_FI.xlsx) | [View](https://listbase.org/fi/health/fi-sairaalat/) |
| [Fysioterapia (Physiotherapists)](fi-fysioterapia.json) | 166 | 19 KB | [CSV](fi-fysioterapia_FI.csv) | [Excel](fi-fysioterapia_FI.xlsx) | [View](https://listbase.org/fi/health/fi-fysioterapia/) |
| [Suomen laakariasemat - OpenStreetMap (Doctors' practices in Finland, OSM)](fi-laakariasemat.json) | 99 | 12 KB | [CSV](fi-laakariasemat_FI.csv) | [Excel](fi-laakariasemat_FI.xlsx) | [View](https://listbase.org/fi/health/fi-laakariasemat/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/health/fi-apteekit.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/health/)
