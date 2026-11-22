# The World in One Day — 22 November 2026

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/nofrizal05/makefun-news-22nov/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/nofrizal05/makefun-news-22nov/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

Entry for the make.fun competition **news-image-20261122**: "Sum up
22 November's world news in one image" ($100, entries close 2026-11-24 07:00 WIB).

Bounty page: https://make.fun/bounty/news-image-20261122

A hero-led newspaper front page (1024×1024) for Sunday, 22 November 2026:

- **Lead story — NATO vows to defend every inch of Poland.** Secretary
  General Rutte in Warsaw after Russian missiles landed in Poland; the
  alliance will bolster air defences and the North Atlantic Council meets
  Monday.
- **COP31 talks in deadlock** — the fossil-fuel fight stalls the climate
  talks; no final deal yet.
- **Iran attacks US base** — strike on Kuwait amid wider Gulf attacks in
  the ninth month of war.
- **Magnitude 6.9 quake hits Peru** — Andean tremor felt widely; no damage
  or casualties yet.
- **'El Chapo Isidro' arrested in Mexico raid** — alleged cartel boss
  Fausto Isidro Meza Flores seized by special forces.
- **AI sell-off spreads; markets plunge** — Nikkei −5.06%, Kospi −5.21%;
  €370bn wiped off Europe in one session.
- Footer strip: Cyclone Akvan weakens, FBI probes NCIC database hack, ANC
  fights to hold South African cities, Denmark expels Russian military
  attache, Trump threatens ban on overseas AI data centres, Australia ends
  England's T20 streak, ADNOC vessel attacked in Hormuz.

## How it works

`main.py` is Python standard library only (`os`, `shutil`, `pathlib`): it
copies the shipped `entry.png` to `MAKEFUN_OUTPUT_DIR` (default `/output`).
The image itself was drawn locally with Pillow and is shipped as a finished
asset, so the entry runs deterministically in the grading sandbox — running
`main.py` twice writes byte-identical output.

## Verify locally

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out1 python3 main.py
MAKEFUN_OUTPUT_DIR=/tmp/out2 python3 main.py
sha256sum /tmp/out1/entry.png /tmp/out2/entry.png  # identical
file /tmp/out1/entry.png                            # 1024x1024 PNG, < 1 MiB
```
