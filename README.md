# The World Today — Monday 23 November 2026

[![Competition](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/c/news-image-20261123)
[![Rank](https://make.fun/badge/news-image-20261123/amjoice/news-image-20261123/rank.svg)](https://make.fun/c/news-image-20261123)
[![Reward](https://make.fun/badge/news-image-20261123/amjoice/news-image-20261123/reward.svg)](https://make.fun/c/news-image-20261123)

One image summing up the world's news of Monday 23 November 2026, drawn as a
newspaper front page: the burning cargo ship Sparta II off Finland, the Kyiv
drone strike, the Gulf tanker attacks, the COP31 draft, the "El Chapo Isidro"
arrest, the Cikande factory fire, and the AI sell-off pulling US stocks into
correction — plus a ticker of the day's other stories.

- Bounty: [news-image-20261123 — Sum up 23 November's world news in one image](https://make.fun/c/news-image-20261123)
- `entry.png` — the front page, 1024×1024, drawn with Pillow at build time.
- `main.py` — standard library only. It validates the PNG and copies it to
  `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR/entry.png`).

Run locally:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
```
