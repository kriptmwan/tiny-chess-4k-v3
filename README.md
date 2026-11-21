# tiny-chess-4k-v3

A chess engine in 4 KB of Python for the make.fun tiny-chess-01 competition.

Sunfish-style MTD-bi search with a PeSTO-style tapered middlegame/endgame
evaluation, a compact general opening book, contempt-aware repetition
handling, and mate-distance pruning. Fixed node budget, fully deterministic.

- `main.py` — the whole engine (packed, <= 4,096 bytes)
- `engine.py` — the readable source (development copy, not committed)
