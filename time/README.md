# Aika ja kalenteri (Time & Calendar)

5 datasets — 6,844 records

> Browse at [listbase.org/fi/time/](https://listbase.org/fi/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Ahvenanmaan pyhäpäivät ja liputuspäivät – kattava monikielinen (1917–2030)](fi-aland-pyhapaivat-completos.json) | 2,888 | 2168 KB | [CSV](fi-aland-pyhapaivat-completos_FI.csv) | [Excel](fi-aland-pyhapaivat-completos_FI.xlsx) | [View](https://listbase.org/fi/time/fi-aland-pyhapaivat-completos/) |
| [Suomen pyhäpäivät ja liputuspäivät – kattava monikielinen (1917–2030)](fi-pyhapaivat-completos.json) | 2,852 | 2091 KB | [CSV](fi-pyhapaivat-completos_FI.csv) | [Excel](fi-pyhapaivat-completos_FI.xlsx) | [View](https://listbase.org/fi/time/fi-pyhapaivat-completos/) |
| [Suomen pyhäpäivät ja liputuspäivät (2000–2030)](fi-pyhapaivat.json) | 1,050 | 311 KB | [CSV](fi-pyhapaivat_FI.csv) | [Excel](fi-pyhapaivat_FI.xlsx) | [View](https://listbase.org/fi/time/fi-pyhapaivat/) |
| [Ahvenanmaan erityispyhäpäivät (1919–2030)](fi-ahvenanmaan-pyhapaivat.json) | 36 | 22 KB | [CSV](fi-ahvenanmaan-pyhapaivat_FI.csv) | [Excel](fi-ahvenanmaan-pyhapaivat_FI.xlsx) | [View](https://listbase.org/fi/time/fi-ahvenanmaan-pyhapaivat/) |
| [Juhlapyhät ja merkkipäivät Suomessa](fi-juhlapyhat.json) | 18 | 8 KB | [CSV](fi-juhlapyhat_FI.csv) | [Excel](fi-juhlapyhat_FI.xlsx) | [View](https://listbase.org/fi/time/fi-juhlapyhat/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.fi.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.fi.listbase.org/time/fi-aland-pyhapaivat-completos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/fi/time/)
