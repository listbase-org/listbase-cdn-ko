# ListBase CDN — 한국어 (ko)

Open dataset collection for **한국어** (Korean).
414 datasets across 16 categories with 444,693 total records.

> Browse and download at [https://listbase.org/ko/](https://listbase.org/ko/)

## Categories

| Category | Datasets |
|----------|----------|
| [문화와 종교 (Culture & Religion)](culture/) | 13 |
| [교육 (Education)](education/) | 37 |
| [엔터테인먼트 (Entertainment)](entertainment/) | 17 |
| [환경 (Environment)](environment/) | 4 |
| [금융과 무역 (Finance & Trade)](finance/) | 12 |
| [음식 (Food & Nutrition)](food/) | 1 |
| [지리 (Geography)](geography/) | 107 |
| [건강 (Health)](health/) | 1 |
| [언어 (Language)](language/) | 2 |
| [레퍼런스 (Reference)](reference/) | 98 |
| [스포츠 (Sports)](sports/) | 3 |
| [기술 (Technology)](tech/) | 13 |
| [시간과 달력 (Time & Calendar)](time/) | 6 |
| [관광 (Tourism)](tourism/) | 25 |
| [교통 (Transport)](transport/) | 61 |
| [단위와 측정 (Units & Measurements)](units/) | 14 |

## Usage

### Browse on the web
Visit [listbase.org/ko/](https://listbase.org/ko/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.ko.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.ko.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.ko.listbase.org/geography/th-central-provinces_KO.xlsx
curl -O https://cdn.ko.listbase.org/geography/th-central-provinces_KO.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.ko.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.ko.listbase.org/geography/th-central-provinces.json');
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
│   ├── {dataset}_KO.csv   # CSV download
│   └── {dataset}_KO.xlsx  # Excel download
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
