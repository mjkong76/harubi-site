# 하루비 Harubi — 공개 웹사이트

App Store 제출용 **개인정보 처리방침 / 지원** 페이지와 **언어별 소개(랜딩) 페이지**입니다. 앱 소스는 별도 비공개 저장소에 있습니다.

- 개인정보 처리방침: `index.html` — **App Store Connect에 개인정보 처리방침 URL로 등록된 파일. 다른 용도로 바꾸지 말 것.**
- 지원: `support.html`
- 소개(랜딩): `ko/index.html`, `en/index.html`, `de/index.html` → `/ko/`, `/en/`, `/de/` 로 서빙
- 사이트맵: `sitemap.xml`

모든 페이지는 외부 CDN·폰트·스크립트 없이 자체 완결형이며 라이트/다크 모드를 지원합니다.
랜딩 페이지끼리는 `hreflang` 로 연결되어 있으므로, URL 구조를 바꾸면 각 파일의 `canonical`·`hreflang`·`sitemap.xml` 을 함께 고쳐야 합니다.

## 게시 방법 (GitHub Pages)
1. GitHub에서 **public** 저장소를 새로 만듭니다 (예: `harubi-site`).
2. 이 폴더의 파일(`index.html`, `support.html`, `README.md`)을 올립니다.
3. 저장소 **Settings → Pages → Source: `main` / `/ (root)`** 로 설정 → 저장.
4. 몇 분 뒤 공개됩니다:
   - 개인정보: `https://<사용자명>.github.io/harubi-site/`
   - 지원: `https://<사용자명>.github.io/harubi-site/support.html`

이 두 URL을 App Store Connect의 **개인정보 처리방침 URL / 지원 URL** 에 입력하세요.

문의: mjkong76@gmail.com
