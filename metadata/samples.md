# Sample set — Null Sector

Status: provisional analytical selection from the actual supplied archives. Sample audition takes place after composition, as requested. The source bytes are not edited.

These are headerless raw sample files, interpreted provisionally as signed 8-bit mono PCM. There is no stored playback rate, note, finetune or loop metadata in these files. Confirm interpretation in the compiled import. All instrument finetunes are `00`; no pitch correction is silently applied.

| ID | Source | Role | Bytes (hex) | Peak | RMS quarters | DC | Rails % | Default volume |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 01 | ST-01/BassDrum2 | kick | 0BB8 | 127 | 41.20 / 29.45 / 6.64 / 2.51 | 0.98 | 0.00 | `35` |
| 02 | ST-01/PopSnare2 | snare | 0FA0 | 128 | 58.37 / 26.73 / 14.59 / 8.58 | 0.40 | 0.12 | `28` |
| 03 | ST-02/HiHat3 | hat | 0708 | 128 | 59.82 / 16.09 / 3.62 / 3.27 | 0.44 | 0.94 | `1E` |
| 04 | ST-01/TuneBass | bass | 12C0 | 115 | 44.49 / 26.63 / 12.01 / 4.44 | -0.07 | 0.00 | `33` |
| 05 | ST-01/ExBells | lead | 0DAC | 103 | 25.31 / 13.68 / 9.31 / 4.53 | -0.12 | 0.00 | `2C` |
| 06 | ST-01/KorgFilter | stab | 0D48 | 86 | 22.33 / 26.26 / 25.01 / 24.31 | -0.06 | 0.00 | `1B` |
| 07 | ST-01/WoodBlock | tick | 04B0 | 119 | 33.64 / 5.12 / 1.53 / 0.37 | -0.11 | 0.00 | `22` |
| 08 | ST-02/Cymbal2 | cymbal | 0CE4 | 128 | 68.83 / 40.59 / 10.75 / 3.39 | -0.25 | 1.55 | `19` |
| 09 | ST-01/SynClaves | tick2 | 03E8 | 127 | 46.12 / 11.81 / 4.26 / 1.51 | -0.16 | 0.10 | `1B` |

Signal measurements use decimal sample units; a signed sample lies from -128 to +127. RMS quarters are chronological, equal-duration portions of the unchanged file. Rail percentage counts samples exactly at -128 or +127; it is evidence of saturation risk, not proof of audible clipping. Volumes and IDs are hexadecimal.

- `01` ST-01/BassDrum2: Persistent low floor leaves room for quiet access signals.
- `02` ST-01/PopSnare2: Broader noise body without the largest rail-clipped alternatives.
- `03` ST-02/HiHat3: Dry initial noise with little late tail.
- `04` ST-01/TuneBass: Low recorded fundamental raised to octave-five trigger labels.
- `05` ST-01/ExBells: A pitched bell, played low; harmonic/inharmonic components need a by-ear single-note check.
- `06` ST-01/KorgFilter: Brief access light; it is not a sustained chord bed.
- `07` ST-01/WoodBlock: Dry access marker.
- `08` ST-02/Cymbal2: Occasional wider entry accent at a deliberately low default.
- `09` ST-01/SynClaves: Second access tick has a contrasting metallic body.

## Suitability, register and balance

Every pitched part is a single monophonic line; there are no chord samples or arpeggiator effects. Pitched sample spectra are broadly consistent with C-related harmonic material; this is provisional suitability evidence, not a by-ear confirmation that every source is an ideal single note. Inharmonic bells and attack noise should not be mistaken for deliberately layered chords.

Default volumes balance source RMS, peak and role. Percussion with large peaks is attenuated; the quiet CloseHiHat, when selected, uses its full source level. Per-row accents remain explicit in the tables. A lower default cannot undo clipping already present in source audio.

DXBass was excluded because its source has a very large DC offset. CowBell was excluded from these sets because of substantial rail occupancy and DC. Where a saturated kick/snare is selected, its grit is a deliberate provisional timbral choice and is identified above. No reverse or ping-pong behaviour is used.

All selected envelopes are used as finite events. No sustained pad role is required; see `loops.md` for loopability decisions and the KorgFilter seam diagnostic. The exact written pitch subsets and provisional source-root estimates are in `ranges.md`.

## Sample audition criteria — after composition

- Solo each instrument at every actual trigger pitch in `ranges.md`, using its metadata volume first. Confirm signed PCM interpretation, note identity, register, attack quality and tail behaviour.
- Compare bass and main voice on the same named tonic and fifth; allow their planned octave separation, then listen for unintended detuning or beating. Keep finetune zero unless the brief is explicitly changed.
- Check the pitched samples are perceived as single notes. If a source sounds like a fixed chord, report that source and exact trigger; do not approve it merely because the spectrum looked harmonic.
- Check low sample endings and every gate for clicks. Evaluate noisy percussion tails at both normal and quiet monitoring levels. Check deliberately saturated sources for useful grit versus objectionable harshness.
- Check kick/bass balance, main-voice intelligibility and hat/tick audibility in the complete ensemble and in mono. Compare the initial group with the densest group before deciding defaults.
- Preserve accepted by-ear sample volumes, loop changes, finetune and row edits in the actual auditioned project. Return that exact project with notes so the source can be reconciled.

Piece-specific check: Check that the low bells read as one pitch each rather than a premixed chord. Their gaps must retain tension while the drums remain active. Confirm bell tails survive the intended channel handoffs.
