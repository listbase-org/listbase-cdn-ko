# 엔터테인먼트 (Entertainment)

17 datasets — 1,882 records

> Browse at [listbase.org/ko/entertainment/](https://listbase.org/ko/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [케이팝 아이돌 (K-pop idols)](ko-kpop-aidol.json) | 835 | 522 KB | [CSV](ko-kpop-aidol_KO.csv) | [Excel](ko-kpop-aidol_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-kpop-aidol/) |
| [대한민국 텔레비전 채널 피드 (송출 정보)](ko-tv-chaeneol-pideu.json) | 317 | 86 KB | [CSV](ko-tv-chaeneol-pideu_KO.csv) | [Excel](ko-tv-chaeneol-pideu_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-pideu/) |
| [대한민국 텔레비전 채널 (Korean television channels)](ko-tv-chaeneol.json) | 311 | 119 KB | [CSV](ko-tv-chaeneol_KO.csv) | [Excel](ko-tv-chaeneol_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol/) |
| [케이팝 그룹 (K-pop groups)](ko-kpop-geurup.json) | 182 | 104 KB | [CSV](ko-kpop-geurup_KO.csv) | [Excel](ko-kpop-geurup_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-kpop-geurup/) |
| [대한민국 종합 채널](ko-tv-chaeneol-general.json) | 71 | 30 KB | [CSV](ko-tv-chaeneol-general_KO.csv) | [Excel](ko-tv-chaeneol-general_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-general/) |
| [대한민국 예능·오락 채널](ko-tv-chaeneol-entertainment.json) | 29 | 13 KB | [CSV](ko-tv-chaeneol-entertainment_KO.csv) | [Excel](ko-tv-chaeneol-entertainment_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-entertainment/) |
| [대한민국 영화 채널](ko-tv-chaeneol-movies.json) | 19 | 9 KB | [CSV](ko-tv-chaeneol-movies_KO.csv) | [Excel](ko-tv-chaeneol-movies_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-movies/) |
| [대한민국 홈쇼핑 채널](ko-tv-chaeneol-shop.json) | 18 | 9 KB | [CSV](ko-tv-chaeneol-shop_KO.csv) | [Excel](ko-tv-chaeneol-shop_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-shop/) |
| [대한민국 교육 채널](ko-tv-chaeneol-education.json) | 17 | 9 KB | [CSV](ko-tv-chaeneol-education_KO.csv) | [Excel](ko-tv-chaeneol-education_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-education/) |
| [대한민국 뉴스 채널](ko-tv-chaeneol-news.json) | 13 | 7 KB | [CSV](ko-tv-chaeneol-news_KO.csv) | [Excel](ko-tv-chaeneol-news_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-news/) |
| [대한민국 드라마 채널](ko-tv-chaeneol-series.json) | 13 | 7 KB | [CSV](ko-tv-chaeneol-series_KO.csv) | [Excel](ko-tv-chaeneol-series_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-series/) |
| [대한민국 어린이 채널](ko-tv-chaeneol-kids.json) | 12 | 7 KB | [CSV](ko-tv-chaeneol-kids_KO.csv) | [Excel](ko-tv-chaeneol-kids_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-kids/) |
| [대한민국 종교 채널](ko-tv-chaeneol-religious.json) | 12 | 7 KB | [CSV](ko-tv-chaeneol-religious_KO.csv) | [Excel](ko-tv-chaeneol-religious_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-religious/) |
| [대한민국 경제·비즈니스 채널](ko-tv-chaeneol-business.json) | 9 | 6 KB | [CSV](ko-tv-chaeneol-business_KO.csv) | [Excel](ko-tv-chaeneol-business_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-business/) |
| [대한민국 라이프스타일 채널](ko-tv-chaeneol-lifestyle.json) | 9 | 6 KB | [CSV](ko-tv-chaeneol-lifestyle_KO.csv) | [Excel](ko-tv-chaeneol-lifestyle_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-lifestyle/) |
| [대한민국 음악 채널](ko-tv-chaeneol-music.json) | 8 | 5 KB | [CSV](ko-tv-chaeneol-music_KO.csv) | [Excel](ko-tv-chaeneol-music_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-music/) |
| [대한민국 애니메이션 채널](ko-tv-chaeneol-animation.json) | 7 | 5 KB | [CSV](ko-tv-chaeneol-animation_KO.csv) | [Excel](ko-tv-chaeneol-animation_KO.xlsx) | [View](https://listbase.org/ko/entertainment/ko-tv-chaeneol-animation/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.ko.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.ko.listbase.org/entertainment/ko-kpop-aidol.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ko/entertainment/)
