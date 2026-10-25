# Trigger and tuning map — Null Sector

All written pitches stay inside C-3…B-5. These labels are the project’s compiler convention; confirm the C-3→period 856 and B-5→period 113 mapping before accepting the compiled import. Low sources are restricted to trigger octaves four/five; bright sources to three/four. All unpitched percussion is C-4.

| ID | Source | Permitted triggers | Actual written triggers |
| --- | --- | --- | --- |
| 01 | ST-01/BassDrum2 | C-4 only | C-4 |
| 02 | ST-01/PopSnare2 | C-4 only | C-4 |
| 03 | ST-02/HiHat3 | C-4 only | C-4 |
| 04 | ST-01/TuneBass | C-4…B-5 | C#5 D-5 E-5 F#5 G-5 A-5 B-5 |
| 05 | ST-01/ExBells | C-3…B-4 | F#3 G-3 A-3 B-3 C#4 D-4 E-4 F#4 |
| 06 | ST-01/KorgFilter | C-3…B-4 | F#3 G-3 A-3 B-3 |
| 07 | ST-01/WoodBlock | C-4 only | C-4 |
| 08 | ST-02/Cymbal2 | C-4 only | C-4 |
| 09 | ST-01/SynClaves | C-4 only | C-4 |

## Provisional pitch evidence

Raw sources have no stored sample rate. At a hypothetical PAL C-4 trigger period of 428, playback rate is about 8287 samples per second. Source-root estimates below use harmonic spacing and inspection of the measured spectrum, rather than treating its largest component as the fundamental.

| ID | Approximate C-4 sounding fundamental | Intended register implication |
| --- | --- | --- |
| 04 | 32.4 Hz | Low source: use upper trigger labels |
| 05 | 262.5 Hz | Higher source: keep lower trigger labels |
| 06 | 262.4 Hz | Higher source: keep lower trigger labels |

The figures are provisional estimates; short envelopes, harmonics, spectral spread and PAL/NTSC timing limit precision. Leader and MuteClav are approximately C-related mid voices; KorgFilter’s strong second harmonic is not an extra played note. ExBells, if selected, has inharmonic/chorused components that require especially careful by-ear checking. No finetune adjustment is authorised or applied.

Compare the actual tonic pitches between the bass and the melody after compilation, allowing their planned octave difference. A register-map pass does not confirm tuning or sample suitability by ear.
