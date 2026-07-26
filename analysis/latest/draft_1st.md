[SNAPSHOT_SOURCE]
- verified_at (ET/KST): 2026-07-26T10:41:36.550261-04:00 / 2026-07-26T23:41:36.550261+09:00
- source_urls: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json , https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json
- manifest.status: {"ESPN_SCOREBOARD": "OK", "ESPN_ODDS": "UNAVAILABLE: No odds in payload", "NBA_SCHEDULE_LEAGUEV2": "FAILED: 403 Client Error: Forbidden for url: https://cdn.nba.com/static/json/staticData/scheduleLeagueV2.json", "NBA_REF_ASSIGNMENTS": "OK", "LINEUPS_AUX": "OK", "CBS_INJURIES_AUX": "OK"}

[MARKET_SNAPSHOT_LOG]
- MARKET=UNAVAILABLE (FAIL-FAST)

[INJURY_SNAPSHOT_LOG]
- nba_injury_report.pdf: UNAVAILABLE (manifest missing)
- AUX(가능): RotoWire lineups / CBS injuries / ESPN injury page (충돌 시 UNRESOLVED)

[UNRESOLVED_ZONE]
- MARKET=UNAVAILABLE (FAIL-FAST: ESPN_ODDS not OK)
- INJURY=FAILED (allow AUX check, conflicts -> UNRESOLVED)

[DRAFT_ANALYSIS_1ST]
- 픽조합 v1.0 준수(같은 경기 핸디+언오버 한 조합 중복 금지, 최소 2폴)
- 후보 없음 (MARKET UNAVAILABLE 또는 엔진 미연결)

[PROCESS_LOG]
- opened: manifest, odds (scoreboard/pdf optional)
- errors: none
