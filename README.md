# colorwall-legal

Support, FAQ, privacy policy, terms of use and legal notice of the iOS app Colorwall: Cozy Coloring,
served by GitHub Pages at https://mario-coder-apps.github.io/colorwall-legal/ (part of the Cavebeer Entertainment
studio site, like idlemonsterforge-legal and idletransportcorp-legal). Plain HTML, no cookies, no third-party content.

`index.html` (English) and `de/index.html` (German) are the app's content page (2026-11-16): what the app is, how
it plays, books, prices, FAQ, support; hreflang pair, Open Graph images `og.jpg` / `de/og.jpg`, JSON-LD
(MobileApplication + FAQPage = the visible FAQ, word for word), screenshots in `img/` (`en-*` / `de-*`, 600 px).
The English page sends `#de` (old links, the legal pages' language switch) to `de/`. On release day: the store
button says "Download on the" / "App Store" ("Laden im" / "App Store"), add
`<meta name="apple-itunes-app" content="app-id=6830637527">` and `downloadUrl` / `installUrl` in the JSON-LD of both
pages. When an FAQ answer changes, change its JSON-LD text the same way.

`press/` is the press kit (English, one page: fact sheet, description, the six App Store screenshots of
1.0.0, the icon). Update its release date and App Store line on release day.
