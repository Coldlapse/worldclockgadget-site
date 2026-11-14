# worldclockgadget-site

Zoneline의 랜딩 페이지, 개인정보 처리방침, 테마 가이드. Zoneline은 Microsoft Store에서 파는 Windows용 바탕 화면 세계 시계 앱이다.
GitHub Pages로 서비스하는 정적 사이트다(빌드 단계 없음).

- 주소: https://zoneline.coldlapse.dev
- 개인정보 처리방침: https://zoneline.coldlapse.dev/privacy.html (Microsoft Store에 제출하는 URL)
- 테마 가이드: https://zoneline.coldlapse.dev/themes.html
- 지원: 이메일 vegarian@dgu.ac.kr

영어와 한국어. 처음 방문하면 브라우저 언어를 따른다(한국어 브라우저는 한국어, 나머지는 영어).
KO/EN 토글로 바꾸면 그 선택을 기억한다. `?lang=en`, `?lang=ko`로 언어를 강제할 수 있다.

| 파일 | 내용 |
|---|---|
| `index.html` | 랜딩 페이지. 문장마다 `<span lang="en">`과 `<span lang="ko">`로 두 번 쓰고 CSS가 하나만 보여 준다 |
| `privacy.html` | 개인정보 처리방침, 두 언어 |
| `themes.html` | 테마 제작 가이드, 두 언어 |
| `style.css` | 스타일, 라이트와 다크(OS 설정을 따름) |
| `main.js` | 언어 토글 |
| `assets/` | 스크린샷(앱이 데모 데이터로 렌더링)과 아이콘 |

Pretendard 글꼴은 jsDelivr에서 불러온다.
