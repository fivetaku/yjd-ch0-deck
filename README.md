# Ch0 오리엔테이션 데크

> 윤자동 원데이클래스 (2026-05-09) Ch0 발표용 자료

---

## 파일

| 파일 | 용도 |
|---|---|
| `deck.md` | Marp 마크다운 슬라이드 (7장) — 발표 + Speaker note 포함 |

---

## 사용

### Marp 으로 발표

```bash
# Marp CLI 설치 (1회)
npm i -g @marp-team/marp-cli

# HTML 변환
marp deck.md -o deck.html

# PDF 변환
marp deck.md --pdf -o deck.pdf

# PPTX 변환
marp deck.md --pptx -o deck.pptx

# 프레젠테이션 모드 (서버)
marp deck.md --server
```

### VS Code Marp 확장

1. VS Code 에서 Marp for VS Code 확장 설치
2. `deck.md` 열기
3. 우측 상단 미리보기 → "Marp: Open Preview to the Side"
4. 그대로 발표 (Speaker note 는 별도 창으로)

---

## 슬라이드 구성

| # | 제목 | 핵심 |
|:-:|---|---|
| 1 | 표지 | 강의명 + 날짜 + 강사 |
| 2 | 강사 소개 | 이철로 / 지피타쿠 / 10년 R&D 엔지니어 |
| 3 | 이 강의의 본질 | 따라쳤던 게 사라지지 않는다 — 내 워크스페이스 |
| 4 | 시간표 | 10:00~17:00 (실강 6H + 점심 1H) |
| 5 | Ch0 5 STEP | 인사·alias·Hook+env·모드·점검 |
| 6 | 시작 명령 | `/yjd-ch0` |
| 7 | Ch1 으로 | 다음 챕터 안내 |

---

## 진행 시간

총 30분 (10:00~10:30) — 슬라이드 7장이지만 5번 슬라이드 이후는 환경 셋업 시연 위주.

---

## 변경 이력

| 날짜 | 변경 |
|---|---|
| 2026-05-09 v2 | 대화 습관 슬라이드 삭제 / 강의 본질 (자신감 → 워크스페이스) / 시간 표기 정정 (7H → 6H+점심) / Speaker note patina 정돈 |
