# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/huimou612/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/huimou612/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact Python chess engine in under 4 KB: 0x88 board, alpha-beta search with quiescence, fixed node budget, and a small piece-square evaluation. It plays the house gauntlet through the make.fun env over HTTP.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

## Local practice

Practice trial-0 (6 games vs the house gauntlet): 3 wins, 3 losses. Wins against the depth-2, depth-3 and depth-4 house engines; losses to the node-capped 100k, 250k and 500k engines.

---

<sub>Entered on [make.fun](https://make.fun/?ref=vy4ejv7y&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
