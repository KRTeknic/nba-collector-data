[SNAPSHOT_SOURCE]
{
  "verified_at": {
    "verified_at_utc": "2025-12-25T23:35:50.423948+00:00",
    "verified_at_et": "2025-12-25T18:35:50.423948-05:00",
    "verified_at_kst": "2025-12-26T08:35:50.423948+09:00"
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
      "match": "CLE@NY",
      "details": "NY -5.5",
      "total": 241.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-25T17:00Z",
      "event_id": "401809238"
    },
    {
      "match": "SA@OKC",
      "details": "OKC -9.5",
      "total": 233.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-25T19:30Z",
      "event_id": "401809239"
    },
    {
      "match": "DAL@GS",
      "details": "GS -8.5",
      "total": 229.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-25T22:00Z",
      "event_id": "401809240"
    },
    {
      "match": "HOU@LAL",
      "details": "HOU -2.5",
      "total": 231.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-26T01:00Z",
      "event_id": "401809241"
    },
    {
      "match": "MIN@DEN",
      "details": "DEN -1.5",
      "total": 239.5,
      "provider": "Draft Kings",
      "start_utc": "2025-12-26T03:30Z",
      "event_id": "401809242"
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
      "match": "CLE@NY",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "SA@OKC",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "DAL@GS",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "HOU@LAL",
      "candidate": "PASS",
      "reason": "현재 단계: SSOT/드리프트/게이트 자동화 완료. 모델 코어(백서 11.5a) 픽 엔진 연결은 다음 단계에서 적용."
    },
    {
      "match": "MIN@DEN",
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