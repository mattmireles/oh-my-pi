# COORD.md — session coordination ledger

Append-only, newest at the bottom, one line per substantive prompt when its work
lands: `- [YYYY-MM-DD HH:MMZ] [session-or-lane] <what was asked> -> <what landed> | evidence: <exit code / commit / path / status>`.
Honest entries only: in-progress is "in progress", untested is "untested". Keep
lines telegraphic (target <=300 chars - pointers, not prose). Compact to
COORD-ARCHIVE.md when the ledger exceeds ~8 KB: the budget is bytes, because
every session reads this tail at startup. In a fable-director arrangement, lane
blackboards live beside this file as COORD-<LANE>.md; this file is the ship/main ledger.

## LEDGER
- [2026-09-24 06:59Z] [hook] COORD.md scaffolded by oracle-suite SessionStart
