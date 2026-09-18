# KOR-0322 marketing site context

- Service: 재경관리사 3과목 500제
- Service ID: KOR-0322
- Android package / iOS bundle: `app.mcyj.examprep.kor0322`
- Scope: currently released app marketing site for GitHub Pages
- Locales: Korean primary, English support
- Design: ink-black, ledger green, and coral three-column accounting workbook
- Typography: preserve Korean word units with global `word-break: keep-all`
- Store badges: App Store and Google Play controls use identical 194 × 75 frames
- Public store links: exact Google Play package and App Store ID `6807132303`
- Official source: Samil Accounting Corporation qualification examination website
- Source app is read-only; website work is isolated in this repository.

## Verification log

- 2026-09-19: Initialized the isolated marketing-site project after confirming no local or remote repository collision.
- 2026-09-19: Built 34 indexable routes and 36 HTML files; automated checks passed for exact Store identities, the official three-subject structure, global Korean `keep-all`, and matching 194 × 75 marketplace controls.
- 2026-09-19: Local HTTP QA passed all 34 sitemap routes, four shared assets, and the missing-route 404 response.
- 2026-09-19: Created public repository `MCYJ/3-500-web`; GitHub Pages workflow run `35378142771` completed successfully.
- 2026-09-19: Production QA passed all 34 routes and four assets at `https://mcyj.github.io/3-500-web/`, plus App Store ID `6807132303`, Android package `app.mcyj.examprep.kor0322`, Samil official-source links, the 120-question/150-minute/each-subject-70 structure, global `keep-all`, equal badge frames, and a real 404 response.
