[SNAPSHOT_SOURCE]
{
  "verified_at": {
    "verified_at_utc": "2026-02-03T14:06:21.124214+00:00",
    "verified_at_et": "2026-02-03T09:06:21.124214-05:00",
    "verified_at_kst": "2026-02-03T23:06:21.124214+09:00"
  },
  "source_urls": {
    "manifest.json": "https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json",
    "espn_odds.json": "https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json"
  },
  "manifest_status_summary": {
    "ESPN_ODDS": "OK",
    "ESPN_SCOREBOARD": "OK",
    "NBA_INJURY_PDF": "",
    "NBA_REF_ASSIGNMENTS": "OK",
    "FATIGUE_PACK": ""
  }
}

[MARKET_SNAPSHOT_LOG]
{
  "rows": [
    {
      "match": "HOU@IND",
      "details": "HOU -6.5",
      "total": 218.5,
      "provider": "Draft Kings",
      "start_utc": "2026-02-03T00:00Z",
      "event_id": "401810568"
    },
    {
      "match": "MIN@MEM",
      "details": "MIN -7.5",
      "total": 231.5,
      "provider": "Draft Kings",
      "start_utc": "2026-02-03T00:30Z",
      "event_id": "401810569"
    },
    {
      "match": "PHI@LAC",
      "details": "PHI -1.5",
      "total": 218.5,
      "provider": "Draft Kings",
      "start_utc": "2026-02-03T03:00Z",
      "event_id": "401810570"
    }
  ],
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
    "tag": "U3",
    "reason": "INJURY PDF missing — INJURY=FAILED (보조확인 필요)"
  }
]

[DRAFT_ANALYSIS_1ST]
{
  "status": "OK",
  "candidates": [
    {
      "match": "HOU@IND",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "MIN@MEM",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "PHI@LAC",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    }
  ],
  "note": "FAIL-FAST: ESPN_ODDS OK가 아니면 종료(대체 마켓 금지)."
}

[PROCESS_LOG]
loaded: latest/manifest.json
loaded: latest/espn_odds.json
FAIL_FAST=NO
anchors_count=0
drift_rows=0