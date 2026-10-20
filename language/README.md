# 언어 (Language)

2 datasets — 614 records

> Browse at [listbase.org/ko/language/](https://listbase.org/ko/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [세계의 언어 (591)](ko-eoneo.json) | 591 | 57 KB | [CSV](ko-eoneo_KO.csv) | [Excel](ko-eoneo_KO.xlsx) | [View](https://listbase.org/ko/language/ko-eoneo/) |
| [언어 변이(variant) 한국어 명칭 (CLDR)](ko-eoneo-byeonche.json) | 23 | 3 KB | [CSV](ko-eoneo-byeonche_KO.csv) | [Excel](ko-eoneo-byeonche_KO.xlsx) | [View](https://listbase.org/ko/language/ko-eoneo-byeonche/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/language/ko-eoneo.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/language/)
