[SNAPSHOT_SOURCE]
{
  "verified_at": {
    "verified_at_utc": "2026-03-27T23:40:20.181489+00:00",
    "verified_at_et": "2026-03-27T19:40:20.181489-04:00",
    "verified_at_kst": "2026-03-28T08:40:20.181489+09:00"
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
      "match": "LAC@IND",
      "details": "LAC -8.5",
      "total": 239.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-27T23:00Z",
      "event_id": "401810921"
    },
    {
      "match": "ATL@BOS",
      "details": "BOS -5.5",
      "total": 226.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-27T23:30Z",
      "event_id": "401810922"
    },
    {
      "match": "MIA@CLE",
      "details": "CLE -5.5",
      "total": 242.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-27T23:30Z",
      "event_id": "401810923"
    },
    {
      "match": "HOU@MEM",
      "details": "HOU -13.5",
      "total": 227.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T00:00Z",
      "event_id": "401810924"
    },
    {
      "match": "CHI@OKC",
      "details": "OKC -19.5",
      "total": 239.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T00:00Z",
      "event_id": "401810925"
    },
    {
      "match": "NO@TOR",
      "details": "TOR -8.5",
      "total": 229.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T00:30Z",
      "event_id": "401810926"
    },
    {
      "match": "UTAH@DEN",
      "details": "DEN -18.5",
      "total": 248.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T01:00Z",
      "event_id": "401810927"
    },
    {
      "match": "WSH@GS",
      "details": "GS -13.5",
      "total": 232.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T02:00Z",
      "event_id": "401810928"
    },
    {
      "match": "DAL@POR",
      "details": "POR -10.5",
      "total": 239.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T02:00Z",
      "event_id": "401810929"
    },
    {
      "match": "BKN@LAL",
      "details": "LAL -16.5",
      "total": 222.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T02:30Z",
      "event_id": "401810930"
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
      "match": "LAC@IND",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "ATL@BOS",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "MIA@CLE",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "HOU@MEM",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "CHI@OKC",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "NO@TOR",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "UTAH@DEN",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "WSH@GS",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "DAL@POR",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "BKN@LAL",
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