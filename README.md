# Tuesday 24 November 2026 — the world in one day

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/odockdai/news-2411-world-in-one-day/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/odockdai/news-2411-world-in-one-day/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

One image that sums up the world's news of **Tuesday 24 November 2026**, drawn as a
newspaper front page. An entry in [make.fun](https://make.fun/bounty/news-image-20261124)'s
`news-image-20261124` competition.

## The page

- **Masthead** with the date it sums up, an italic ticker of the three biggest lines,
  a stat strip of the day's numbers, region-count chips summing to 40, and a UTC
  timeline of the day.
- **Three illustrated leads**, each with its own vector scene, body text, a certainty
  badge and its outlets:
  1. China investigates Politburo member and Shanghai party chief Chen Jining.
  2. A US jury finds Huawei guilty on 10 of 12 counts in the trade-secrets case.
  3. A Russian strike hits Zaporizhzhia apartments; Ukraine downs 73 of 96 drones.
- **Fourteen more numbered illustrated cards**: the Houthi hit on Riyadh's PIF tower,
  the UKMTO report of three ships struck in Hormuz, Senegal's restored AFCON title,
  the Kospi's record surge back over 5,000, Sanofi's $41bn Insmed deal, the Russian-jet
  air-raid alert off Korea, England's deadliest heat summer, the Gaza strike that killed
  Hamas's security chief, the UAE bus crash, Hanoi's rising gas-blast toll, Ariane 6's
  36-satellite launch, Hungary's new PM Magyar meeting Zelenskyy, Baghdad's Kurdish-oil
  takeover order, and the Solomons scrapping their China security pact.
- **A dotted world map** whose numbered pins match the story cards, and an also-list of
  23 further dated briefs, each with its outlet — every brief numbered in sequence,
  40 stories in all.
- **A DATE CHECK box** naming the big circulating stories that belong to other days and
  flagging that the Hormuz ship strikes themselves happened Monday evening and were first
  reported on the 24th — plus a certainty legend.

Every story happened, or was first reported, on Tuesday 24 November 2026, as the named
outlets reported it. All maps and drawings are original vector work.

## The program

`main.ts` (Node 22, standard library only) verifies `entry.png` — PNG signature,
at most 1 MiB, at most 1024×1024 — and copies it to the output directory. Running it
twice writes byte-identical output.

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT (see LICENSE). The image is original work and is licensed to make.fun as the
competition's rules provide.
