# tiny-chess-01 entry

A chess engine in 4 KB of Python: negamax alpha-beta with PVS, a
transposition table, quiescence (captures, promotions, check evasions),
null-move pruning, late-move reductions, check extensions, killer and
history move ordering, and a tapered material + piece-square evaluation
with bishop pair and king pawn shield. It searches a fixed budget of
100,000 nodes a move: no clock, no randomness, so replays match.

main.py is the whole engine (packed by the makefun CLI from the readable
source). It plays the house gauntlet through the env at MAKEFUN_ENV_URL.
