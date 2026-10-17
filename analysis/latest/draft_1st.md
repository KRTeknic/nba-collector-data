[SNAPSHOT_SOURCE]
- verified_at (ET/KST): 2026-10-17T12:17:02.184601-04:00 / 2026-10-18T01:17:02.184601+09:00
- source_urls: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json , https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json
- manifest.status: {"ESPN_SCOREBOARD": "OK", "ESPN_ODDS": "OK", "NBA_SCHEDULE_LEAGUEV2": "FAILED: 403 Client Error: Forbidden for url: https://cdn.nba.com/static/json/staticData/scheduleLeagueV2.json", "NBA_REF_ASSIGNMENTS": "OK", "LINEUPS_AUX": "OK", "CBS_INJURIES_AUX": "OK"}

[MARKET_SNAPSHOT_LOG]
- POR@GS | spread(details): POR -1.5 | total: 225.5 | provider: DraftKings | start_utc: 2026-10-17T02:00Z
- UTAH@PHX | spread(details): PHX -4.5 | total: 225.5 | provider: DraftKings | start_utc: 2026-10-17T02:00Z
- DEN@LAL | spread(details): LAL -3.5 | total: 229.5 | provider: DraftKings | start_utc: 2026-10-17T02:30Z

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
