[SNAPSHOT_SOURCE]
{
  "verified_at": {
    "verified_at_utc": "2025-12-26T23:36:09.356359+00:00",
    "verified_at_et": "2025-12-26T18:36:09.356359-05:00",
    "verified_at_kst": "2025-12-27T08:36:09.356359+09:00"
  },
  "source_urls": {
    "manifest.json": "https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json",
    "espn_odds.json": "https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json"
  },
  "manifest_status_summary": {
    "ESPN_ODDS": "OK",
    "ESPN_SCOREBOARD": "OK",
    "NBA_INJURY_PDF": "FAILED: Not found (official-parse=no_pdf_links_for_date; brute-force=all_failed)",
    "NBA_REF_ASSIGNMENTS": "OK",
    "FATIGUE_PACK": "OK"
  }
}

[MARKET_SNAPSHOT_LOG]
{
  "rows": [
    {
      "match": "MIA@ATL",
      "details": "ATL -2.5",
      "total": 248.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-27T00:00Z",
      "event_id": "401810278"
    },
    {
      "match": "CHA@ORL",
      "details": "ORL -5.5",
      "total": 232.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-27T00:00Z",
      "event_id": "401810279"
    },
    {
      "match": "TOR@WSH",
      "details": "TOR -7.5",
      "total": 228.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-27T00:00Z",
      "event_id": "401810280"
    },
    {
      "match": "BOS@IND",
      "details": "BOS -8.5",
      "total": 222.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-27T00:00Z",
      "event_id": "401810281"
    },
    {
      "match": "PHI@CHI",
      "details": "PHI -1.5",
      "total": 240.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-27T00:30Z",
      "event_id": "401810282"
    },
    {
      "match": "MIL@MEM",
      "details": "MEM -5.5",
      "total": 228.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-27T01:00Z",
      "event_id": "401810283"
    },
    {
      "match": "PHX@NO",
      "details": "PHX -5.5",
      "total": 238.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-27T01:00Z",
      "event_id": "401810284"
    },
    {
      "match": "DET@UTAH",
      "details": "DET -9.5",
      "total": 243.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-27T02:30Z",
      "event_id": "401810285"
    },
    {
      "match": "LAC@POR",
      "details": "LAC -1.5",
      "total": 227.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-27T03:00Z",
      "event_id": "401810286"
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
      "match": "MIA@ATL",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "CHA@ORL",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "TOR@WSH",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "BOS@IND",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "PHI@CHI",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "MIL@MEM",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "PHX@NO",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "DET@UTAH",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "LAC@POR",
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