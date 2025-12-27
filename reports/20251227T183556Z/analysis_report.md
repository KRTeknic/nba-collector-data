# RESUME.AUTO ANALYSIS REPORT v1

## SNAPSHOT_SOURCE
- run_kind: **SNAPSHOT_2205** (source: fallback_window(03:35))
- as_of_kst: 2025-12-28T03:35:59.794732+09:00
- as_of_et:  2025-12-27T13:35:59.794732-05:00
- as_of_utc: 2025-12-27T18:35:59.794732+00:00
- snapshot_ts(manifest): 20251227T183556Z
- baseline_ts: 20251226T135111Z
- baseline_urls.manifest: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/history/20251226T135111Z/manifest.json
- baseline_urls.odds: https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/history/20251226T135111Z/espn_odds.json
- slate_date_kst: None (manifest)
- slate_date_et:  None (manifest)

## MARKET_SNAPSHOT_LOG
- ESPN_ODDS: OK
- ESPN_SCOREBOARD: OK
- provider(sample): Draft Kings

_No parsed anchor rows._

## INJURY_SNAPSHOT_LOG
- NBA_INJURY_PDF: FAILED: Not found (official-parse=no_pdf_links_for_date; brute-force=all_failed)
- injury_aux: OK -> {'cbs_status': 'OK', 'cbs_rows': 3, 'espn_status': 'OK', 'espn_rows': 18}
- lineups_aux: OK -> {'status': 'OK', 'games': 0, 'note': 'fail-soft; tries __NEXT_DATA__ first, then HTML fallback.'}

## UNRESOLVED_ZONE
- INJURY_PDF_FAILED

## DRAFT_ANALYSIS_1ST
- This report intentionally outputs **drift & integrity gates** only.
- Picks/portfolio generation should be done in your 분석 모듈(화이트페이퍼 엔진) 단계 to avoid ungrounded recommendations.
- Next action: use the drift table + unresolved flags as inputs for the main model.

## PROCESS_LOG
- anchor_lines_received: 0
- anchor_lines_parsed_ok: 0
- anchor_lines_parsed_fail: 0
- latest_odds_rows: 9
- baseline_available_local: YES
