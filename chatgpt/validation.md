# Validation — Null Sector, revision 01

## Completed static checks

- Emitted table parsing: passed. Exactly four channel cells; decimal row labels 00–63 in increasing order; no duplicated or entirely empty rows; correct `--- -- ---` empty cells; uppercase instrument/effect hex. Each pattern expands to 64 logical rows.
- Metadata: passed. All required keys, matching title/speed/BPM, exact existing raw-source identities, legal volume defaults, zero finetunes, disabled loops and defined order references.
- Register checks: passed. Each written note obeys its per-instrument range; every unpitched hit is C-4. No chord sample or arpeggiator effect is requested. Sample monophony itself remains an audition question.
- Effect checks: passed. Only Cxx, tick cuts, the documented note delay where used, initial Fxx and terminal F00. All tick indices are below the piece’s speed; no slide or effect-memory dependencies.
- Group/order checks: passed. Exclusive groups of at most four patterns; all patterns numbered consecutively; final pattern occurs once at the final position.
- Full-order tick/volume simulation: passed. Trigger defaults, Cxx, ECx and ED1 event placement were followed through the actual order list. All four channel volumes are zero before the final F00. This does not emulate sample audio or establish audible balance.

Unique trigger events across distinct patterns: 818 decimal. Trigger events through the full order simulation: 2282 decimal.

Nominal duration: 240.000 seconds. Standard layout size estimate: 39,372 bytes; selected raw sample bytes: 26,000. Neither is an actual MOD measurement.

## Boundary test list

| From | To | Playback status |
| --- | --- | --- |
| 00 | 01 | Pending |
| 01 | 02 | Pending |
| 02 | 03 | Pending |
| 02 | 06 | Pending |
| 03 | 04 | Pending |
| 04 | 05 | Pending |
| 05 | 00 | Pending |
| 05 | 06 | Pending |
| 06 | 07 | Pending |
| 07 | 08 | Pending |
| 08 | 00 | Pending |
| 08 | 03 | Pending |
| 08 | 06 | Pending |
| 08 | 09 | Pending |
| 09 | 0a | Pending |
| 0a | 0b | Pending |

Play every occurrence as well as each distinct pair: a familiar pattern can read differently after a different group. Confirm sample-tail handoffs, phrase breathing, tonal transitions, percussion replacements and volume recovery. Test entry into the complete terminal group and the final F00 separately.

## Pending acceptance stages

| Stage | Status |
| --- | --- |
| ptgen compilation | Not run; compiler not supplied |
| Independent compiled MOD/header/period inspection | Pending an actual MOD |
| Sample import, monophony, tuning, register and balance auditions | Pending |
| Individual patterns and complete groups | Pending |
| Distinct boundaries and final stop/no-restart test | Pending |
| Full-track audition and musical acceptance | Pending |
| Actual file size and elapsed runtime | Unmeasured |

No static pass, numerical estimate or provisional source choice is an audition-confirmed result.
