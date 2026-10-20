# 금융과 무역 (Finance & Trade)

12 datasets — 761 records

> Browse at [listbase.org/ko/finance/](https://listbase.org/ko/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Seoul 은행 — SWIFT/BIC 코드](ko-seoul-eunhaeng.json) | 252 | 40 KB | [CSV](ko-seoul-eunhaeng_KO.csv) | [Excel](ko-seoul-eunhaeng_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-seoul-eunhaeng/) |
| [세계의 국가들 (250)](ko-gukga.json) | 250 | 170 KB | [CSV](ko-gukga_KO.csv) | [Excel](ko-gukga_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-gukga/) |
| [아프리카 국가들 (60)](ko-apeurika-gukga.json) | 60 | 43 KB | [CSV](ko-apeurika-gukga_KO.csv) | [Excel](ko-apeurika-gukga_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-apeurika-gukga/) |
| [유럽 국가들 (53)](ko-yureop-gukga.json) | 53 | 38 KB | [CSV](ko-yureop-gukga_KO.csv) | [Excel](ko-yureop-gukga_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-yureop-gukga/) |
| [아시아 국가들 (50)](ko-asia-gukga.json) | 50 | 36 KB | [CSV](ko-asia-gukga_KO.csv) | [Excel](ko-asia-gukga_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-asia-gukga/) |
| [북아메리카 국가들 (42)](ko-bukmi-gukga.json) | 42 | 32 KB | [CSV](ko-bukmi-gukga_KO.csv) | [Excel](ko-bukmi-gukga_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-bukmi-gukga/) |
| [오세아니아 국가들 (27)](ko-oseania-gukga.json) | 27 | 21 KB | [CSV](ko-oseania-gukga_KO.csv) | [Excel](ko-oseania-gukga_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-oseania-gukga/) |
| [남아메리카 국가들 (15)](ko-nammi-gukga.json) | 15 | 13 KB | [CSV](ko-nammi-gukga_KO.csv) | [Excel](ko-nammi-gukga_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-nammi-gukga/) |
| [Busan 은행 — SWIFT/BIC 코드](ko-busan-eunhaeng.json) | 3 | 2 KB | [CSV](ko-busan-eunhaeng_KO.csv) | [Excel](ko-busan-eunhaeng_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-busan-eunhaeng/) |
| [Daegu 은행 — SWIFT/BIC 코드](ko-daegu-eunhaeng.json) | 3 | 2 KB | [CSV](ko-daegu-eunhaeng_KO.csv) | [Excel](ko-daegu-eunhaeng_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-daegu-eunhaeng/) |
| [남극 국가들 (3)](ko-namgeuk-gukga.json) | 3 | 5 KB | [CSV](ko-namgeuk-gukga_KO.csv) | [Excel](ko-namgeuk-gukga_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-namgeuk-gukga/) |
| [Pusan 은행 — SWIFT/BIC 코드](ko-pusan-eunhaeng.json) | 3 | 2 KB | [CSV](ko-pusan-eunhaeng_KO.csv) | [Excel](ko-pusan-eunhaeng_KO.xlsx) | [View](https://listbase.org/ko/finance/ko-pusan-eunhaeng/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/finance/ko-seoul-eunhaeng.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/finance/)
