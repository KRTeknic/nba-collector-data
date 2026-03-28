[SNAPSHOT_SOURCE]
- verified_at (ET/KST): 2026-03-28T09:53:50.837890-04:00 / 2026-03-28T22:53:50.837890+09:00
- source_urls: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json , https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json
- manifest.status: {"ESPN_SCOREBOARD": "OK", "ESPN_ODDS": "OK", "NBA_SCHEDULE_LEAGUEV2": "OK", "NBA_REF_ASSIGNMENTS": "OK", "LINEUPS_AUX": "OK", "CBS_INJURIES_AUX": "OK"}

[MARKET_SNAPSHOT_LOG]
- HOU@MEM | spread(details): HOU -13.5 | total: 229.5 | provider: Draft Kings | start_utc: 2026-03-28T00:00Z
- CHI@OKC | spread(details): OKC -19.5 | total: 241.5 | provider: Draft Kings | start_utc: 2026-03-28T00:00Z
- NO@TOR | spread(details): TOR -8.5 | total: 229.5 | provider: Draft Kings | start_utc: 2026-03-28T00:30Z
- UTAH@DEN | spread(details): DEN -19.5 | total: 246.5 | provider: Draft Kings | start_utc: 2026-03-28T01:00Z
- WSH@GS | spread(details): GS -12.5 | total: 230.5 | provider: Draft Kings | start_utc: 2026-03-28T02:00Z
- DAL@POR | spread(details): POR -10.5 | total: 240.5 | provider: Draft Kings | start_utc: 2026-03-28T02:00Z
- BKN@LAL | spread(details): LAL -18.5 | total: 224.5 | provider: Draft Kings | start_utc: 2026-03-28T02:30Z

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
