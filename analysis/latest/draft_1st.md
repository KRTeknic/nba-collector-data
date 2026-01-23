[SNAPSHOT_SOURCE]
{
  "verified_at": {
    "verified_at_utc": "2026-01-23T13:47:08.427366+00:00",
    "verified_at_et": "2026-01-23T08:47:08.427366-05:00",
    "verified_at_kst": "2026-01-23T22:47:08.427366+09:00"
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
      "match": "CHA@ORL",
      "details": "ORL -3.5",
      "total": 225.5,
      "provider": "Draft Kings",
      "start_utc": "2026-01-23T00:00Z",
      "event_id": "401810482"
    },
    {
      "match": "HOU@PHI",
      "details": "HOU -2.5",
      "total": 221.5,
      "provider": "Draft Kings",
      "start_utc": "2026-01-23T00:00Z",
      "event_id": "401810483"
    },
    {
      "match": "DEN@WSH",
      "details": "DEN -5.5",
      "total": 227.5,
      "provider": "Draft Kings",
      "start_utc": "2026-01-23T00:00Z",
      "event_id": "401810484"
    },
    {
      "match": "GS@DAL",
      "details": "GS -6.5",
      "total": 234.5,
      "provider": "Draft Kings",
      "start_utc": "2026-01-23T00:30Z",
      "event_id": "401810485"
    },
    {
      "match": "CHI@MIN",
      "details": "MIN -9.5",
      "total": 238.5,
      "provider": "Draft Kings",
      "start_utc": "2026-01-23T01:00Z",
      "event_id": "401810486"
    },
    {
      "match": "SA@UTAH",
      "details": "SA -13.5",
      "total": 236.5,
      "provider": "Draft Kings",
      "start_utc": "2026-01-23T02:00Z",
      "event_id": "401810487"
    },
    {
      "match": "LAL@LAC",
      "details": "LAL -1.5",
      "total": 222.5,
      "provider": "Draft Kings",
      "start_utc": "2026-01-23T03:00Z",
      "event_id": "401810488"
    },
    {
      "match": "MIA@POR",
      "details": "POR -2.5",
      "total": 235.5,
      "provider": "Draft Kings",
      "start_utc": "2026-01-23T03:00Z",
      "event_id": "401810489"
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
      "match": "CHA@ORL",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "HOU@PHI",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "DEN@WSH",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "GS@DAL",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "CHI@MIN",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "SA@UTAH",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "LAL@LAC",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "MIA@POR",
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