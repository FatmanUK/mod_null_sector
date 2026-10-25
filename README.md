# Build handoff — Null Sector

This is revision 01 source only. The requested composition is complete; compilation and auditory validation have not been performed.

Use your established ptgen invocation with this directory’s `song.yaml` and all twelve `patternNN.md` files. The YAML follows the bootstrap: source keys `st01` / `st02`, exact archive-relative names, hexadecimal instrument IDs/volumes and zero finetunes. No unverified compiler command is invented here.

Provide the original sample archives or their unchanged extracted files using your normal ptgen source routing. This tarball does not duplicate those archives. Confirm the selected sample hashes in `sample_analysis.json`; there are no derivative sample edits.

After compilation inspect the actual MOD: four-channel signature, exact order, twelve 64-row patterns, valid periods, expected instrument defaults, zero finetunes and disabled loops. Expected size assumes original even-length sample files and exactly twelve pattern blocks. Confirm the actual size rather than treating the estimate as evidence.

The last row contains F00 as the intended stop. Verify actual stop behaviour in the user’s MilkyTracker version/replay mode and check no restart occurs. The composition has an authored coda before this command. Other MOD players may handle stop behaviour differently.

Follow sample criteria only after composition is complete (it now is), then pattern/group criteria, distinct boundary tests and full-track acceptance. Keep those stages separate. Return the actual edited/auditioned project with notes; accepted by-ear values outrank this initial source.

## Input archive identity

- `st-01.tar.gz` SHA-256: `34feb17a5130d5e45c032d28af04a9d9b6e6ef369316a203bd0df4ed4e3450ed`.
- `st-02.tar.gz` SHA-256: `39d170f7aa9a85e4ecefdd9221cc381567b886dd78060bac93c6668099bc0538`.
