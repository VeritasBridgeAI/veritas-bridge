# Qualification Evidence

This page summarizes selected public-safe evidence from retained Veritas Bridge qualification records. The goal is to state **what happened, what the evidence supports, and what it does not support**.

The runs below are separate qualifications and should not be merged into a single composite experiment.

## A. Autonomous CHANGE qualification

**Date:** 28 September 2026  
**Outcome:** qualified candidate reached creator-approval boundary; no adoption occurred

### Recorded sequence

1. The acceptance contract was frozen before model execution.
2. A fresh uninterrupted investigation was launched.
3. The defective baseline was evaluated across 122 tests.
4. The run recorded **6 failures**, 0 errors, and 0 skips.
5. Veritas produced a new model-authored candidate associated with model/editor receipts.
6. The same suite evaluated the candidate at **122 / 122 passing**.
7. Six paired resource comparisons were recorded.
8. Required engineering, conversation-parent, and TMC boundary/decision checks completed.
9. The autonomous terminal state was **awaiting creator approval**.
10. No candidate adoption occurred in the run.

### Workload

- **87 settled model calls**
- **2,107,438 actual input + output tokens processed**

The token figure is cumulative across repeated calls during investigation, implementation, and review. It is not a single context window and is not a reserved allowance.

### Supported claim

A model-generated candidate corrected the measured defect under the recorded qualification without being automatically installed. Passing the frozen repair suite was followed by review and a separate approval boundary rather than implicit deployment authority.

### Important limits

- This demonstrates one bounded repair task, not universal software-repair competence.
- The stricter delegated-worker hierarchy qualifier did not pass in this selected run; direct repair and delegated orchestration are separate claims.
- The demonstrated candidate was not approved or deployed during this run.

## B. Autonomous NO CHANGE qualification

**Date:** 28 September 2026  
**Outcome:** accepted NO CHANGE

### Recorded sequence

- Actual GUI Start recorded at **08:11:28.686342 UTC**.
- Three targets were selected automatically for investigation.
- **122 individual test results passed** with 0 failures/errors/skips.
- Baseline and candidate identities were identical.
- The change set was empty.
- Six paired resource observations recorded **zero allocation deltas**.
- Engineering review completed and accepted.
- Conversation-parent review completed and accepted.
- Terminal NO CHANGE was recorded at **08:31:33.924447 UTC**.
- No candidate was adopted.
- Worker and lease cleanup completed successfully.

### Workload

- **53 settled model calls**
- **1,135,075 actual input + output tokens processed**
- **1,205.238 seconds** start-to-terminal, approximately **20 minutes 5 seconds**

### Supported claim

The admitted investigation supported leaving the tested sources unchanged. The terminal disposition, unchanged candidate identity, empty change set, successful checks, and completed reviews jointly support an intentional NO CHANGE outcome rather than a failed attempt to produce a patch.

### Important limits

- This does not prove the inspected modules contain no undiscovered defects.
- Reviewer judgments are not independent execution proof.
- Browser attachment issues prevented pixel-level screenshot verification for part of this run; backend completion and final DOM status were retained.

## C. Combined completed developmental workload

| Run | Model calls | Actual tokens processed |
| --- | ---: | ---: |
| Autonomous repair | 87 | 2,107,438 |
| NO CHANGE | 53 | 1,135,075 |
| **Combined** | **140** | **3,242,513** |

Earlier failed trials and ordinary chat are excluded from these totals.

## D. Rollback, re-adoption, and state continuity

**Date:** 14 September 2026  
**Type:** explicit operator qualification, not an autonomous model decision

### Completed sequence

1. Four declared canonical stores were recorded before changing release.
2. An explicit approved rollback was committed.
3. All four before/after store fingerprints matched across rollback.
4. The previous version was started and exercised through an authenticated client.
5. Legitimate activity was created while the previous version was active.
6. Fresh qualification and mandatory review occurred before re-adoption.
7. Explicit approved re-adoption selected the newer release.
8. All four current store fingerprints remained unchanged across re-adoption.
9. The re-adopted release started successfully and retained both earlier and intervening history.
10. Final shutdown and audit completed with no remaining execution leases.

### Results

- **4 declared canonical stores preserved**
- **16 / 16 round-trip checks passed**
- **14 / 14 independent final-audit checks passed**
- Approximately **31.1 minutes** elapsed

A separate whole-release qualification record also reports **646 CPU regressions** alongside round-trip and final-audit checks.

### Supported claim

For the registered compatible versions and four declared stores in the tested managed profile, rollback and fresh re-adoption did not erase legitimate intervening persistent activity.

### Important limits

This does not guarantee continuity for unregistered stores, arbitrary schema changes, incompatible releases, concurrent unaccounted writers, or destructive migrations.

## E. Authority-boundary evidence

The protected architecture distinguishes proposal, execution result, review, and deployment authorization.

Retained qualification and regression evidence includes rejection or denial for cases involving:

- evaluation without matching required review evidence;
- attempted policy downgrade or replacement of admitted review routes;
- reuse of stale review evidence after reviewer changes;
- forged or stale latest review material;
- missing or forged evaluation evidence;
- failed candidate status;
- altered or expired approval material;
- changed frozen cases;
- continuation after a persisted stop condition;
- attempts to reset cumulative budget state by reopening control state;
- operating-system access probes attempting protected controller/review/runner writes;
- runtime-identity access to protected approval material.

The tested boundary runs did not automatically alter production selection.

### What this establishes

Governance checks for approval, budget, stop state, source identity, and mandatory review exist outside the reasoning model and are exercised in retained tests/qualifications.

### What this does not establish

It is not proof of universal resistance to prompt injection, hostile privileged code, host compromise, every plugin/launcher/browser path, or every future model.

## Evidence availability

This public repository intentionally contains summarized evidence rather than raw protected logs, private fingerprints, credentials, authority payloads, proprietary prompts, or production source code.

Additional sanitized evidence may be made available during controlled technical diligence.
