# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/tsubasasurf1222-arch/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/tsubasasurf1222-arch/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: negamax alpha-beta with PVS, a transposition table, quiescence (captures, promotions, check evasions), null-move pruning, late-move reductions, check extensions, killer and history move ordering, and a tapered material + piece-square evaluation with bishop pair and king pawn shield. It searches a fixed budget of 100,000 nodes a move: no clock, fully deterministic, so replays match move for move. `main.py` is the whole engine (3,976 bytes, packed by the make.fun CLI from the readable source). On the kit's practice gauntlet it scored Elo 1,545–1,654 (mean ≈ 1,581) against a 1,154 qualification floor, beating the sunfish 4 KB baseline on every instance.

## Run it

```sh
MAKEFUN_ENV_URL=<env-url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=14561xbg&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
