# Liferary — 신입 부원 모집 페이지

독서 모임 라이프러리의 부원 모집 랜딩 페이지입니다. 빌드 과정 없는 정적 사이트(`index.html` + `assets/`)예요.

## 수정하기
- 문구·모집 정보: `index.html`의 첫 화면(모집 일정)과 손님 초대·지원 섹션의 문장을 바꾸면 돼요.
- 책장 카드: `index.html` 하단 스크립트의 `books` 배열에 책을 추가하면 흘러가는 책장에 자동으로 붙어요.
- 지원서 링크: `지원서 쓰러 가기` 버튼의 구글폼 주소.

## 배포 (Vercel)
1. vercel.com → Add New → Project → 이 저장소 Import
2. Framework Preset: **Other**, Build Command 비움, Output Directory 비움
3. Deploy — 이후 `main`에 push할 때마다 자동 배포돼요.
