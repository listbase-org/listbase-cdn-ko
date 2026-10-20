# 단위와 측정 (Units & Measurements)

14 datasets — 422 records

> Browse at [listbase.org/ko/units/](https://listbase.org/ko/units/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [측정 단위 한국어 명칭 (CLDR)](ko-cheukjeong-danwi.json) | 232 | 50 KB | [CSV](ko-cheukjeong-danwi_KO.csv) | [Excel](ko-cheukjeong-danwi_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi/) |
| [부피 단위 (44)](ko-cheukjeong-danwi-volume.json) | 44 | 11 KB | [CSV](ko-cheukjeong-danwi-volume_KO.csv) | [Excel](ko-cheukjeong-danwi-volume_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-volume/) |
| [길이 단위 (31)](ko-cheukjeong-danwi-length.json) | 31 | 8 KB | [CSV](ko-cheukjeong-danwi-length_KO.csv) | [Excel](ko-cheukjeong-danwi-length_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-length/) |
| [질량 단위 (17)](ko-cheukjeong-danwi-mass.json) | 17 | 5 KB | [CSV](ko-cheukjeong-danwi-mass_KO.csv) | [Excel](ko-cheukjeong-danwi-mass_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-mass/) |
| [시간 단위 (15)](ko-cheukjeong-danwi-duration.json) | 15 | 4 KB | [CSV](ko-cheukjeong-danwi-duration_KO.csv) | [Excel](ko-cheukjeong-danwi-duration_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-duration/) |
| [넓이 단위 (13)](ko-cheukjeong-danwi-area.json) | 13 | 4 KB | [CSV](ko-cheukjeong-danwi-area_KO.csv) | [Excel](ko-cheukjeong-danwi-area_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-area/) |
| [농도 단위 (13)](ko-cheukjeong-danwi-concentr.json) | 13 | 4 KB | [CSV](ko-cheukjeong-danwi-concentr_KO.csv) | [Excel](ko-cheukjeong-danwi-concentr_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-concentr/) |
| [압력 단위 (12)](ko-cheukjeong-danwi-pressure.json) | 12 | 4 KB | [CSV](ko-cheukjeong-danwi-pressure_KO.csv) | [Excel](ko-cheukjeong-danwi-pressure_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-pressure/) |
| [데이터 단위 (11)](ko-cheukjeong-danwi-digital.json) | 11 | 4 KB | [CSV](ko-cheukjeong-danwi-digital_KO.csv) | [Excel](ko-cheukjeong-danwi-digital_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-digital/) |
| [전기 단위 (8)](ko-cheukjeong-danwi-electric.json) | 8 | 3 KB | [CSV](ko-cheukjeong-danwi-electric_KO.csv) | [Excel](ko-cheukjeong-danwi-electric_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-electric/) |
| [그래픽 단위 (8)](ko-cheukjeong-danwi-graphics.json) | 8 | 3 KB | [CSV](ko-cheukjeong-danwi-graphics_KO.csv) | [Excel](ko-cheukjeong-danwi-graphics_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-graphics/) |
| [각도 단위 (6)](ko-cheukjeong-danwi-angle.json) | 6 | 3 KB | [CSV](ko-cheukjeong-danwi-angle_KO.csv) | [Excel](ko-cheukjeong-danwi-angle_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-angle/) |
| [일률 단위 (6)](ko-cheukjeong-danwi-power.json) | 6 | 3 KB | [CSV](ko-cheukjeong-danwi-power_KO.csv) | [Excel](ko-cheukjeong-danwi-power_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-power/) |
| [속도 단위 (6)](ko-cheukjeong-danwi-speed.json) | 6 | 3 KB | [CSV](ko-cheukjeong-danwi-speed_KO.csv) | [Excel](ko-cheukjeong-danwi-speed_KO.xlsx) | [View](https://listbase.org/ko/units/ko-cheukjeong-danwi-speed/) |

## Quick Start

```bash
# List all units & measurements datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="units") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/units/ko-cheukjeong-danwi.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/units/)
