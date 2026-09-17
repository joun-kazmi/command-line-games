# Command Line Games

A small collection of terminal-based games written in Python. These were early
programming exercises, so don't expect polished code or Python 3 support —
they're kept here as-is, warts and all.

## Games

### Battleship (`battleship/battle.py`)

Classic Battleship against the computer. Place your five ships on a 10x10
grid, then take turns calling out coordinates until one side sinks the
other's fleet.

Run it with:

```bash
python2 battleship/battle.py
```

### Rock, Paper, Scissors (`rock_paper_scissors/rockp.py`)

Play Rock, Paper, Scissors against the computer for as many rounds as you
like, then type `quit` to see the final score.

Run it with:

```bash
python2 rock_paper_scissors/rockp.py
```

### Tic-Tac-Toe (`tictactoe/`)

Two versions of Tic-Tac-Toe:

- `tict.py` — single player against a computer opponent (the computer plays
  a reasonably competent win/block/corner/center strategy).
- `tictac.py` — two player, played on the same terminal.

Run either with:

```bash
python2 tictactoe/tict.py
# or
python2 tictactoe/tictac.py
```

## Requirements

All three games are written in **Python 2** (they use `print` as a statement
and `raw_input()`), so they will not run under Python 3 without porting.
There are no external dependencies beyond the Python 2 standard library.

## Status

These are early, informal projects written for practice rather than
production use — no tests, no packaging, and no Python 3 port yet. They're
kept around as a record of early work rather than as actively maintained
software.
