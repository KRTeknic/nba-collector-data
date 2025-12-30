[SNAPSHOT_SOURCE]
{
  "verified_at": {
    "verified_at_utc": "2025-12-30T14:00:24.132456+00:00",
    "verified_at_et": "2025-12-30T09:00:24.132456-05:00",
    "verified_at_kst": "2025-12-30T23:00:24.132456+09:00"
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
      "match": "MIL@CHA",
      "details": "MIL -3.5",
      "total": 227.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T00:00Z",
      "event_id": "401810302"
    },
    {
      "match": "PHX@WSH",
      "details": "PHX -10.5",
      "total": 233.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T00:00Z",
      "event_id": "401810303"
    },
    {
      "match": "GS@BKN",
      "details": "GS -6.5",
      "total": 226.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T00:30Z",
      "event_id": "401810304"
    },
    {
      "match": "DEN@MIA",
      "details": "DEN -1.5",
      "total": 244.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T00:30Z",
      "event_id": "401810305"
    },
    {
      "match": "ORL@TOR",
      "details": "ORL -1.5",
      "total": 220.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T00:30Z",
      "event_id": "401810306"
    },
    {
      "match": "MIN@CHI",
      "details": "MIN -6.5",
      "total": 243.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T01:00Z",
      "event_id": "401810307"
    },
    {
      "match": "IND@HOU",
      "details": "HOU -13.5",
      "total": 222.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T01:00Z",
      "event_id": "401810308"
    },
    {
      "match": "NY@NO",
      "details": "NY -8.5",
      "total": 247.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T01:00Z",
      "event_id": "401810309"
    },
    {
      "match": "ATL@OKC",
      "details": "OKC -17.5",
      "total": 232.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T01:00Z",
      "event_id": "401810310"
    },
    {
      "match": "CLE@SA",
      "details": "SA -3.5",
      "total": 244.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T01:00Z",
      "event_id": "401810311"
    },
    {
      "match": "DAL@POR",
      "details": "POR -2.5",
      "total": 232.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-30T03:30Z",
      "event_id": "401810312"
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
      "match": "MIL@CHA",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "PHX@WSH",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "GS@BKN",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "DEN@MIA",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "ORL@TOR",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "MIN@CHI",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "IND@HOU",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "NY@NO",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "ATL@OKC",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "CLE@SA",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "DAL@POR",
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