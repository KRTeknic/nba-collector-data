[SNAPSHOT_SOURCE]
{
  "verified_at": {
    "verified_at_utc": "2026-07-09T16:00:46.363652+00:00",
    "verified_at_et": "2026-07-09T12:00:46.363652-04:00",
    "verified_at_kst": "2026-07-10T01:00:46.363652+09:00"
  },
  "source_urls": {
    "manifest.json": "https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json",
    "espn_odds.json": "https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json"
  },
  "manifest_status_summary": {
    "ESPN_ODDS": "UNAVAILABLE: No odds in payload",
    "ESPN_SCOREBOARD": "OK",
    "NBA_INJURY_PDF": "",
    "NBA_REF_ASSIGNMENTS": "OK",
    "FATIGUE_PACK": ""
  }
}

[MARKET_SNAPSHOT_LOG]
{
  "rows": [],
  "drift_vs_open_anchor": []
}

[INJURY_SNAPSHOT_LOG]
{
  "nba_injury_report_pdf_present": false,
  "nba_injury_report_pdf_path": null,
  "note": "보조 확인(RotoWire/CBS/ESPN)은 다음 단계에서 별도 수집기로 분리 권장"
}

[UNRESOLVED_ZONE]
[
  {
    "tag": "U0",
    "reason": "MARKET_UNAVAILABLE (FAIL-FAST) — manifest.status.ESPN_ODDS != OK"
  },
  {
    "tag": "U3",
    "reason": "INJURY PDF missing — INJURY=FAILED (보조확인 필요)"
  }
]

[DRAFT_ANALYSIS_1ST]
{
  "status": "BLOCKED",
  "candidates": [],
  "note": "FAIL-FAST: ESPN_ODDS OK가 아니면 종료(대체 마켓 금지)."
}

[PROCESS_LOG]
loaded: latest/manifest.json
loaded: latest/espn_odds.json
FAIL_FAST=YES
anchors_count=0
drift_rows=0