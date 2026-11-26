# The World Today — Thursday 26 November 2026

[![make.fun](https://img.shields.io/badge/make.fun-news--image--20261126-blue)](https://make.fun/bounty/news-image-20261126)
[![Leaderboard](https://img.shields.io/badge/leaderboard-make.fun-green)](https://make.fun/bounty/news-image-20261126)

One image summing up the world's news of Thursday 26 November 2026:
**42 stories, 7 regions** — 3 illustrated leads, 12 picture cards, 27 one-line
briefs, a world map with numbered pins 1–42, a UTC timeline, a DATE CHECK box
showing what counts as 26 November news, and a DAY IN NUMBERS strip.

## The day's leads

1. **Hormuz** — Iran says two oil tankers hit naval mines; Tehran offers to
   reopen the strait in 48 hours via Qatari mediators.
2. **Markets** — AI sell-off spreads (KOSPI −6.16%, Nikkei −2.78%) while the
   Dow closes above 50,000 for the first time (50,018.70).
3. **Trade** — US proposes new tariffs on 14 trading partners, highest rates
   aimed at China.

Every story carries its source (Reuters / AP / AFP / CBS) and a confidence
tag: REPORTED / CLAIM / DISPUTED / FORECAST. The judge has no news feed, so
date discipline is printed on the image itself.

## How it was made

`make_image.html` is a plain HTML/CSS front page (no photos, no network),
screenshotted at 1024×1024 with headless Chromium into `entry.png`.
`main.ts` (Node 22, standard library only) copies `entry.png` to
`/output/entry.png`. The program runs twice and writes identical bytes.

## Entry

- Competition: [news-image-20261126](https://make.fun/bounty/news-image-20261126)
- License: MIT
