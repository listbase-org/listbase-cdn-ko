# 기술 (Technology)

13 datasets — 3,061 records

> Browse at [listbase.org/ko/tech/](https://listbase.org/ko/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [이모지 한국어 이름 (CLDR)](ko-imoji-ireum.json) | 1,966 | 334 KB | [CSV](ko-imoji-ireum_KO.csv) | [Excel](ko-imoji-ireum_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-imoji-ireum/) |
| [세계의 시간대 (IANA / CLDR 한국어)](ko-sigandae.json) | 420 | 76 KB | [CSV](ko-sigandae_KO.csv) | [Excel](ko-sigandae_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-sigandae/) |
| [세계의 문자 체계 (ISO 15924 / CLDR)](ko-munja-chegye.json) | 172 | 16 KB | [CSV](ko-munja-chegye_KO.csv) | [Excel](ko-munja-chegye_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-munja-chegye/) |
| [아메리카 시간대 (144)](ko-sigandae-america.json) | 144 | 28 KB | [CSV](ko-sigandae-america_KO.csv) | [Excel](ko-sigandae-america_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-sigandae-america/) |
| [문자 분류 라벨 한국어 명칭 (CLDR)](ko-munja-bunryu-lebel.json) | 86 | 9 KB | [CSV](ko-munja-bunryu-lebel_KO.csv) | [Excel](ko-munja-bunryu-lebel_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-munja-bunryu-lebel/) |
| [아시아 시간대 (82)](ko-sigandae-asia.json) | 82 | 15 KB | [CSV](ko-sigandae-asia_KO.csv) | [Excel](ko-sigandae-asia_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-sigandae-asia/) |
| [유럽 시간대 (58)](ko-sigandae-europe.json) | 58 | 12 KB | [CSV](ko-sigandae-europe_KO.csv) | [Excel](ko-sigandae-europe_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-sigandae-europe/) |
| [아프리카 시간대 (52)](ko-sigandae-africa.json) | 52 | 11 KB | [CSV](ko-sigandae-africa_KO.csv) | [Excel](ko-sigandae-africa_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-sigandae-africa/) |
| [태평양 시간대 (38)](ko-sigandae-pacific.json) | 38 | 8 KB | [CSV](ko-sigandae-pacific_KO.csv) | [Excel](ko-sigandae-pacific_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-sigandae-pacific/) |
| [남극 시간대 (11)](ko-sigandae-antarctica.json) | 11 | 3 KB | [CSV](ko-sigandae-antarctica_KO.csv) | [Excel](ko-sigandae-antarctica_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-sigandae-antarctica/) |
| [오스트레일리아 시간대 (11)](ko-sigandae-australia.json) | 11 | 3 KB | [CSV](ko-sigandae-australia_KO.csv) | [Excel](ko-sigandae-australia_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-sigandae-australia/) |
| [인도양 시간대 (11)](ko-sigandae-indian.json) | 11 | 3 KB | [CSV](ko-sigandae-indian_KO.csv) | [Excel](ko-sigandae-indian_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-sigandae-indian/) |
| [대서양 시간대 (10)](ko-sigandae-atlantic.json) | 10 | 3 KB | [CSV](ko-sigandae-atlantic_KO.csv) | [Excel](ko-sigandae-atlantic_KO.xlsx) | [View](https://listbase.org/ko/tech/ko-sigandae-atlantic/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/tech/ko-imoji-ireum.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/tech/)
