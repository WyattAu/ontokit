# Pattern adoption

| Pattern | Status | Evidence |
|---|---|---|
| P83 | adopted | src/provenance.rs:1 (each mutation hash covers the previous head; reorder or removal breaks verification) |
| P102 | adopted | src/store.rs:40 (typed EntityStore over observations), src/provenance.rs:1 (lineage chain over mutations) |
