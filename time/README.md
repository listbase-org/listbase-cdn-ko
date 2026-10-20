# 시간과 달력 (Time & Calendar)

6 datasets — 2,373 records

> Browse at [listbase.org/ko/time/](https://listbase.org/ko/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [대한민국 공휴일 — 전체 목록 (1948–2030)](ko-gongyuil-completos.json) | 1,445 | 634 KB | [CSV](ko-gongyuil-completos_KO.csv) | [Excel](ko-gongyuil-completos_KO.xlsx) | [View](https://listbase.org/ko/time/ko-gongyuil-completos/) |
| [대한민국 공휴일 (2000–2030)](kr-gongyuil.json) | 533 | 118 KB | [CSV](kr-gongyuil_KO.csv) | [Excel](kr-gongyuil_KO.xlsx) | [View](https://listbase.org/ko/time/kr-gongyuil/) |
| [일본 연호 한국어 표기 (CLDR)](ko-ilbon-yeonho.json) | 237 | 31 KB | [CSV](ko-ilbon-yeonho_KO.csv) | [Excel](ko-ilbon-yeonho_KO.xlsx) | [View](https://listbase.org/ko/time/ko-ilbon-yeonho/) |
| [역법별 달 이름 한국어 표기 (CLDR)](ko-yeokbeop-dal-ireum.json) | 74 | 13 KB | [CSV](ko-yeokbeop-dal-ireum_KO.csv) | [Excel](ko-yeokbeop-dal-ireum_KO.xlsx) | [View](https://listbase.org/ko/time/ko-yeokbeop-dal-ireum/) |
| [대한민국 공휴일 (KASI / data.go.kr — 2025–2027)](ko-gonghyuil-kasi.json) | 60 | 17 KB | [CSV](ko-gonghyuil-kasi_KO.csv) | [Excel](ko-gonghyuil-kasi_KO.xlsx) | [View](https://listbase.org/ko/time/ko-gonghyuil-kasi/) |
| [요일·분기·시간대·연호 한국어 용어 (CLDR)](ko-yoil-mit-sigan-yongeo.json) | 24 | 4 KB | [CSV](ko-yoil-mit-sigan-yongeo_KO.csv) | [Excel](ko-yoil-mit-sigan-yongeo_KO.xlsx) | [View](https://listbase.org/ko/time/ko-yoil-mit-sigan-yongeo/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/time/ko-gongyuil-completos.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/time/)
