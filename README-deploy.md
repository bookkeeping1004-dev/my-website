# 시온유학원 · Zion Study Abroad 배포 최종본

이 폴더는 시온유학원 홈페이지 배포용 최종본입니다.

## 포함 파일

- `index.html` — 메인 홈페이지. 카카오톡 QR 이미지는 HTML 내부에 직접 삽입되어 있어 이미지 경로 문제 없이 표시됩니다.
- `robots.txt` — 검색엔진 크롤링 허용 및 sitemap 위치 안내.
- `sitemap.xml` — Google Search Console 제출용 사이트맵.
- `assets/kakao-ljmuskorea-qr.png` — 카카오톡 QR 원본 백업 파일.

## 현재 반영 정보

- 영문명: Zion Study Abroad
- 한글명: 시온유학원
- 이메일: bookkeeping1004@gmail.com
- 전화번호: 010-2582-3993
- 카카오톡 ID: ljmuskorea
- 주소: 서울 서초구 강남대로 381 501호 시온유학원
- 최근 합격 소식: UC Irvine, University of Wisconsin, Northeastern University, Cornell University, Tufts University

## 배포 전 반드시 수정할 항목

현재 기본 도메인은 `zionstudyabroad.com`으로 넣어두었습니다. 실제 사용할 도메인이 다르면 아래 파일에서 모두 변경하세요.

- `index.html`
  - `<link rel="canonical" href="https://zionstudyabroad.com/">`
  - `og:url`
  - JSON-LD의 `url`
- `robots.txt`
  - `Sitemap: https://zionstudyabroad.com/sitemap.xml`
- `sitemap.xml`
  - `<loc>https://zionstudyabroad.com/</loc>`

## 추천 배포 방식: Vercel

1. GitHub에 새 저장소 생성
2. 이 폴더 안의 파일을 저장소 루트에 업로드
3. Vercel에서 New Project → GitHub 저장소 Import
4. Framework Preset은 Other 또는 Static으로 두고 배포
5. 배포 후 Vercel Domains에서 실제 도메인 연결
6. 도메인 DNS 설정 완료 후 `https://내도메인/` 접속 확인

## Google 노출 세팅 순서

1. Google Search Console 접속
2. Domain Property 또는 URL Prefix Property 추가
3. DNS TXT 방식 또는 HTML 파일 방식으로 소유권 인증
4. `https://내도메인/sitemap.xml` 제출
5. URL Inspection에서 `https://내도메인/` 검사
6. 문제가 없으면 Request indexing 요청
7. 1~2주 동안 Coverage / Indexing / Enhancements 상태 확인

## 추가로 하면 좋은 작업

- Google Business Profile 등록: 서초구 오프라인 유학원 검색 노출에 도움
- 실제 합격 사례가 추가될 때마다 홈페이지의 Recent Results 섹션 업데이트
- `University of Wisconsin`이 Madison 캠퍼스라면 `University of Wisconsin–Madison`으로 표기 변경
- 블로그/칼럼 페이지 추가: “미국 대학 입시”, “보딩스쿨”, “국제학교 전학” 등 키워드별 노출 확대
