[SNAPSHOT_SOURCE]
- verified_at (ET/KST): 2026-01-23T08:48:40.578239-05:00 / 2026-01-23T22:48:40.578239+09:00
- source_urls: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json , https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json
- manifest.status: {"ESPN_SCOREBOARD": "OK", "ESPN_ODDS": "OK", "NBA_SCHEDULE_LEAGUEV2": "OK", "NBA_REF_ASSIGNMENTS": "OK", "LINEUPS_AUX": "OK", "CBS_INJURIES_AUX": "OK"}

[MARKET_SNAPSHOT_LOG]
- CHA@ORL | spread(details): ORL -3.5 | total: 225.5 | provider: Draft Kings | start_utc: 2026-01-23T00:00Z
- HOU@PHI | spread(details): HOU -2.5 | total: 221.5 | provider: Draft Kings | start_utc: 2026-01-23T00:00Z
- DEN@WSH | spread(details): DEN -5.5 | total: 227.5 | provider: Draft Kings | start_utc: 2026-01-23T00:00Z
- GS@DAL | spread(details): GS -6.5 | total: 234.5 | provider: Draft Kings | start_utc: 2026-01-23T00:30Z
- CHI@MIN | spread(details): MIN -9.5 | total: 238.5 | provider: Draft Kings | start_utc: 2026-01-23T01:00Z
- SA@UTAH | spread(details): SA -13.5 | total: 236.5 | provider: Draft Kings | start_utc: 2026-01-23T02:00Z
- LAL@LAC | spread(details): LAL -1.5 | total: 222.5 | provider: Draft Kings | start_utc: 2026-01-23T03:00Z
- MIA@POR | spread(details): POR -2.5 | total: 235.5 | provider: Draft Kings | start_utc: 2026-01-23T03:00Z

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
