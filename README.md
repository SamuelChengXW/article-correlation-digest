# Article Correlation Digest — Archive

A static, auto-updating archive of daily digests: does CNBC / The Edge
coverage support or contradict specific investment claims made in tracked
[FSMOne](https://www.fsmone.com.my) research articles?

**Live site:** published via GitHub Pages from `docs/`.

This repo holds only the site and the digest history (`docs/digests/*.json`)
— no source code, no credentials. It's updated automatically each day by
a separate private automation repo, which pushes here using a deploy key
scoped only to this repo.

- `docs/index.html` — the site (single self-contained file, no build step).
- `docs/digests/index.json` — manifest of all archived dates.
- `docs/digests/{date}.json` — structured findings for one day.
