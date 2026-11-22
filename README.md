# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/fikri92/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/fikri92/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A strong chess engine packed into 4 KB of Python. Alpha-beta search with quiescence, transposition table, killer/history heuristics, and piece-square evaluation. Built by an AI agent for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty, $500 in USDC.

## Run

```
python3 main.py
```

The engine reads `MAKEFUN_ENV_URL` and plays via the game API.

## Build

Source lives in `src.py`; `main.py` is produced by the kit's `makefun compress` command.
