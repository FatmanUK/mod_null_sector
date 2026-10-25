# Pattern 0b — Airlock seal

Group D; harmonic bars: Bm, Bm, Bm, Bm. Logical length: 64 rows. Status: complete source draft, not auditioned.

First half recalls a; the second half is the independently written seal sequence coda.

Ch1 persistent kicks with offset snares; Ch2 TuneBass; Ch3 low bell messages; Ch4 access stabs, hats and two contrasting ticks.

## Effects used here

Cxx sets channel volume immediately, from `00` silence to `40` maximum. Each written note includes its instrument; its default volume is restored at the next trigger before any row effect.
EC4 cuts that channel at tick 04 within the row; the next written trigger restores the sample default. There are no inherited slides or vibrato settings.
F00 requests playback stop on row 63. The final hit is followed by a fixed silence boundary, not a volume fade. Stop handling remains a required check in the compiled MOD and the user’s MilkyTracker replay mode.

| Row | Ch1 | Ch2 | Ch3 | Ch4 |
| --- | --- | --- | --- | --- |
| 00 | C-4 01 C35 | --- -- C00 | --- -- C00 | B-3 06 C1B |
| 01 | --- -- --- | B-5 04 --- | --- -- --- | --- -- --- |
| 02 | --- -- --- | --- -- --- | B-3 05 C2C | --- -- --- |
| 04 | C-4 01 C2F | --- -- --- | --- -- --- | --- -- --- |
| 05 | --- -- --- | F#5 04 --- | --- -- --- | --- -- --- |
| 06 | C-4 02 C28 | --- -- --- | --- -- --- | C-4 03 C1E |
| 08 | C-4 01 C35 | --- -- --- | --- -- --- | --- -- --- |
| 09 | --- -- --- | B-5 04 EC4 | --- -- --- | --- -- --- |
| 10 | --- -- --- | --- -- --- | --- -- --- | C-4 03 C1E |
| 12 | C-4 01 C2F | --- -- --- | F#4 05 C28 | --- -- --- |
| 13 | --- -- --- | D-5 04 --- | --- -- --- | --- -- --- |
| 14 | C-4 02 C28 | --- -- --- | --- -- --- | C-4 03 C1E |
| 15 | --- -- --- | --- -- --- | --- -- --- | C-4 07 C22 |
| 16 | C-4 01 C35 | --- -- --- | --- -- --- | C-4 09 C1B |
| 17 | --- -- --- | B-5 04 --- | --- -- --- | --- -- --- |
| 20 | C-4 01 C2F | --- -- --- | --- -- --- | C-4 03 C16 |
| 21 | --- -- --- | F#5 04 --- | --- -- --- | --- -- --- |
| 22 | C-4 02 C28 | --- -- --- | D-4 05 C2C | --- -- --- |
| 23 | --- -- --- | B-5 04 EC4 | --- -- --- | --- -- --- |
| 24 | C-4 01 C35 | --- -- --- | --- -- --- | C-4 03 C16 |
| 25 | --- -- --- | D-5 04 --- | --- -- --- | --- -- --- |
| 28 | C-4 01 C2F | --- -- --- | --- -- --- | C-4 03 C16 |
| 29 | --- -- --- | F#5 04 --- | --- -- --- | --- -- --- |
| 30 | C-4 02 C28 | --- -- --- | --- -- --- | --- -- --- |
| 31 | --- -- --- | --- -- --- | --- -- --- | C-4 07 C22 |
| 32 | C-4 01 C35 | --- -- --- | B-3 05 C2C | --- -- --- |
| 34 | --- -- --- | B-5 04 --- | --- -- --- | --- -- --- |
| 36 | C-4 02 C28 | --- -- --- | --- -- --- | --- -- --- |
| 37 | --- -- --- | --- -- --- | --- -- --- | C-4 09 C1B |
| 40 | C-4 01 C35 | --- -- --- | F#4 05 C28 | --- -- --- |
| 42 | --- -- --- | F#5 04 EC4 | --- -- --- | --- -- --- |
| 44 | C-4 02 C28 | --- -- --- | --- -- --- | --- -- --- |
| 45 | --- -- --- | --- -- --- | --- -- --- | C-4 07 C22 |
| 48 | C-4 01 C35 | --- -- --- | D-4 05 C2C | --- -- --- |
| 50 | --- -- --- | D-5 04 EC4 | --- -- --- | --- -- --- |
| 51 | --- -- --- | --- -- --- | --- -- --- | C-4 09 C1B |
| 54 | C-4 01 C35 | B-5 04 --- | B-3 05 C2C | C-4 08 C19 |
| 61 | --- -- C00 | --- -- C00 | --- -- C00 | --- -- C00 |
| 63 | --- -- F00 | --- -- --- | --- -- --- | --- -- --- |

## Audition criteria

- Listen to this entire pattern inside its complete group, then at every order-list occurrence. Check the melodic breath between the two halves, the bass response and the deliberate percussion handoffs.
- Check each EC cut and each percussion replacement of a pitched voice for a musically acceptable edge. Notes are single-voice events; tails can be deliberately interrupted on the same channel.
- Check balance in normal stereo and mono. The bass must remain a coherent line beneath the melodic signal, and short hats/ticks must remain audible without taking over.
- Check that the low bells read as one pitch each rather than a premixed chord. Their gaps must retain tension while the drums remain active. Confirm bell tails survive the intended channel handoffs.
- Check the last full group flows into the distinct flourish, the root landing is convincing, and the final cut does not steal a needed tail. Verify F00 stops, all channels are silent, and pattern00 does not restart.
