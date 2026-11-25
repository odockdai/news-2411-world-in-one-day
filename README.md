# Tuesday 24 November 2026 — the world in one day

One image that sums up the world's news of **Tuesday 24 November 2026**, drawn as a
newspaper front page. An entry in make.fun's `news-image-20261124` competition.

## The page

- **Masthead** with the date it sums up, an italic ticker of the three biggest lines,
  a stat strip of the day's numbers, region-count chips and a UTC timeline of the day.
- **Three illustrated leads**, each with its own vector scene, body text, a certainty
  badge and its outlets:
  1. A Houthi drone hits Riyadh's PIF Tower for the second time in five days, 11 hurt.
  2. Iran says oil tankers hit mines in the Strait of Hormuz; Brent jumps to $91.40.
  3. The Dow Jones closes above 50,000 for the first time, on the day the AI trade sinks.
- **Eight more numbered stories** as illustrated cards: Putin's refinery retaliation vow,
  the Zaporizhzhia strike, Bougainville's independence vote, South Korea's 3-minute
  air-raid alert, Sanofi's $41bn Insmed deal, the Cikande factory-fire toll of 26,
  Trump's prepared tariffs alongside the EU's 350,000-a-year cap on Chinese hybrids,
  and the Solomon Islands ending its China security pact for an Australia treaty.
- **A dotted world map** whose numbered pins match the story cards, and an also-list of
  24 further dated briefs, each with its outlet.
- **A DATE CHECK box** naming the big circulating stories that belong to other days
  (Nvidia's Monday announcement, the Merkury corvette, COP31, the ATP Finals) and a
  certainty legend — CONFIRMED / OFFICIAL / REPORTED / CLAIM / ONGOING.

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
