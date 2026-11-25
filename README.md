# Symposium on Breathing Control for Radiation Therapy in Korea (2027)

2027년 3월 5일(금) 13:00–18:20, 연세암병원 서암강당(B3) 심포지엄 홈페이지입니다.
GitHub Pages에 그대로 올릴 수 있는 정적 사이트(HTML/CSS)입니다.

## 폴더 구성

```
index.html                 ← 모든 내용(소개, 인사말, 프로그램, 연자, 등록, 오시는 길, 포스터)
assets/css/style.css       ← 디자인(색상·글꼴·레이아웃)
assets/img/                ← 히어로 그림, 포스터, 로고, 장지석 교수님 사진, 파비콘
.nojekyll                  ← GitHub Pages가 파일을 그대로 서비스하도록 하는 빈 파일
```

## 자주 고칠 곳 (index.html에서 검색)

| 바꿀 내용 | 검색어 |
|---|---|
| 연자 영문 이름·소속 | 이름 (예: `Dosol Yoo`) — 프로그램 표와 Speakers 카드 두 곳 모두 수정 |
| 발표 제목 | `CPAP`, `NIMV-60p` |
| 좌장 | `Chair to be announced` |
| 등록 링크 | `Register (coming soon)` — `href="#registration" aria-disabled="true"`를 `href="구글폼 주소"`로 바꾸고 `aria-disabled` 삭제 |
| 포스터 이미지 | `assets/img/poster.jpg` 파일 교체 |

## GitHub Pages로 공개하기

### A. `bric.github.io` 주소를 쓰려면
1. GitHub에서 이름이 **BRIC**인 계정 또는 Organization을 만듭니다
   (github.com → 오른쪽 위 `+` → **New organization** → Free 플랜).
   이름이 이미 사용 중이면 `bric-korea`, `bcrt-korea` 같은 다른 이름을 써야 합니다.
2. 그 Organization 아래에 저장소 이름을 정확히 **`BRIC.github.io`** 로 만듭니다 (Public).
3. 이 폴더의 파일을 모두 업로드합니다 (`Add file` → `Upload files`, `.nojekyll` 포함).
4. 저장소 **Settings → Pages** → Source: `Deploy from a branch`, Branch: `main` / `/(root)` → Save.
5. 1–2분 뒤 `https://bric.github.io` 에서 열립니다 (GitHub 주소는 항상 소문자로 표시됩니다).

### B. 개인 계정 아래 프로젝트 주소로 쓰려면
기존 계정에 `bcrt2027` 같은 저장소를 만들고 같은 방식으로 올리면
`https://<계정이름>.github.io/bcrt2027/` 로 열립니다.
