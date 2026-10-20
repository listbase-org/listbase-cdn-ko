# 문화와 종교 (Culture & Religion)

13 datasets — 1,983 records

> Browse at [listbase.org/ko/culture/](https://listbase.org/ko/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [대한민국의 박물관 (Museums in South Korea)](ko-bakmulgwan.json) | 738 | 193 KB | [CSV](ko-bakmulgwan_KO.csv) | [Excel](ko-bakmulgwan_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-bakmulgwan/) |
| [한국의 성곽·요새 (Korean Fortifications & Fortresses)](ko-seonggwak.json) | 458 | 141 KB | [CSV](ko-seonggwak_KO.csv) | [Excel](ko-seonggwak_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-seonggwak/) |
| [한국의 능·고분 (Korean Royal Tombs & Ancient Tombs)](ko-wangneung-gobun.json) | 180 | 57 KB | [CSV](ko-wangneung-gobun_KO.csv) | [Excel](ko-wangneung-gobun_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-wangneung-gobun/) |
| [한국의 서원 (Korean Seowon — Confucian Academies)](ko-seowon.json) | 179 | 52 KB | [CSV](ko-seowon_KO.csv) | [Excel](ko-seowon_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-seowon/) |
| [한국의 향교 (Korean Hyanggyo — Local Confucian Schools)](ko-hyanggyo.json) | 153 | 47 KB | [CSV](ko-hyanggyo_KO.csv) | [Excel](ko-hyanggyo_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-hyanggyo/) |
| [한국의 불교 사찰 (Korean Buddhist Temples)](ko-bulgyo-sachal.json) | 113 | 34 KB | [CSV](ko-bulgyo-sachal_KO.csv) | [Excel](ko-bulgyo-sachal_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-bulgyo-sachal/) |
| [대한민국의 도서관 (Libraries of South Korea)](ko-doseogwan.json) | 52 | 18 KB | [CSV](ko-doseogwan_KO.csv) | [Excel](ko-doseogwan_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-doseogwan/) |
| [대한민국의 동상 (Statues of South Korea)](ko-dongsang.json) | 25 | 10 KB | [CSV](ko-dongsang_KO.csv) | [Excel](ko-dongsang_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-dongsang/) |
| [대한민국의 교회 (Churches of South Korea)](ko-gyohoe.json) | 24 | 10 KB | [CSV](ko-gyohoe_KO.csv) | [Excel](ko-gyohoe_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-gyohoe/) |
| [대한민국의 기념물 (Monuments and Memorials of South Korea)](ko-ginyeommul.json) | 23 | 10 KB | [CSV](ko-ginyeommul_KO.csv) | [Excel](ko-ginyeommul_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-ginyeommul/) |
| [한국의 궁궐 (Korean Royal Palaces)](ko-gunggwol.json) | 18 | 7 KB | [CSV](ko-gunggwol_KO.csv) | [Excel](ko-gunggwol_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-gunggwol/) |
| [대한민국의 유네스코 세계유산](ko-segye-yusan.json) | 14 | 17 KB | [CSV](ko-segye-yusan_KO.csv) | [Excel](ko-segye-yusan_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-segye-yusan/) |
| [대한민국의 극장 (Theatres of South Korea)](ko-geukjang.json) | 6 | 4 KB | [CSV](ko-geukjang_KO.csv) | [Excel](ko-geukjang_KO.xlsx) | [View](https://listbase.org/ko/culture/ko-geukjang/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/culture/ko-bakmulgwan.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/culture/)
