# ListBase CDN — Suomi (fi)

Open dataset collection for **Suomi** (Finnish).
469 datasets across 18 categories with 490,059 total records.

> Browse and download at [https://listbase.org/fi/](https://listbase.org/fi/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kulttuuri ja uskonto (Culture & Religion)](culture/) | 21 |
| [Koulutus (Education)](education/) | 5 |
| [Viihde (Entertainment)](entertainment/) | 2 |
| [Ympäristö (Environment)](environment/) | 3 |
| [Rahoitus ja kauppa (Finance & Trade)](finance/) | 2 |
| [Ruoka (Food & Nutrition)](food/) | 6 |
| [Maantiede (Geography)](geography/) | 177 |
| [Terveys (Health)](health/) | 7 |
| [Kieli (Language)](language/) | 1 |
| [Politiikka (Politics)](politics/) | 2 |
| [Viitetiedot (Reference)](reference/) | 137 |
| [Tiede (Science)](science/) | 1 |
| [Yhteiskunta (Society)](society/) | 2 |
| [Urheilu (Sports)](sports/) | 4 |
| [Teknologia (Technology)](tech/) | 1 |
| [Aika ja kalenteri (Time & Calendar)](time/) | 5 |
| [Matkailu (Tourism)](tourism/) | 18 |
| [Liikenne (Transport)](transport/) | 75 |

## Usage

### Browse on the web
Visit [listbase.org/fi/](https://listbase.org/fi/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.fi.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.fi.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.fi.listbase.org/geography/th-central-provinces_FI.xlsx
curl -O https://cdn.fi.listbase.org/geography/th-central-provinces_FI.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.fi.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.fi.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_FI.csv   # CSV download
│   └── {dataset}_FI.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
