# RESUME 프로토콜 v1 (표준 운영 템플릿) + RESUME.AUTO v1

본 문서는 Teknic NBA 운영 파이프라인에서 “새 채팅방/새 세션에서도 SSOT(깃허브 산출물) 링크만으로 상태 복원” 및
“사용자는 국내 OPEN 앵커만 입력하면 날짜/런모드 자동 판정 후 분석까지 자동 진행”을 위한 표준 규격이다.

---

## 0) 핵심 규칙 (Immutable)

1. **SSOT(깃허브 산출물) 링크만으로 상태 복원**
   - latest/ 또는 history/<TS>/ 산출물만 사용한다.
2. **국내 OPEN 앵커는 사용자 입력(LOCK)**
   - 절대 덮어쓰지 않는다.
   - SSOT는 “드리프트(변동값) 비교” 전용이다.
3. **FAIL-FAST**
   - `manifest.status.ESPN_ODDS != "OK"` 이면 즉시 종료:
     - `MARKET=UNAVAILABLE`
     - **대체 마켓/북 금지**
4. **출력 블록 순서 고정**
   - 템플릿에 정의된 순서를 반드시 유지한다.

---

## 1) SSOT 링크 (LATEST)

- manifest.json:
  - https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/manifest.json
- espn_odds.json:
  - https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_odds.json
- (optional) espn_scoreboard.json:
  - https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/espn_scoreboard.json
- (optional) nba_injury_report.pdf:
  - https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/nba_injury_report.pdf
- (optional) lineups_aux.json:
  - https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/lineups_aux.json
- (optional) injury_aux.json:
  - https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/injury_aux.json
- (optional) ref_assignments.json:
  - https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/ref_assignments.json
- (optional) fatigue_pack.json:
  - https://raw.githubusercontent.com/KRTeknic/nba-collector-data/main/latest/fatigue_pack.json

---

## 2) RESUME.AUTO v1 (사용자 입력 최소화: 국내 OPEN 앵커만)

### 목적
- 사용자는 **국내 OPEN 앵커만** 입력한다.
- 시스템(분석자/에이전트)은 **manifest 기반으로 run_kind(22:05/08:05) + slate_date(ET/KST) + baseline_ts(history) 자동 판정** 후
  FAIL-FAST 검사 → SSOT 로드 → 고정 출력 블록 생성까지 수행한다.

### 사용자 입력(새 채팅방 첫 메시지)
```text
[RESUME.AUTO_V1]
[OPEN_ANCHOR_LOCK]
<국내 OPEN 앵커만 여러 줄로 붙여넣기>
