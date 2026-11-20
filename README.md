# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/calm-puffin-80-5828/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/calm-puffin-80-5828/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in under 4 KB of Python (stdlib only). Negamax alpha-beta search with quiescence, a transposition table with exact/lower/upper bound flags, principal variation search, late move reductions, MVV-LVA and killer-move ordering, and a material + piece-square evaluation. Fully deterministic: a fixed 45,000-node budget per move, no clock, no randomness. The readable source is packed into the shipped main.py with the competition kit's own compressor.

## Run it

```sh
MAKEFUN_ENV_URL=<gauntlet env url> python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=7jh68hq8&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
