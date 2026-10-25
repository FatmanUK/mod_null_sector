# Pattern plan — Null Sector

Group membership is exclusive; each group contains at most four patterns. Patterns were written sequentially, group by group, beginning with pattern00.

| Group | Pattern members | Role |
| --- | --- | --- |
| A | 00 01 02 | First complete working state |
| B | 03 04 05 | Alternate working / pressure state |
| C | 06 07 08 | Alternate working / pressure state |
| D | 09 0a 0b | One-time terminal route and coda |

Group order: **A B C A C B A B C C D**.

A defines the patrol and its unanswered messages. B crosses G and A to return to B. C brings the bell replies closer while the bass keeps the same deliberate stride. The order returns through alternate access routes, then a single D group closes the sector with a spaced B-minor seal.

| Pattern | Harmonic bars | Fragments | Purpose |
| --- | --- | --- | --- |
| 00 | Bm, Bm, Bm, Bm | a / b | Patrol enters |
| 01 | Bm, Bm, Bm, Bm | b / a | Unanswered access |
| 02 | F#m, F#m, Bm, Bm | f / b | First turn |
| 03 | G, G, A, A | c / d | Alternate route |
| 04 | A, A, G, G | d / c | Door network |
| 05 | Bm, Bm, Bm, Bm | g / a | Return to patrol |
| 06 | Bm, Bm, Bm, Bm | e / a | Messages close in |
| 07 | F#m, F#m, Bm, Bm | f / e | Crosscheck |
| 08 | Bm, Bm, Bm, Bm | h / g | Sector confirmed |
| 09 | G, G, G, G | c / g | Seal route |
| 0a | A, A, A, A | d / h | Last access |
| 0b | Bm, Bm, Bm, Bm | a / independent coda | Airlock seal |

| Order position (hex) | Pattern |
| --- | --- |
| 00 | 00 |
| 01 | 01 |
| 02 | 02 |
| 03 | 03 |
| 04 | 04 |
| 05 | 05 |
| 06 | 06 |
| 07 | 07 |
| 08 | 08 |
| 09 | 00 |
| 0A | 01 |
| 0B | 02 |
| 0C | 06 |
| 0D | 07 |
| 0E | 08 |
| 0F | 03 |
| 10 | 04 |
| 11 | 05 |
| 12 | 00 |
| 13 | 01 |
| 14 | 02 |
| 15 | 03 |
| 16 | 04 |
| 17 | 05 |
| 18 | 06 |
| 19 | 07 |
| 1A | 08 |
| 1B | 06 |
| 1C | 07 |
| 1D | 08 |
| 1E | 09 |
| 1F | 0a |
| 20 | 0b |

Nominal duration is 240.000 seconds before terminal-row stop nuances. Standard MOD size estimate is 39,372 bytes, including 26,000 raw sample bytes and twelve pattern blocks. These are calculations, not compiled measurements.

All patterns have 64 logical rows. Omitted table rows are entirely empty rows; the compiler must expand them. There are no Dxx breaks, Bxx order jumps, E6x musical loops or tempo changes. Order-list reuse, rather than flow-control effects, creates the structure. The last pattern contains an articulated final flourish and F00. Player stop handling is pending validation.
