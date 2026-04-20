# Workflow

## High-level functional workflow
1. Confirm site ownership
2. Run manual diagnosis
3. Review prioritized findings
4. Apply hardening guidance
5. Re-run the same safe workflow

```mermaid
    flowchart TD
        S1["Confirm site ownership"]
    S2["Run manual diagnosis"]
    S3["Review prioritized findings"]
    S4["Apply hardening guidance"]
    S5["Re-run the same safe workflow"]
    S1 --> S2
    S2 --> S3
    S3 --> S4
    S4 --> S5
```

## Publication boundary
- The workflow is intentionally simplified.
- No internal rules, private thresholds, or sensitive processing detail are described here.
