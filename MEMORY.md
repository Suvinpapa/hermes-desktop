# hermes-desktop Memory

## 현재 상태
<!-- 대시보드가 읽는 스냅샷. 매 세션 종료 시 덮어쓴다. 형식 고정. -->
```yaml
status: active
last_agent: antigravity
last_branch: main
last_session: 2026-06-01T13:38:00+09:00
session_count: 3
```

## 프로젝트 개요
Hermes Agent Desktop — self-improving AI assistant

## 기술 스택
- Electron (v39.2.6)
- React (v19.2.1)
- TypeScript (v5.9.3)
- Tailwind CSS (v4.2.2)
- SQLite (better-sqlite3 v12.8.0)
- electron-vite (v5.0.0)

## 아키텍처 결정
- *아직 기록된 아키텍처 결정 사항이 없습니다.*

## 코드 컨벤션
- *아직 기록된 코드 컨벤션이 없습니다.*

## 알려진 제약사항
- *아직 기록된 알려진 제약사항이 없습니다.*

## 하지 말 것
- *아직 기록된 하지 말 것(안티패턴)이 없습니다.*

## 세션 로그
<!-- 추가 전용. 한 세션 = 한 행. 대시보드가 마지막 행 = 직전 세션으로 읽는다. -->
| session_end | agent | branch | status | summary |
|---|---|---|---|---|
| 2026-06-01T10:58:30+09:00 | antigravity | main | active | 초기 MEMORY.md 생성 및 프로젝트 확인 |
| 2026-06-01T11:53:00+09:00 | antigravity | main | active | WSL2 systemd 자동실행 환경변수 주입 및 SSH 무암호 연동 완료 |
| 2026-06-01T13:38:00+09:00 | antigravity | main | active | SSH 세션 연동 오류(API_SERVER_KEY) 해결 및 Gemini 3.1 flash lite 모델 설정 완료 |
