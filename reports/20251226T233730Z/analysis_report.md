# RESUME.AUTO ANALYSIS REPORT v1

## SNAPSHOT_SOURCE
- run_kind: **DELTA_0805** (source: manifest.run_kind)
- as_of_kst: 2025-12-27T08:37:36.305951+09:00
- as_of_et:  2025-12-26T18:37:36.305951-05:00
- as_of_utc: 2025-12-26T23:37:36.305951+00:00
- snapshot_ts(manifest): 20251226T233730Z
- baseline_ts: 20251226T135111Z
- baseline_urls.manifest: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/history/20251226T135111Z/manifest.json
- baseline_urls.odds: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/history/20251226T135111Z/espn_odds.json
- slate_date_kst: 2025-12-27 (manifest)
- slate_date_et:  2025-12-26 (manifest)

## MARKET_DELTA_LOG
- ESPN_ODDS: OK
- ESPN_SCOREBOARD: OK
- provider(sample): Draft Kings

_No parsed anchor rows._

## INJURY_DELTA_LOG
- NBA_INJURY_PDF: FAILED: Not found (official-parse=no_pdf_links_for_date; brute-force=all_failed)
- injury_aux: OK -> {'cbs_status': 'OK', 'cbs_rows': 3, 'espn_status': 'OK', 'espn_rows': 18}
- lineups_aux: OK -> {'status': 'OK', 'games': 11, 'note': 'best-effort parser. raw HTML saved as rotowire_lineups_raw.html'}

## UNRESOLVED_ZONE
- INJURY_PDF_FAILED

## UPDATED_DRAFT_2ND
- This report intentionally outputs **drift & integrity gates** only.
- Picks/portfolio generation should be done in your 분석 모듈(화이트페이퍼 엔진) 단계 to avoid ungrounded recommendations.
- Next action: use the drift table + unresolved flags as inputs for the main model.

## PROCESS_LOG
- anchor_lines_received: 0
- anchor_lines_parsed_ok: 0
- anchor_lines_parsed_fail: 0
- latest_odds_rows: 9
- baseline_available_local: YES
