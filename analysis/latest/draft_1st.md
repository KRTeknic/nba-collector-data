[SNAPSHOT_SOURCE]
{
  "verified_at": {
    "verified_at_utc": "2026-03-28T13:53:10.734013+00:00",
    "verified_at_et": "2026-03-28T09:53:10.734013-04:00",
    "verified_at_kst": "2026-03-28T22:53:10.734013+09:00"
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
      "match": "HOU@MEM",
      "details": "HOU -13.5",
      "total": 229.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T00:00Z",
      "event_id": "401810924"
    },
    {
      "match": "CHI@OKC",
      "details": "OKC -19.5",
      "total": 241.5,
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
      "details": "DEN -19.5",
      "total": 246.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T01:00Z",
      "event_id": "401810927"
    },
    {
      "match": "WSH@GS",
      "details": "GS -12.5",
      "total": 230.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T02:00Z",
      "event_id": "401810928"
    },
    {
      "match": "DAL@POR",
      "details": "POR -10.5",
      "total": 240.5,
      "provider": "Draft Kings",
      "start_utc": "2026-03-28T02:00Z",
      "event_id": "401810929"
    },
    {
      "match": "BKN@LAL",
      "details": "LAL -18.5",
      "total": 224.5,
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