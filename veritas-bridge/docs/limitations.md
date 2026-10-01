# Limitations and Preserved Negative Evidence

Veritas Bridge intentionally distinguishes successful demonstrations from broader claims that the current evidence does not support.

This page is part of the public technical record because later success should not erase earlier failures, partial qualifications, or unresolved coverage gaps.

## Not established by the current public evidence

The current evidence does **not** establish:

1. Universal repair correctness or success across arbitrary repositories.
2. A published standardized software-engineering benchmark score.
3. Successful delegated-worker hierarchy behavior in the selected autonomous CHANGE run.
4. Deployment of the specific model-authored repair from that CHANGE run.
5. Equivalent end-to-end workflow behavior across arbitrary model replacements.
6. Complete installed network/process containment or immunity from compromise.
7. Preservation of every possible state owner through arbitrary incompatible or destructive migrations.
8. Infallible or independently corroborated reviewers.
9. Independent third-party reproduction or an external security audit.

These are boundaries of the evidence, not claims that future demonstrations are impossible.

## Preserved negative and partial results

### Delegated-worker qualifier

The stricter hierarchy qualification remained **failed_quality** in the selected successful repair record because delegated worker assignments/calls/result review were not exercised. The separately predeclared direct-repair contract passed.

**Correct interpretation:** a direct autonomous repair was demonstrated; delegated-worker orchestration was not demonstrated by that run.

### Earlier review-protocol failure

An earlier conversation-review page contained a JSON syntax error and the final conversation review deferred after engineering review accepted.

**Correct interpretation:** a repaired candidate and a complete autonomous handback are different achievements. That earlier run was not a full-loop pass.

### Earlier resource regression

An earlier proposal replay allocated roughly 16 MiB for oversized well-formed input and 48 MiB for malformed input, versus approximately 1–4 KiB in baseline probes; malformed-input disposition also changed.

**Correct interpretation:** functional repair does not establish resource safety. This result remains negative evidence rather than being overwritten by later successful runs.

### Earlier GUI rehearsal failure

A previous GUI rehearsal passed its baseline but terminated with an admission/concurrency error and both episodes were cancelled.

**Correct interpretation:** a passing baseline is not successful orchestration. The later NO CHANGE run is separate evidence.

### GUI evidence boundary

During the completed NO CHANGE run, browser automation attachment intermittently failed and screenshot capture failed while backend work continued. Final DOM state was retained.

**Correct interpretation:** terminal GUI state is supported, but pixel-level visual verification is not claimed for that portion of the run.

### Review independence

Some retained release/schema review records explicitly mark `independence_established: false` because review roles shared evidence.

**Correct interpretation:** review enforcement is supported; independent expert corroboration is not established by those records.

### Network/containment coverage

Installed containment acceptance has recorded successful scoped checks while broader network coverage remained incomplete.

**Correct interpretation:** scoped supervisor acceptance is not proof that every runtime, browser, plugin, launcher, or privileged process is confined.

## Claim language used by this repository

To avoid collapsing architecture, tests, and demonstrations into the same category, public documentation uses the following meanings:

- **Implemented** — present in inspected architecture/source.
- **Tested** — exercised by retained tests or probes.
- **Demonstrated** — supported by a completed recorded run.
- **Partially supported** — evidence exists but does not justify the broad form of the claim.
- **Not established** — not demonstrated by the current evidence.

## Why this matters

Veritas is designed around evidence-bound development. The same discipline should apply to claims about Veritas itself.

A successful later run does not retroactively convert a failed earlier run into a success. A test of one boundary does not become proof of universal security. A model judgment does not become independent corroboration simply because multiple review roles exist.

That distinction is intentional.
