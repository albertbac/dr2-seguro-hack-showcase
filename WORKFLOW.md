# Workflow

## High-level functional workflow
1. Confirm site ownership
2. Run manual diagnosis
3. Review prioritized findings
4. Apply hardening guidance
5. Re-run the same safe workflow

```mermaid
    flowchart TD
        W1["Confirm site ownership"]
    W2["Run manual diagnosis"]
    W3["Review prioritized findings"]
    W4["Apply hardening guidance"]
    W5["Re-run the same safe workflow"]
    W1 --> W2
    W2 --> W3
    W3 --> W4
    W4 --> W5
```

## Publication boundary
- The workflow is intentionally simplified.
- No internal rules, private thresholds, or sensitive processing detail are described here.
