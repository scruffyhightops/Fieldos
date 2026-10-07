ECTO Containment Concept 006.1 — transfer repair

Fixes:
- Transfer completion is guarded so it completes exactly once.
- Field Hold resumes correctly after operator intervention.
- Sector Reject reroutes and then resumes to completion.
- Reset clears all temporary transfer/popup/sector animation state.
- Transfer-route pulse, selected-grid pulse and trap-scan animation restored.
- Existing Concept 006 localStorage data remains in use (ecto_containment_006).

This is a repair build of 006, not a new feature phase.
