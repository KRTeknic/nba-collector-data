[SNAPSHOT_SOURCE]
- verified_at (ET/KST): 2025-12-22T08:53:38.617481-05:00 / 2025-12-22T22:53:38.617481+09:00
- source_urls: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json , https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json
- manifest.status: {"NBA_SCHEDULE_LEAGUEV2": "OK", "ESPN_SCOREBOARD": "OK", "ESPN_ODDS": "UNAVAILABLE: No odds found in ESPN scoreboard payload.", "NBA_CDN_SCOREBOARD": "OK", "NBA_CDN_ODDS": "OK", "NBA_INJURY_PDF": "OK: https://ak-static.cms.nba.com/referee/injury/Injury-Report_2025-12-22_07AM.pdf", "NBA_REF_ASSIGNMENTS": "OK", "FATIGUE_PACK": "OK", "FINAL_SCORES": "OK", "LINEUPS_AUX": "OK", "CBS_INJURIES_AUX": "OK", "ESPN_TEAM_INJURIES_AUX": "OK"}

[MARKET_SNAPSHOT_LOG]
- MARKET=UNAVAILABLE (FAIL-FAST)

[INJURY_SNAPSHOT_LOG]
- nba_injury_report.pdf: OK: https://ak-static.cms.nba.com/referee/injury/Injury-Report_2025-12-22_07AM.pdf
- AUX(가능): RotoWire lineups / CBS injuries / ESPN injury page (충돌 시 UNRESOLVED)

[UNRESOLVED_ZONE]
- MARKET=UNAVAILABLE (FAIL-FAST: ESPN_ODDS not OK)

[DRAFT_ANALYSIS_1ST]
- 픽조합 v1.0 준수(같은 경기 핸디+언오버 한 조합 중복 금지, 최소 2폴)
- 후보 없음 (MARKET UNAVAILABLE 또는 엔진 미연결)

[PROCESS_LOG]
- opened: manifest, odds (scoreboard/pdf optional)
- errors: none
