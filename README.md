# Pocket Orchard

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![Rank](https://make.fun/badge/tiny-chess-01/leeeboo/makefun-tiny-chess-20261118/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![Reward](https://make.fun/badge/tiny-chess-01/leeeboo/makefun-tiny-chess-20261118/reward.svg)](https://make.fun/bounty/tiny-chess-01)

An original Python standard-library chess engine. Uses a 0x88 board,
iterative-deepening alpha-beta, capture search, move ordering, a transposition
table and tapered positional evaluation. A fixed node budget makes search
independent of elapsed time. No model calls or external chess code.

Run `python3 -P -s main.py` with `MAKEFUN_ENV_URL` set by the competition.
The engine sends JSON to `/game` and `/move` until the trial is complete.

`source.py` is the readable development source, retained separately in the
verification bundle, not in the submitted repository. The official compressor
produces the standalone `main.py`. Submit only `main.py`, this README and
LICENSE.

No gameplay score or runtime benchmark is claimed. Budget and chess strength
have not been verified against the live environment.

SPDX-License-Identifier: MIT
