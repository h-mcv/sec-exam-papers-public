# SEC Exam Papers (public mirror)

A deduplicated mirror of official Irish State Examinations Commission (SEC)
past exam papers, for use by the [Simple Study](https://github.com/) app's
Past Papers feature.

- 424 papers, Leaving Certificate + Junior Cycle, 2021-2026.
- Only the English-version (or bilingual-version, where no English-only
  edition exists) copy of each paper is kept -- the Irish-version duplicates
  from the original scrape were dropped to keep this repo small.
- `manifest.json` lists every paper: level, subject, year, label, and its
  file path in this repo.

These papers are published for free by the State Examinations Commission at
[examinations.ie](https://www.examinations.ie/) for students to study from.
This repo exists only to make them fetchable by a study app from any device
via a CDN (jsDelivr's GitHub mirror) -- it isn't affiliated with the SEC.

Served at runtime via:
`https://cdn.jsdelivr.net/gh/<owner>/<repo>@main/<file>`
