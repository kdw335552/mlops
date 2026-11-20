# MLOps 실습 가이드 (2차)

[인공지능] 개발부터 운영까지 · MLOps 기반 AI 모델 관리 실습 · 2026-11-21 ~ 22 · 김덕우 강사

| 파일 | 내용 |
|---|---|
| `index.html` | 첫 화면 (1일차 · 2일차 고르기) |
| `day1.html` | 1일차 — 0. 시작 전 · 실습 1~3 |
| `day2.html` | 2일차 공개 전 안내 페이지 |
| `day2.html.enc` | 2일차 가이드(암호화). 11-22 08:30 KST 에 자동으로 풀려 `day2.html` 로 올라갑니다 |
| `.github/workflows/pages.yml` | GitHub Pages 배포. 08:30 전에는 안내 페이지, 뒤에는 2일차 |

## 처음 한 번 설정 (저장소 주인)
1. Settings → Pages → Build and deployment → Source: **GitHub Actions**
2. Settings → Secrets and variables → Actions → New repository secret — 이름 `DAY2_KEY`, 값은 강사 PC의 `웹가이드_비공개/DAY2_KEY.txt` 내용
3. Actions 탭에서 `pages` 가 초록색이면 `https://kdw335552.github.io/mlops/` 로 열립니다

GitHub 예약 실행은 UTC 기준(`30 23 21 11 *` = 11-22 08:30 KST)이고, 늦게 돌 수는 있어도 일찍 돌지는 않습니다. 늦으면 Actions → pages → Run workflow 로 바로 돌릴 수 있습니다(08:30 전에 누르면 안내 페이지 그대로).
