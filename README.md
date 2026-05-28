# 사업시도 1차 — 로컬 업체 웹사이트 제작·판매

> 상태: Research 단계 대기 중

## 한 줄 요약

홈페이지 없는 로컬 업체를 찾아 → Claude로 웹사이트를 먼저 만들어 → 무료 제안으로 판매하는 수익화 실험.

## 비즈니스 플로우

```
구글맵으로 업체 발굴
    ↓
홈페이지 없는 곳 필터링 (리뷰 있고 활발히 영업 중)
    ↓
Claude + getdesign.md로 웹사이트 시안 제작
    ↓
"보고 만들어봤습니다" 방식으로 먼저 가치 제공
    ↓
수락 → 아임웹 호스팅 연결 후 최종 전달
    ↓
유지보수·SEO 지속 수익으로 확장
```

## 디렉터리 구조

```
/
├─ CLAUDE.md          # 프로젝트 헌법 (규칙·프로세스·금지사항)
├─ RESEARCH.md        # Research 단계 산출물
├─ PLAN.md            # Plan 단계 산출물
├─ REVIEW.md          # Review 단계 산출물
├─ README.md          # 이 파일
└─ .claude/
   └─ commands/
      ├─ research.md   # /research 커맨드
      ├─ plan.md       # /plan 커맨드
      ├─ execute.md    # /execute 커맨드
      ├─ review.md     # /review 커맨드
      ├─ ship.md       # /ship 커맨드
      └─ orchestrate.md # /orchestrate 커맨드
```

## Agentic Engineering 프로세스

```
/research → (승인) → /plan → (승인) → /execute → (승인) → /review → (승인) → /ship
```

현재 단계 확인은 `/orchestrate` 실행.

## 참고 자료

- 원본 가이드: https://seulstudio.notion.site/3666970e8916805aac6ec734eeafb551
- 와이어프레임 가이드: https://seulstudio.notion.site/34e6970e891680fbafbbe4390720a031
- 와이어프레임 소스: https://getdesign.md
