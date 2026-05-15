# MIRAI Gallery

> 디자인 시스템·토큰은 [`../shared/CLAUDE.md`](../shared/CLAUDE.md) 참조.

## 페이지

| 파일 | 설명 |
|---|---|
| `gallery-prototype.html` | 갤러리 — 풀스크린 (사이드바·바텀네비 없음) |

## 진입점

마이페이지 갤러리 탭의 카드 클릭 시 진입.

## 특이사항

- **풀스크린 모달 컨테이너**: `.screen` 클래스로 자체 풀스크린. `.app` grid 구조 사용 X.
- **shared 토큰만 참조**.
- **viewer**: 썸네일 클릭 시 큰 이미지 모달. prev/next 무한 캐러셀 (끝→처음 wrap-around).

## 이미지 에셋

`./images/` 하위 — 캐릭터 일러스트 (해금/잠금 변형 있음).
