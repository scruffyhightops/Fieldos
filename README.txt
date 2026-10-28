ECTO 008C.5.3 — CU-01 event-state and diagnostics recovery

Based on 008C.5.2. Preserves existing localStorage keys and offline operation.

Changes:
- Active automatic incident and affected sector visible in Engineering Diagnostics.
- Diagnostic sweep available while an automatic event is active.
- Controlled stalled-event recovery only after 12 seconds, blocked when an active alarm or engineering fault exists.
- Completed Event Director corrections restore sector stability to >=94.
- Stalled-event recovery clears only transient event state, preserving stored records and engineering faults.

Test CU-01 F6 Diagnostics, automatic incident alarm corrections, sectors 01 and 06, and VEH-01 functions.
