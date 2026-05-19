# MariaMealMenu

신설마리아병원 구내식당 주간 식단 데이터 (PUBLIC).

- `latest_meal.json` — `{"YYYY-MM-DD": ["메뉴1", ...]}` 형태
- 갱신 주기: 매주 일요일 23:00 KST (GitHub Actions에서 자동 commit)
- 데이터 출처: 신설마리아 그룹웨어(mgw.mariababy.com)
- 소비처: today-meal.dyshin.workers.dev (Cloudflare Worker)

운영 코드·시크릿은 별도 PRIVATE repo `dyshin-maria/MariaMealCheck`에서 관리.
