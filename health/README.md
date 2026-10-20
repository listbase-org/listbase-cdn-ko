# 건강 (Health)

1 datasets — 151 records

> Browse at [listbase.org/ko/health/](https://listbase.org/ko/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [대한민국의 병원 (Hospitals of South Korea)](ko-byeongwon.json) | 151 | 51 KB | [CSV](ko-byeongwon_KO.csv) | [Excel](ko-byeongwon_KO.xlsx) | [View](https://listbase.org/ko/health/ko-byeongwon/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/health/ko-byeongwon.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/health/)
