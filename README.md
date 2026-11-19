# tiny-chess-01 v2

A 4 KB Python chess engine: 0x88 board, alpha-beta + transposition table +
captures-only quiescence, null-move pruning, late-move reductions, MVV-LVA
ordering, Sunfish piece-square tables, fixed 100,000 nodes per move.

`main.py` is the whole engine, packed from `src/engine.py` with
`makefun compress`. Run: `MAKEFUN_ENV_URL=<env> python3 main.py`.
