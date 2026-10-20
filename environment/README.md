# 환경 (Environment)

4 datasets — 183 records

> Browse at [listbase.org/ko/environment/](https://listbase.org/ko/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [대한민국의 발전소](ko-baljeonso.json) | 132 | 54 KB | [CSV](ko-baljeonso_KO.csv) | [Excel](ko-baljeonso_KO.xlsx) | [View](https://listbase.org/ko/environment/ko-baljeonso/) |
| [한국의 원자력 발전소](ko-wonjaryeok-baljeonso.json) | 32 | 15 KB | [CSV](ko-wonjaryeok-baljeonso_KO.csv) | [Excel](ko-wonjaryeok-baljeonso_KO.xlsx) | [View](https://listbase.org/ko/environment/ko-wonjaryeok-baljeonso/) |
| [에너지 단위 (14)](ko-cheukjeong-danwi-energy.json) | 14 | 4 KB | [CSV](ko-cheukjeong-danwi-energy_KO.csv) | [Excel](ko-cheukjeong-danwi-energy_KO.xlsx) | [View](https://listbase.org/ko/environment/ko-cheukjeong-danwi-energy/) |
| [온도 단위 (5)](ko-cheukjeong-danwi-temperature.json) | 5 | 2 KB | [CSV](ko-cheukjeong-danwi-temperature_KO.csv) | [Excel](ko-cheukjeong-danwi-temperature_KO.xlsx) | [View](https://listbase.org/ko/environment/ko-cheukjeong-danwi-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/environment/ko-baljeonso.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/environment/)
