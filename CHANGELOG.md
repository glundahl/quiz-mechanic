# Changelog — Quiz Mechanic

Most recent changes at the top.

## v0.4 — 2026-09-07
- Quiz groups via `?group=` — CPFO-only picker: `?group=cpfo`; kids math: `?group=kids`
- Manifest `group` field (`cpfo` / `kids`); CPFO cards use a CPFO badge

## v0.3 — 2026-09-03
- Browser tab: picker/home shows **Quiz Mechanic**; in-quiz tabs still use `{Quiz title} — Quiz Mechanic`
- CPFO Treasury & Investment Management practice exam (200 Qs) + distractor quality rewrite
- Debt management distractor rewrite (related misconceptions)

## v0.2 — 2026-05-24
- Normalize math notation in renderer: `^2` → `²`, `^3` → `³`, `sqrt()` → `√`
- Updated question generation prompt to use Unicode math notation directly

## v0.1 — 2026-05-24
- Initial release: Math Exam Review quiz (55 questions, 9 sections)
- Dynamic SPA fetching quiz JSON at runtime
- Section tabs, instant feedback, progress bar, score card, missed-question review
- GitHub Pages deployment at https://glundahl.github.io/quiz-mechanic/
