# 음식 (Food & Nutrition)

1 datasets — 232 records

> Browse at [listbase.org/ko/food/](https://listbase.org/ko/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [대한민국 미쉐린 가이드 레스토랑](ko-michelin-restaurant.json) | 232 | 249 KB | [CSV](ko-michelin-restaurant_KO.csv) | [Excel](ko-michelin-restaurant_KO.xlsx) | [View](https://listbase.org/ko/food/ko-michelin-restaurant/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/food/ko-michelin-restaurant.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/food/)
