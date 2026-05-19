# Zion Study Abroad GitHub Pages 배포 가이드

이 폴더의 파일을 GitHub 저장소 `my-website` 루트에 업로드하면 됩니다.

## 기준 주소

https://bookkeeping1004-dev.github.io/my-website/

## 업로드해야 하는 파일

- index.html
- about.html
- results.html
- testimonials.html
- college-admissions.html
- boarding-school.html
- international-school.html
- apush-dbq-guide.html
- ap-gov-frq-guide.html
- sat-ssat-guide.html
- gpa-management.html
- faq-contact.html
- sitemap.xml
- robots.txt
- .nojekyll
- assets/site.css
- assets/og-image.png
- assets/kakao-ljmuskorea-qr.png

## 배포 후 확인

1. `https://bookkeeping1004-dev.github.io/my-website/` 접속
2. `https://bookkeeping1004-dev.github.io/my-website/sitemap.xml` 접속: XML이 바로 보여야 합니다.
3. `https://bookkeeping1004-dev.github.io/my-website/robots.txt` 접속: Sitemap 주소가 보여야 합니다.
4. Search Console에서 URL prefix로 `https://bookkeeping1004-dev.github.io/my-website/` 등록
5. sitemap 제출: `https://bookkeeping1004-dev.github.io/my-website/sitemap.xml`
6. URL 검사에서 홈과 주요 자료 페이지를 색인 요청

## 주요 SEO 구조

- 12개 주요 페이지
- 페이지별 고유 title/description/canonical
- sitemap.xml에 모든 URL 포함
- robots.txt에서 크롤링 허용
- 내부 링크와 관련 페이지 링크 강화
- FAQPage, Article, BreadcrumbList, EducationalOrganization 구조화 데이터 포함
