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
https://github.com/Phuc1Le/pathreview/commit/c5c9db5
This first commit is to fix another issue, keyword_score is always 0, which was reproduced and fix-verified with tests/unit/test_hybrid.py
https://github.com/Phuc1Le/pathreview/commit/81ea29f
This is the reproduction of issue #34
**Reproduction summary:**
[1–2 sentences: How did you reproduce the issue? What did you observe?]
I created a mock vector store with mock chunks, 2 of which are actual relevant chunk and keyword-stuffed chunk. Without the re ranker, the stuffed chunk score is higher than the actual relevant chunk.
**PLAN.md link:** [link to PLAN.md in your fork]

**Walkthrough video (recommended):** [link to your Loom video, ≤2 min — recommended, not graded]

**Blockers or open questions:**
[Anything you're still uncertain about going into Week 9, or leave blank]

53 failed, 378 passed, 2 warnings

## Week 9 — Solution building & PR submission

### Check-in 1 (mid-week)

**Current progress:**
[What have you implemented so far? Which sub-tasks from PLAN.md are done?]

**Next steps:**
[What are you working on for the rest of the week?]

**Blockers:**
[Anything slowing you down? Or leave blank.]

---

### Check-in 2 (end of week)

**PR link:** [link to your submitted pull request]

**Branch:** [the branch name you worked on, e.g. `fix/123-short-description`]

**What you built:**
[1–3 sentences summarizing what your fix does and how it works]

**Tests added or updated:**
[Which test files did you touch? What do they cover?]

**Self-review confirmation:** [ ] make check passes  [ ] make test-unit passes

**Draft PR feedback received from:** [name or Slack handle, or "none"]