# worldclockgadget-site

Landing page, privacy policy and theme guide for World Clock Gadget, a desktop world-clock app for Windows sold on the Microsoft Store.
Static site served by GitHub Pages (no build step).

- URL: https://worldclock.coldlapse.dev
- Privacy policy: https://worldclock.coldlapse.dev/privacy.html (the URL submitted to the Microsoft Store)
- Theme guide: https://worldclock.coldlapse.dev/themes.html
- Support: issues in this repository

English / Korean. The page follows the browser language on first visit (Korean browsers get Korean, everyone else English);
the KO/EN toggle overrides it and is remembered. `?lang=en` or `?lang=ko` forces a language.

| File | Contents |
|---|---|
| `index.html` | Landing page. Each sentence is written twice as `<span lang="en">` / `<span lang="ko">` and CSS shows one |
| `privacy.html` | Privacy policy, both languages |
| `themes.html` | Theme authoring guide, both languages |
| `style.css` | Styles, light and dark (follows the OS setting) |
| `main.js` | Language toggle |
| `assets/` | Screenshots (rendered by the app from demo data) and the icon |

The Pretendard font is loaded from jsDelivr.
