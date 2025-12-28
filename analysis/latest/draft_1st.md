[SNAPSHOT_SOURCE]
- verified_at (ET/KST): 2025-12-28T08:47:19.230723-05:00 / 2025-12-28T22:47:19.230723+09:00
- source_urls: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json , https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json
- manifest.status: {"NBA_SCHEDULE_LEAGUEV2": "OK", "ESPN_SCOREBOARD": "OK", "ESPN_ODDS": "OK", "NBA_CDN_SCOREBOARD": "OK", "NBA_CDN_ODDS": "OK", "NBA_INJURY_PDF": "FAILED: Not found (official-parse=no_pdf_links_for_date; brute-force=all_failed)", "NBA_REF_ASSIGNMENTS": "OK", "FATIGUE_PACK": "OK", "FINAL_SCORES": "OK", "LINEUPS_AUX": "OK", "CBS_INJURIES_AUX": "OK", "ESPN_TEAM_INJURIES_AUX": "OK"}

[MARKET_SNAPSHOT_LOG]
- DAL@SAC | spread(details): DAL -3.5 | total: 233.5 | provider: Draft Kings | start_utc: 2025-12-27T22:00Z
- DEN@ORL | spread(details): DEN -4.5 | total: 234.5 | provider: Draft Kings | start_utc: 2025-12-28T00:00Z
- PHX@NOP | spread(details): PHX -4.5 | total: 237.5 | provider: Draft Kings | start_utc: 2025-12-28T00:00Z
- NYK@ATL | spread(details): NY -6.5 | total: 242.5 | provider: Draft Kings | start_utc: 2025-12-28T01:00Z
- IND@MIA | spread(details): MIA -7.5 | total: 228.5 | provider: Draft Kings | start_utc: 2025-12-28T01:00Z
- MIL@CHI | spread(details): CHI -2.5 | total: 232.5 | provider: Draft Kings | start_utc: 2025-12-28T01:00Z
- CLE@HOU | spread(details): HOU -3.5 | total: 234.5 | provider: Draft Kings | start_utc: 2025-12-28T01:00Z
- BKN@MIN | spread(details): MIN -12.5 | total: 224.5 | provider: Draft Kings | start_utc: 2025-12-28T01:00Z
- UTA@SAS | spread(details): SA -15.5 | total: 241.5 | provider: Draft Kings | start_utc: 2025-12-28T01:00Z

[INJURY_SNAPSHOT_LOG]
- nba_injury_report.pdf: FAILED: Not found (official-parse=no_pdf_links_for_date; brute-force=all_failed)
- AUX(가능): RotoWire lineups / CBS injuries / ESPN injury page (충돌 시 UNRESOLVED)

[UNRESOLVED_ZONE]
- INJURY=FAILED (allow AUX check, conflicts -> UNRESOLVED)

[DRAFT_ANALYSIS_1ST]
- 픽조합 v1.0 준수(같은 경기 핸디+언오버 한 조합 중복 금지, 최소 2폴)
- PASS (engine not yet integrated): DRAFT pipeline OK; pick engine integration next

[PROCESS_LOG]
- opened: manifest, odds (scoreboard/pdf optional)
- errors: none
