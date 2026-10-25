# Loop decisions — Null Sector

No loops are enabled. This composition uses finite bass/pluck/bell phrases and explicit retriggers, not a sustained voice that requires a loop. Loop-disabled metadata is a composition decision; actual end quality remains an audition question.

| ID | Source | Loop decision | Start / length |
| --- | --- | --- | --- |
| 01 | ST-01/BassDrum2 | One-shot percussion; reject sustained use | Disabled |
| 02 | ST-01/PopSnare2 | One-shot percussion; reject sustained use | Disabled |
| 03 | ST-02/HiHat3 | One-shot percussion; reject sustained use | Disabled |
| 04 | ST-01/TuneBass | Finite pitched event; no loop required | Disabled |
| 05 | ST-01/ExBells | Finite pitched event; no loop required | Disabled |
| 06 | ST-01/KorgFilter | Finite pitched event; no loop required | Disabled |
| 07 | ST-01/WoodBlock | One-shot percussion; reject sustained use | Disabled |
| 08 | ST-02/Cymbal2 | One-shot percussion; reject sustained use | Disabled |
| 09 | ST-01/SynClaves | One-shot percussion; reject sustained use | Disabled |

The KorgFilter source is present in the supplied archives. A numerical even-byte seam candidate at start `04AE`, length `0278`, exclusive end `0726` has an endpoint difference of one sample unit but a 64-sample seam-context RMS mismatch of 9.327 sample units. Its body RMS is approximately 24–26 units. That context error is not a convincing basis for approving a musical sustain loop. This selected source therefore remains a finite stab.

These diagnostic positions are bytes in the unedited raw source. MOD repeat fields use words; no byte coordinates should be copied into a header without conversion. Optional ptgen `start` and `length` semantics are unverified, and these keys are absent from `song.yaml`. No loop candidate has been listened to or approved.

After compilation, check each instrument is actually non-looping. A conventional non-loop sentinel in the MOD header must not become an audible two-byte sustain. If a finite ending clicks, inspect that exact imported sample before proposing a trim, envelope edit or a new forward loop.
