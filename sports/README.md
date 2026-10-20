# 스포츠 (Sports)

3 datasets — 123 records

> Browse at [listbase.org/ko/sports/](https://listbase.org/ko/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [대한민국의 경기장 (Stadiums of South Korea)](ko-gyeonggijang.json) | 80 | 27 KB | [CSV](ko-gyeonggijang_KO.csv) | [Excel](ko-gyeonggijang_KO.xlsx) | [View](https://listbase.org/ko/sports/ko-gyeonggijang/) |
| [대한민국 스포츠 채널](ko-tv-chaeneol-sports.json) | 27 | 12 KB | [CSV](ko-tv-chaeneol-sports_KO.csv) | [Excel](ko-tv-chaeneol-sports_KO.xlsx) | [View](https://listbase.org/ko/sports/ko-tv-chaeneol-sports/) |
| [대한민국의 축구 클럽 (South Korean football clubs)](ko-chukgu-keulleop.json) | 16 | 6 KB | [CSV](ko-chukgu-keulleop_KO.csv) | [Excel](ko-chukgu-keulleop_KO.xlsx) | [View](https://listbase.org/ko/sports/ko-chukgu-keulleop/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/sports/ko-gyeonggijang.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/sports/)
