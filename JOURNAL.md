## Week 7 — Issue selection

**Issue link:** https://github.com/ascherj/pathreview/issues/34

**Issue title:** Implement a re-ranking step that uses an LLM to score retrieved chunks before generation

**Tier:** [ ] Tier 1  [ ] Tier 2  [Y] Tier 3

**Problem summary:**
Currently, chunks are retrieved and ranked based on a hybrid approach, using semantic and keyword search. However, this ranking is not in the perfect order, for example because keyword search might rank a document higher just because it contains a specific keyword multiple times. Hence, the need for re-ranking.

**Branch name:** feat/34-re-ranking-chunks

**Setup confirmation:** [Y] App runs locally at localhost:5173

**Cohort ledger:** [Y] Issue added to cohort ledger

## Week 8 — Reproduction & solution planning

**Reproduction commit link:** [link to commit documenting the reproduced issue]

**Reproduction summary:**
[1–2 sentences: How did you reproduce the issue? What did you observe?]

**PLAN.md link:** [link to PLAN.md in your fork]

**Walkthrough video (recommended):** [link to your Loom video, ≤2 min — recommended, not graded]

**Blockers or open questions:**
[Anything you're still uncertain about going into Week 9, or leave blank]