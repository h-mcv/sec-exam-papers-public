# SEC Exam Papers (public mirror)

A deduplicated mirror of official Irish State Examinations Commission (SEC)
past exam papers, for use by the [Simple Study](https://github.com/) app's
Past Papers feature.

- 527 locally mirrored PDFs, including 488 exam papers and 39 marking
  schemes. Leaving Certificate + Junior Cycle coverage includes 1996-2026
  where source material is available.
- Only the English-version (or bilingual-version, where no English-only
  edition exists) copy of each paper is kept -- the Irish-version duplicates
  from the original scrape were dropped to keep this repo small.
- `manifest.json` lists every paper: level, subject, year, label, and its
  file path in this repo.
- Local Mathematics papers and marking schemes from 1996-2024 were imported
  from a public study-resource mirror where the SEC PDFs were available.
- Junior Cycle Science papers and marking schemes from 2019 and 2022-2025
  were imported from a public study-guide repository.
- Additional marking schemes were imported from the StudyClix public CDN for
  subjects and years where the matching local exam paper is present.

These papers are published for free by the State Examinations Commission at
[examinations.ie](https://www.examinations.ie/) for students to study from.
This repo exists only to make them fetchable by a study app from any device
via a CDN (jsDelivr's GitHub mirror) -- it isn't affiliated with the SEC.

Served at runtime via:
`https://cdn.jsdelivr.net/gh/<owner>/<repo>@main/<file>`
