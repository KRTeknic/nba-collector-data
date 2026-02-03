[SNAPSHOT_SOURCE]
- verified_at (ET/KST): 2026-02-03T09:07:19.552172-05:00 / 2026-02-03T23:07:19.552172+09:00
- source_urls: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json , https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json
- manifest.status: {"ESPN_SCOREBOARD": "OK", "ESPN_ODDS": "OK", "NBA_SCHEDULE_LEAGUEV2": "OK", "NBA_REF_ASSIGNMENTS": "OK", "LINEUPS_AUX": "OK", "CBS_INJURIES_AUX": "OK"}

[MARKET_SNAPSHOT_LOG]
- HOU@IND | spread(details): HOU -6.5 | total: 218.5 | provider: Draft Kings | start_utc: 2026-02-03T00:00Z
- MIN@MEM | spread(details): MIN -7.5 | total: 231.5 | provider: Draft Kings | start_utc: 2026-02-03T00:30Z
- PHI@LAC | spread(details): PHI -1.5 | total: 218.5 | provider: Draft Kings | start_utc: 2026-02-03T03:00Z

[INJURY_SNAPSHOT_LOG]
- nba_injury_report.pdf: UNAVAILABLE (manifest missing)
- AUX(가능): RotoWire lineups / CBS injuries / ESPN injury page (충돌 시 UNRESOLVED)

[UNRESOLVED_ZONE]
- INJURY=FAILED (allow AUX check, conflicts -> UNRESOLVED)

[DRAFT_ANALYSIS_1ST]
- 픽조합 v1.0 준수(같은 경기 핸디+언오버 한 조합 중복 금지, 최소 2폴)
- PASS (engine not yet integrated): DRAFT pipeline OK; pick engine integration next

[PROCESS_LOG]
- opened: manifest, odds (scoreboard/pdf optional)
- errors: none
