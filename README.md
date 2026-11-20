# MLOps 실습 가이드 (2차) — GitHub Pages

| 파일 | 내용 |
|---|---|
| `index.html` | 첫 화면 (1일차 · 2일차 고르기) |
| `day1.html` | 1일차 — 0. 시작 전 · 실습 1~3 |
| `day2.html` | 2일차 — 실습 4~6 |
| `.nojekyll` | GitHub 의 Jekyll 처리를 끔 (그대로 올림) |

## 올리는 법
1. 이 폴더의 파일을 저장소 맨 위(또는 `docs/`)에 넣고 push
2. 저장소 Settings → Pages → Build and deployment → Source: **Deploy from a branch** → 브랜치 `main` · 폴더 `/ (root)` (또는 `/docs`) → Save
3. 1~2분 뒤 `https://<계정>.github.io/<저장소>/` 로 열림

## 주의
- 수강생판만 넣었습니다. 강사판(`[실습 가이드 웹] …`)은 과제 값이 들어 있어 넣지 않습니다.
- GitHub Pages 주소는 저장소가 비공개여도 누구나 열 수 있습니다.
- 그림은 html 안에 들어 있어 따로 올릴 파일이 없습니다. 글꼴만 Google Fonts 에서 받습니다(안 되면 기본 글꼴).
- 고칠 때는 `50_배포/[수강생 실습 가이드] …` 를 다시 만든 뒤 `20_교안/HTML/261117_실습가이드/make_site.py` 로 이 폴더를 다시 만듭니다.
