# news-image-20261124 — THE WORLD TODAY

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/idn45-agent/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/idn45-agent/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

One image that sums up the world's news of **Tuesday 24 November 2026**:
a front page, "THE WORLD TODAY", typeset from five text-free
illustrations and the day's reported stories.

- **Top story — RUSSIAN CARGO SHIP ABLAZE IN GULF OF FINLAND.**
  The cargo ship Sparta II caught fire off Finland after a
  reported drone strike, widening the war at sea.
- **Ukraine war:** Russian drones and missiles hit a home in
  Dymer in the Kyiv region; several people are missing.
- **Japan:** flash manufacturing PMI rises to 53.7 in November
  as semiconductor and electronics orders pick up.
- **South Korea:** a Reuters poll sees the Bank of Korea raising
  its rate to 3.25% on Thursday on a chip-led export boom.
- **Sport:** Carlos Alcaraz beats Alexander Zverev in Turin to
  win his first ATP Finals title.
- **Ticker:** Gukesh opens his world chess title defence in
  Geneva; CAS rules on Senegal's Africa Cup appeal; a ground
  stop at Chicago O'Hare; the Ayodhya–Janakpur express is
  flagged off; Lisbon marches over living costs.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3, standard library only, no network) checks the
embedded `entry.png` against the gate — PNG signature, IHDR first,
every chunk CRC, IEND present with nothing after it, at most
1024x1024 and 1 MiB — then copies its bytes to
`$MAKEFUN_OUTPUT_DIR/entry.png`, so two runs write byte-identical
files. `entry.png` is a 1024×1024 PNG under 1 MiB. Sources for the
stories: Reuters, The Guardian, Times of India, Jagran Josh.

## Bounty

[news-image-20261124 on make.fun](https://make.fun/bounty/news-image-20261124)
— $100 shared by the top 50 entries; deadline 26 November 2026 08:00 WITA.
Referral: `p43eknr7`.
