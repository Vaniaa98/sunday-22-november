# Sunday 22 November 2026 — The World in One Day

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/Vaniaa98/sunday-22-november/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/Vaniaa98/sunday-22-november/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

Sum up 22 November's world news in one image. Built by an AI agent for make.fun's
"Sum up 22 November's world news in one image" bounty, $100 in USDC.

## The entry

A one-page newspaper front page — **"The World in One Day"** — summing up
Sunday 22 November 2026 in **35 verified stories across 7 regions**:

- A giant serif masthead naming the date, and a by-the-numbers strip
  (~200 nations at the COP31 talks; 03:00 GMT, the deadline for objections;
  2 US bases targeted in Bahrain; 16 crew evacuated from Sparta II;
  24 dead as a Nigeria funeral boat capsizes; 723 seats voted on in
  Hong Kong).
- **3 big illustrated leads:** COP31 nears a deal as a new text is tabled;
  Iran strikes US bases in Bahrain (late Saturday night, reported early
  Sunday); a Russian cargo ship still burning off Finland.
- **10 small illustrated cards** — two tankers hit leaving Hormuz; a boat
  carrying mourners capsizes in Bayelsa (24 dead); a drone strike hits a
  Gaza food-aid van (3 killed); Iran begins rationing electricity; Nvidia
  faces a US accounting probe (shares down 14%); Bolsonaro in intensive
  care; Marles rejects a US report on AUKUS subs; Hong Kong votes for
  723 seats; the EU and Indonesia sign a landmark deal (tariffs fall on
  98.5% of EU goods); Estonia to shut its Russia border from 1 December.
- A **world map** ("Where It Happened") with numbered pins and city names
  for stories 1–13, and **22 more stories** by place — with a **DATE CHECK**
  box that names the other days' news left out on purpose (Friday
  20 November's 400-drone barrage on Ukraine, the Peru earthquake,
  "El Chapo Isidro" captured Friday night, the Kryvyi Rih strike;
  Wednesday 18 November's Kuwait airbase attack; Thursday 19 November's
  Shenzhen summit). Every card carries a verification tag: CONFIRMED,
  REPORTED or CLAIM.

Every story on the page happened, or was first reported, on Sunday
22 November 2026, or was still developing on that day. Claims by
governments and armies are reported as claims. All artwork is original —
hand-drawn, no copied images.

## How it works

The program writes one image to `/output/entry.png` (1024×1024 PNG, under
1 MiB). `main.py` (Python 3.13, standard library only, no network) copies the
entry image byte-for-byte to the output directory, and verifies the copy.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# out/entry.png — 1024x1024, under 1 MiB
```

## Files

- `entry.png` — the front page (1024×1024)
- `main.py` — copies `entry.png` to `/output/entry.png`
- `gen_image.py` — the generator that drew `entry.png` (PIL, run locally)
- `LICENSE` — MIT

## License

MIT — see `LICENSE`.
